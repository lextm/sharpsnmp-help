# Messenger.GetAsync Method 
 

**Namespace:**&nbsp;<a href="N_Lextm_SharpSnmpLib_Messaging">Lextm.SharpSnmpLib.Messaging</a><br />**Assembly:**&nbsp;SharpSnmpLib (in SharpSnmpLib.dll) Version: 12.4.0+601762d0e653a71ebb69af963204dfbfb6c26b74

## Syntax

**C#**<br />
``` C#
public static Task<IList<Variable>> GetAsync(
	VersionCode version,
	IPEndPoint endpoint,
	OctetString community,
	IList<Variable> variables
)
```

**VB**<br />
``` VB
Public Shared Function GetAsync ( 
	version As VersionCode,
	endpoint As IPEndPoint,
	community As OctetString,
	variables As IList(Of Variable)
) As Task(Of IList(Of Variable))
```

**C++**<br />
``` C++
public:
static Task<IList<Variable^>^>^ GetAsync(
	VersionCode version, 
	IPEndPoint^ endpoint, 
	OctetString^ community, 
	IList<Variable^>^ variables
)
```

**F#**<br />
``` F#
static member GetAsync : 
        version : VersionCode * 
        endpoint : IPEndPoint * 
        community : OctetString * 
        variables : IList<Variable> -> Task<IList<Variable>> 

```


#### Parameters
&nbsp;<dl><dt>version</dt><dd>Type: <a href="T_Lextm_SharpSnmpLib_VersionCode">Lextm.SharpSnmpLib.VersionCode</a><br /></dd><dt>endpoint</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.net.ipendpoint" target="_blank" rel="noopener noreferrer">System.Net.IPEndPoint</a><br /></dd><dt>community</dt><dd>Type: <a href="T_Lextm_SharpSnmpLib_OctetString">Lextm.SharpSnmpLib.OctetString</a><br /></dd><dt>variables</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.collections.generic.ilist-1" target="_blank" rel="noopener noreferrer">System.Collections.Generic.IList</a>(<a href="T_Lextm_SharpSnmpLib_Variable">Variable</a>)<br /></dd></dl>

#### Return Value
Type: <a href="https://docs.microsoft.com/dotnet/api/system.threading.tasks.task-1" target="_blank" rel="noopener noreferrer">Task</a>(<a href="https://docs.microsoft.com/dotnet/api/system.collections.generic.ilist-1" target="_blank" rel="noopener noreferrer">IList</a>(<a href="T_Lextm_SharpSnmpLib_Variable">Variable</a>))

## See Also


#### Reference
<a href="T_Lextm_SharpSnmpLib_Messaging_Messenger">Messenger Class</a><br /><a href="N_Lextm_SharpSnmpLib_Messaging">Lextm.SharpSnmpLib.Messaging Namespace</a><br />