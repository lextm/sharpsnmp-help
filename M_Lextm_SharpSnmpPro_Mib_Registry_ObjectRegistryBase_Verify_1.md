# ObjectRegistryBase.Verify Method (String, String, ISnmpData)
 

Verifies the data against the object name defined in specified module.

**Namespace:**&nbsp;<a href="N_Lextm_SharpSnmpPro_Mib_Registry">Lextm.SharpSnmpPro.Mib.Registry</a><br />**Assembly:**&nbsp;SharpSnmpPro.Mib (in SharpSnmpPro.Mib.dll) Version: 2.1.2

## Syntax

**C#**<br />
``` C#
public bool Verify(
	string module,
	string name,
	ISnmpData data
)
```

**VB**<br />
``` VB
Public Function Verify ( 
	module As String,
	name As String,
	data As ISnmpData
) As Boolean
```

**C++**<br />
``` C++
public:
bool Verify(
	String^ module, 
	String^ name, 
	ISnmpData^ data
)
```

**F#**<br />
``` F#
member Verify : 
        module : string * 
        name : string * 
        data : ISnmpData -> bool 

```


#### Parameters
&nbsp;<dl><dt>module</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.string" target="_blank" rel="noopener noreferrer">System.String</a><br />The module.</dd><dt>name</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.string" target="_blank" rel="noopener noreferrer">System.String</a><br />The name.</dd><dt>data</dt><dd>Type: <a href="T_Lextm_SharpSnmpLib_ISnmpData">Lextm.SharpSnmpLib.ISnmpData</a><br />The data.</dd></dl>

#### Return Value
Type: <a href="https://docs.microsoft.com/dotnet/api/system.boolean" target="_blank" rel="noopener noreferrer">Boolean</a><br />

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td><a href="https://docs.microsoft.com/dotnet/api/system.invalidoperationexception" target="_blank" rel="noopener noreferrer">InvalidOperationException</a></td><td /></tr></table>

## See Also


#### Reference
<a href="T_Lextm_SharpSnmpPro_Mib_Registry_ObjectRegistryBase">ObjectRegistryBase Class</a><br /><a href="Overload_Lextm_SharpSnmpPro_Mib_Registry_ObjectRegistryBase_Verify">Verify Overload</a><br /><a href="N_Lextm_SharpSnmpPro_Mib_Registry">Lextm.SharpSnmpPro.Mib.Registry Namespace</a><br />