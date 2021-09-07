# Manager.GetTable Method (IPAddress, String, ObjectIdentifier)
 

**Namespace:**&nbsp;<a href="N_Lextm_SharpSnmpLib_Messaging">Lextm.SharpSnmpLib.Messaging</a><br />**Assembly:**&nbsp;SharpSnmpLib (in SharpSnmpLib.dll) Version: 12.4.0+601762d0e653a71ebb69af963204dfbfb6c26b74

## Syntax

**C#**<br />
``` C#
public Variable[,] GetTable(
	IPAddress address,
	string community,
	ObjectIdentifier table
)
```

**VB**<br />
``` VB
Public Function GetTable ( 
	address As IPAddress,
	community As String,
	table As ObjectIdentifier
) As Variable(,)
```

**C++**<br />
``` C++
public:
array<Variable^,2>^ GetTable(
	IPAddress^ address, 
	String^ community, 
	ObjectIdentifier^ table
)
```

**F#**<br />
``` F#
member GetTable : 
        address : IPAddress * 
        community : string * 
        table : ObjectIdentifier -> Variable[,] 

```


#### Parameters
&nbsp;<dl><dt>address</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.net.ipaddress" target="_blank" rel="noopener noreferrer">System.Net.IPAddress</a><br /></dd><dt>community</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.string" target="_blank" rel="noopener noreferrer">System.String</a><br /></dd><dt>table</dt><dd>Type: <a href="T_Lextm_SharpSnmpLib_ObjectIdentifier">Lextm.SharpSnmpLib.ObjectIdentifier</a><br /></dd></dl>

#### Return Value
Type: <a href="T_Lextm_SharpSnmpLib_Variable">Variable</a>[,]

## See Also


#### Reference
<a href="T_Lextm_SharpSnmpLib_Messaging_Manager">Manager Class</a><br /><a href="Overload_Lextm_SharpSnmpLib_Messaging_Manager_GetTable">GetTable Overload</a><br /><a href="N_Lextm_SharpSnmpLib_Messaging">Lextm.SharpSnmpLib.Messaging Namespace</a><br />