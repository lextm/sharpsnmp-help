# ObjectRegistryBase.Verify Method (ObjectIdentifier, ISnmpData)
 

Verifies the data against the object identifier.

**Namespace:**&nbsp;<a href="N_Lextm_SharpSnmpPro_Mib_Registry">Lextm.SharpSnmpPro.Mib.Registry</a><br />**Assembly:**&nbsp;SharpSnmpPro.Mib (in SharpSnmpPro.Mib.dll) Version: 2.1.2

## Syntax

**C#**<br />
``` C#
public bool Verify(
	ObjectIdentifier oid,
	ISnmpData data
)
```

**VB**<br />
``` VB
Public Function Verify ( 
	oid As ObjectIdentifier,
	data As ISnmpData
) As Boolean
```

**C++**<br />
``` C++
public:
bool Verify(
	ObjectIdentifier^ oid, 
	ISnmpData^ data
)
```

**F#**<br />
``` F#
member Verify : 
        oid : ObjectIdentifier * 
        data : ISnmpData -> bool 

```


#### Parameters
&nbsp;<dl><dt>oid</dt><dd>Type: <a href="T_Lextm_SharpSnmpLib_ObjectIdentifier">Lextm.SharpSnmpLib.ObjectIdentifier</a><br />The object identifier.</dd><dt>data</dt><dd>Type: <a href="T_Lextm_SharpSnmpLib_ISnmpData">Lextm.SharpSnmpLib.ISnmpData</a><br />The data.</dd></dl>

#### Return Value
Type: <a href="https://docs.microsoft.com/dotnet/api/system.boolean" target="_blank" rel="noopener noreferrer">Boolean</a><br />

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td><a href="https://docs.microsoft.com/dotnet/api/system.invalidoperationexception" target="_blank" rel="noopener noreferrer">InvalidOperationException</a></td><td /></tr></table>

## See Also


#### Reference
<a href="T_Lextm_SharpSnmpPro_Mib_Registry_ObjectRegistryBase">ObjectRegistryBase Class</a><br /><a href="Overload_Lextm_SharpSnmpPro_Mib_Registry_ObjectRegistryBase_Verify">Verify Overload</a><br /><a href="N_Lextm_SharpSnmpPro_Mib_Registry">Lextm.SharpSnmpPro.Mib.Registry Namespace</a><br />