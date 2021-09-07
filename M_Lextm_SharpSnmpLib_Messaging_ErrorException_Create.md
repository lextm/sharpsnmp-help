# ErrorException.Create Method 
 

**Namespace:**&nbsp;<a href="N_Lextm_SharpSnmpLib_Messaging">Lextm.SharpSnmpLib.Messaging</a><br />**Assembly:**&nbsp;SharpSnmpLib (in SharpSnmpLib.dll) Version: 12.4.0+601762d0e653a71ebb69af963204dfbfb6c26b74

## Syntax

**C#**<br />
``` C#
public static ErrorException Create(
	string message,
	IPAddress agent,
	ISnmpMessage body
)
```

**VB**<br />
``` VB
Public Shared Function Create ( 
	message As String,
	agent As IPAddress,
	body As ISnmpMessage
) As ErrorException
```

**C++**<br />
``` C++
public:
static ErrorException^ Create(
	String^ message, 
	IPAddress^ agent, 
	ISnmpMessage^ body
)
```

**F#**<br />
``` F#
static member Create : 
        message : string * 
        agent : IPAddress * 
        body : ISnmpMessage -> ErrorException 

```


#### Parameters
&nbsp;<dl><dt>message</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.string" target="_blank" rel="noopener noreferrer">System.String</a><br /></dd><dt>agent</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.net.ipaddress" target="_blank" rel="noopener noreferrer">System.Net.IPAddress</a><br /></dd><dt>body</dt><dd>Type: <a href="T_Lextm_SharpSnmpLib_Messaging_ISnmpMessage">Lextm.SharpSnmpLib.Messaging.ISnmpMessage</a><br /></dd></dl>

#### Return Value
Type: <a href="T_Lextm_SharpSnmpLib_Messaging_ErrorException">ErrorException</a>

## See Also


#### Reference
<a href="T_Lextm_SharpSnmpLib_Messaging_ErrorException">ErrorException Class</a><br /><a href="N_Lextm_SharpSnmpLib_Messaging">Lextm.SharpSnmpLib.Messaging Namespace</a><br />