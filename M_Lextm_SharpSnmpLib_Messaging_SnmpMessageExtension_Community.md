# SnmpMessageExtension.Community Method 
 

**Namespace:**&nbsp;<a href="N_Lextm_SharpSnmpLib_Messaging">Lextm.SharpSnmpLib.Messaging</a><br />**Assembly:**&nbsp;SharpSnmpLib (in SharpSnmpLib.dll) Version: 12.4.0+601762d0e653a71ebb69af963204dfbfb6c26b74

## Syntax

**C#**<br />
``` C#
public static OctetString Community(
	this ISnmpMessage message
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
Public Shared Function Community ( 
	message As ISnmpMessage
) As OctetString
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
static OctetString^ Community(
	ISnmpMessage^ message
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
static member Community : 
        message : ISnmpMessage -> OctetString 

```


#### Parameters
&nbsp;<dl><dt>message</dt><dd>Type: <a href="T_Lextm_SharpSnmpLib_Messaging_ISnmpMessage">Lextm.SharpSnmpLib.Messaging.ISnmpMessage</a><br /></dd></dl>

#### Return Value
Type: <a href="T_Lextm_SharpSnmpLib_OctetString">OctetString</a>

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type <a href="T_Lextm_SharpSnmpLib_Messaging_ISnmpMessage">ISnmpMessage</a>. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods" target="_blank" rel="noopener noreferrer">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods" target="_blank" rel="noopener noreferrer">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_Lextm_SharpSnmpLib_Messaging_SnmpMessageExtension">SnmpMessageExtension Class</a><br /><a href="N_Lextm_SharpSnmpLib_Messaging">Lextm.SharpSnmpLib.Messaging Namespace</a><br />