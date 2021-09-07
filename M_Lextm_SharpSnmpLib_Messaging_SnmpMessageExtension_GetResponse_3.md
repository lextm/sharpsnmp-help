# SnmpMessageExtension.GetResponse Method (ISnmpMessage, Int32, IPEndPoint, Socket)
 

**Namespace:**&nbsp;<a href="N_Lextm_SharpSnmpLib_Messaging">Lextm.SharpSnmpLib.Messaging</a><br />**Assembly:**&nbsp;SharpSnmpLib (in SharpSnmpLib.dll) Version: 12.4.0+601762d0e653a71ebb69af963204dfbfb6c26b74

## Syntax

**C#**<br />
``` C#
public static ISnmpMessage GetResponse(
	this ISnmpMessage request,
	int timeout,
	IPEndPoint receiver,
	Socket udpSocket
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
Public Shared Function GetResponse ( 
	request As ISnmpMessage,
	timeout As Integer,
	receiver As IPEndPoint,
	udpSocket As Socket
) As ISnmpMessage
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
static ISnmpMessage^ GetResponse(
	ISnmpMessage^ request, 
	int timeout, 
	IPEndPoint^ receiver, 
	Socket^ udpSocket
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
static member GetResponse : 
        request : ISnmpMessage * 
        timeout : int * 
        receiver : IPEndPoint * 
        udpSocket : Socket -> ISnmpMessage 

```


#### Parameters
&nbsp;<dl><dt>request</dt><dd>Type: <a href="T_Lextm_SharpSnmpLib_Messaging_ISnmpMessage">Lextm.SharpSnmpLib.Messaging.ISnmpMessage</a><br /></dd><dt>timeout</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.int32" target="_blank" rel="noopener noreferrer">System.Int32</a><br /></dd><dt>receiver</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.net.ipendpoint" target="_blank" rel="noopener noreferrer">System.Net.IPEndPoint</a><br /></dd><dt>udpSocket</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.net.sockets.socket" target="_blank" rel="noopener noreferrer">System.Net.Sockets.Socket</a><br /></dd></dl>

#### Return Value
Type: <a href="T_Lextm_SharpSnmpLib_Messaging_ISnmpMessage">ISnmpMessage</a>

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type <a href="T_Lextm_SharpSnmpLib_Messaging_ISnmpMessage">ISnmpMessage</a>. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods" target="_blank" rel="noopener noreferrer">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods" target="_blank" rel="noopener noreferrer">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_Lextm_SharpSnmpLib_Messaging_SnmpMessageExtension">SnmpMessageExtension Class</a><br /><a href="Overload_Lextm_SharpSnmpLib_Messaging_SnmpMessageExtension_GetResponse">GetResponse Overload</a><br /><a href="N_Lextm_SharpSnmpLib_Messaging">Lextm.SharpSnmpLib.Messaging Namespace</a><br />