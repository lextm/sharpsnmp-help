# TimeoutException.Create Method 
 

**Namespace:**&nbsp;<a href="N_Lextm_SharpSnmpLib_Messaging">Lextm.SharpSnmpLib.Messaging</a><br />**Assembly:**&nbsp;SharpSnmpLib (in SharpSnmpLib.dll) Version: 12.4.0+601762d0e653a71ebb69af963204dfbfb6c26b74

## Syntax

**C#**<br />
``` C#
public static TimeoutException Create(
	IPAddress agent,
	int timeout
)
```

**VB**<br />
``` VB
Public Shared Function Create ( 
	agent As IPAddress,
	timeout As Integer
) As TimeoutException
```

**C++**<br />
``` C++
public:
static TimeoutException^ Create(
	IPAddress^ agent, 
	int timeout
)
```

**F#**<br />
``` F#
static member Create : 
        agent : IPAddress * 
        timeout : int -> TimeoutException 

```


#### Parameters
&nbsp;<dl><dt>agent</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.net.ipaddress" target="_blank" rel="noopener noreferrer">System.Net.IPAddress</a><br /></dd><dt>timeout</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.int32" target="_blank" rel="noopener noreferrer">System.Int32</a><br /></dd></dl>

#### Return Value
Type: <a href="T_Lextm_SharpSnmpLib_Messaging_TimeoutException">TimeoutException</a>

## See Also


#### Reference
<a href="T_Lextm_SharpSnmpLib_Messaging_TimeoutException">TimeoutException Class</a><br /><a href="N_Lextm_SharpSnmpLib_Messaging">Lextm.SharpSnmpLib.Messaging Namespace</a><br />