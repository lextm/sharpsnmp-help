# Discovery.GetResponse Method 
 

**Namespace:**&nbsp;<a href="N_Lextm_SharpSnmpLib_Messaging">Lextm.SharpSnmpLib.Messaging</a><br />**Assembly:**&nbsp;SharpSnmpLib (in SharpSnmpLib.dll) Version: 12.4.0+601762d0e653a71ebb69af963204dfbfb6c26b74

## Syntax

**C#**<br />
``` C#
public ReportMessage GetResponse(
	int timeout,
	IPEndPoint receiver
)
```

**VB**<br />
``` VB
Public Function GetResponse ( 
	timeout As Integer,
	receiver As IPEndPoint
) As ReportMessage
```

**C++**<br />
``` C++
public:
ReportMessage^ GetResponse(
	int timeout, 
	IPEndPoint^ receiver
)
```

**F#**<br />
``` F#
member GetResponse : 
        timeout : int * 
        receiver : IPEndPoint -> ReportMessage 

```


#### Parameters
&nbsp;<dl><dt>timeout</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.int32" target="_blank" rel="noopener noreferrer">System.Int32</a><br /></dd><dt>receiver</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.net.ipendpoint" target="_blank" rel="noopener noreferrer">System.Net.IPEndPoint</a><br /></dd></dl>

#### Return Value
Type: <a href="T_Lextm_SharpSnmpLib_Messaging_ReportMessage">ReportMessage</a>

## See Also


#### Reference
<a href="T_Lextm_SharpSnmpLib_Messaging_Discovery">Discovery Class</a><br /><a href="N_Lextm_SharpSnmpLib_Messaging">Lextm.SharpSnmpLib.Messaging Namespace</a><br />