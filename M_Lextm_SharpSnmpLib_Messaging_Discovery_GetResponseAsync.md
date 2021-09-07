# Discovery.GetResponseAsync Method 
 

**Namespace:**&nbsp;<a href="N_Lextm_SharpSnmpLib_Messaging">Lextm.SharpSnmpLib.Messaging</a><br />**Assembly:**&nbsp;SharpSnmpLib (in SharpSnmpLib.dll) Version: 12.4.0+601762d0e653a71ebb69af963204dfbfb6c26b74

## Syntax

**C#**<br />
``` C#
public Task<ReportMessage> GetResponseAsync(
	IPEndPoint receiver
)
```

**VB**<br />
``` VB
Public Function GetResponseAsync ( 
	receiver As IPEndPoint
) As Task(Of ReportMessage)
```

**C++**<br />
``` C++
public:
Task<ReportMessage^>^ GetResponseAsync(
	IPEndPoint^ receiver
)
```

**F#**<br />
``` F#
member GetResponseAsync : 
        receiver : IPEndPoint -> Task<ReportMessage> 

```


#### Parameters
&nbsp;<dl><dt>receiver</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.net.ipendpoint" target="_blank" rel="noopener noreferrer">System.Net.IPEndPoint</a><br /></dd></dl>

#### Return Value
Type: <a href="https://docs.microsoft.com/dotnet/api/system.threading.tasks.task-1" target="_blank" rel="noopener noreferrer">Task</a>(<a href="T_Lextm_SharpSnmpLib_Messaging_ReportMessage">ReportMessage</a>)

## See Also


#### Reference
<a href="T_Lextm_SharpSnmpLib_Messaging_Discovery">Discovery Class</a><br /><a href="N_Lextm_SharpSnmpLib_Messaging">Lextm.SharpSnmpLib.Messaging Namespace</a><br />