# ObjectIdentityMacro Constructor (String, String, IEntity, UInt32, Boolean)
 

Initializes a new instance of the <a href="T_Lextm_SharpSnmpPro_Mib_ObjectIdentityMacro">ObjectIdentityMacro</a> class

**Namespace:**&nbsp;<a href="N_Lextm_SharpSnmpPro_Mib">Lextm.SharpSnmpPro.Mib</a><br />**Assembly:**&nbsp;SharpSnmpPro.Mib (in SharpSnmpPro.Mib.dll) Version: 2.1.2

## Syntax

**C#**<br />
``` C#
public ObjectIdentityMacro(
	string moduleName,
	string name,
	IEntity parent,
	uint value,
	bool lockModule = false
)
```

**VB**<br />
``` VB
Public Sub New ( 
	moduleName As String,
	name As String,
	parent As IEntity,
	value As UInteger,
	Optional lockModule As Boolean = false
)
```

**C++**<br />
``` C++
public:
ObjectIdentityMacro(
	String^ moduleName, 
	String^ name, 
	IEntity^ parent, 
	unsigned int value, 
	bool lockModule = false
)
```

**F#**<br />
``` F#
new : 
        moduleName : string * 
        name : string * 
        parent : IEntity * 
        value : uint32 * 
        ?lockModule : bool 
(* Defaults:
        let _lockModule = defaultArg lockModule false
*)
-> ObjectIdentityMacro
```


#### Parameters
&nbsp;<dl><dt>moduleName</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.string" target="_blank" rel="noopener noreferrer">System.String</a><br /></dd><dt>name</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.string" target="_blank" rel="noopener noreferrer">System.String</a><br /></dd><dt>parent</dt><dd>Type: <a href="T_Lextm_SharpSnmpPro_Mib_IEntity">Lextm.SharpSnmpPro.Mib.IEntity</a><br /></dd><dt>value</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.uint32" target="_blank" rel="noopener noreferrer">System.UInt32</a><br /></dd><dt>lockModule (Optional)</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.boolean" target="_blank" rel="noopener noreferrer">System.Boolean</a><br /></dd></dl>

## See Also


#### Reference
<a href="T_Lextm_SharpSnmpPro_Mib_ObjectIdentityMacro">ObjectIdentityMacro Class</a><br /><a href="Overload_Lextm_SharpSnmpPro_Mib_ObjectIdentityMacro__ctor">ObjectIdentityMacro Overload</a><br /><a href="N_Lextm_SharpSnmpPro_Mib">Lextm.SharpSnmpPro.Mib Namespace</a><br />