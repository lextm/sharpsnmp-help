# ObjectRegistryBase.Translate Method (String, String)
 

Gets numerical form from textual form.

**Namespace:**&nbsp;<a href="N_Lextm_SharpSnmpPro_Mib_Registry">Lextm.SharpSnmpPro.Mib.Registry</a><br />**Assembly:**&nbsp;SharpSnmpPro.Mib (in SharpSnmpPro.Mib.dll) Version: 2.1.2

## Syntax

**C#**<br />
``` C#
public uint[] Translate(
	string moduleName,
	string name
)
```

**VB**<br />
``` VB
Public Function Translate ( 
	moduleName As String,
	name As String
) As UInteger()
```

**C++**<br />
``` C++
public:
array<unsigned int>^ Translate(
	String^ moduleName, 
	String^ name
)
```

**F#**<br />
``` F#
member Translate : 
        moduleName : string * 
        name : string -> uint32[] 

```


#### Parameters
&nbsp;<dl><dt>moduleName</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.string" target="_blank" rel="noopener noreferrer">System.String</a><br />Module name</dd><dt>name</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.string" target="_blank" rel="noopener noreferrer">System.String</a><br />Object name</dd></dl>

#### Return Value
Type: <a href="https://docs.microsoft.com/dotnet/api/system.uint32" target="_blank" rel="noopener noreferrer">UInt32</a>[]<br />

## See Also


#### Reference
<a href="T_Lextm_SharpSnmpPro_Mib_Registry_ObjectRegistryBase">ObjectRegistryBase Class</a><br /><a href="Overload_Lextm_SharpSnmpPro_Mib_Registry_ObjectRegistryBase_Translate">Translate Overload</a><br /><a href="N_Lextm_SharpSnmpPro_Mib_Registry">Lextm.SharpSnmpPro.Mib.Registry Namespace</a><br />