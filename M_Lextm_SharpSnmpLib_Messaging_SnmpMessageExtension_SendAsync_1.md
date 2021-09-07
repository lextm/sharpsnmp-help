# SnmpMessageExtension.SendAsync Method (ISnmpMessage, EndPoint, Socket)
 

**Namespace:**&nbsp;<a href="N_Lextm_SharpSnmpLib_Messaging">Lextm.SharpSnmpLib.Messaging</a><br />**Assembly:**&nbsp;SharpSnmpLib (in SharpSnmpLib.dll) Version: 12.4.0+601762d0e653a71ebb69af963204dfbfb6c26b74

## Syntax

**C#**<br />
``` C#
public static Task SendAsync(
	this ISnmpMessage message,
	EndPoint manager,
	Socket socket
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
Public Shared Function SendAsync ( 
	message As ISnmpMessage,
	manager As EndPoint,
	socket As Socket
) As Task
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
static Task^ SendAsync(
	ISnmpMessage^ message, 
	EndPoint^ manager, 
	Socket^ socket
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
static member SendAsync : 
        message : ISnmpMessage * 
        manager : EndPoint * 
        socket : Socket -> Task 

```


#### Parameters
&nbsp;<dl><dt>message</dt><dd>Type: <a href="T_Lextm_SharpSnmpLib_Messaging_ISnmpMessage">Lextm.SharpSnmpLib.Messaging.ISnmpMessage</a><br /></dd><dt>manager</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.net.endpoint" target="_blank" rel="noopener noreferrer">System.Net.EndPoint</a><br /></dd><dt>socket</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.net.sockets.socket" target="_blank" rel="noopener noreferrer">System.Net.Sockets.Socket</a><br /></dd></dl>

#### Return Value
Type: <a href="https://docs.microsoft.com/dotnet/api/system.threading.tasks.task" target="_blank" rel="noopener noreferrer">Task</a>

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type <a href="T_Lextm_SharpSnmpLib_Messaging_ISnmpMessage">ISnmpMessage</a>. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods" target="_blank" rel="noopener noreferrer">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods" target="_blank" rel="noopener noreferrer">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_Lextm_SharpSnmpLib_Messaging_SnmpMessageExtension">SnmpMessageExtension Class</a><br /><a href="Overload_Lextm_SharpSnmpLib_Messaging_SnmpMessageExtension_SendAsync">SendAsync Overload</a><br /><a href="N_Lextm_SharpSnmpLib_Messaging">Lextm.SharpSnmpLib.Messaging Namespace</a><br />