# Manager.Set Method (IPAddress, String, IList(Variable))
 

**Namespace:**&nbsp;<a href="N_Lextm_SharpSnmpLib_Messaging">Lextm.SharpSnmpLib.Messaging</a><br />**Assembly:**&nbsp;SharpSnmpLib (in SharpSnmpLib.dll) Version: 12.4.0+601762d0e653a71ebb69af963204dfbfb6c26b74

## Syntax

**C#**<br />
``` C#
public IList<Variable> Set(
	IPAddress address,
	string community,
	IList<Variable> variables
)
```

**VB**<br />
``` VB
Public Function Set ( 
	address As IPAddress,
	community As String,
	variables As IList(Of Variable)
) As IList(Of Variable)
```

**C++**<br />
``` C++
public:
IList<Variable^>^ Set(
	IPAddress^ address, 
	String^ community, 
	IList<Variable^>^ variables
)
```

**F#**<br />
``` F#
member Set : 
        address : IPAddress * 
        community : string * 
        variables : IList<Variable> -> IList<Variable> 

```


#### Parameters
&nbsp;<dl><dt>address</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.net.ipaddress" target="_blank" rel="noopener noreferrer">System.Net.IPAddress</a><br /></dd><dt>community</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.string" target="_blank" rel="noopener noreferrer">System.String</a><br /></dd><dt>variables</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.collections.generic.ilist-1" target="_blank" rel="noopener noreferrer">System.Collections.Generic.IList</a>(<a href="T_Lextm_SharpSnmpLib_Variable">Variable</a>)<br /></dd></dl>

#### Return Value
Type: <a href="https://docs.microsoft.com/dotnet/api/system.collections.generic.ilist-1" target="_blank" rel="noopener noreferrer">IList</a>(<a href="T_Lextm_SharpSnmpLib_Variable">Variable</a>)

## See Also


#### Reference
<a href="T_Lextm_SharpSnmpLib_Messaging_Manager">Manager Class</a><br /><a href="Overload_Lextm_SharpSnmpLib_Messaging_Manager_Set">Set Overload</a><br /><a href="N_Lextm_SharpSnmpLib_Messaging">Lextm.SharpSnmpLib.Messaging Namespace</a><br />