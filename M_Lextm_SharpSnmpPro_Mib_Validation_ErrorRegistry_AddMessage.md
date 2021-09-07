# ErrorRegistry.AddMessage Method (MessageCategory, String, IToken, String)
 

Adds a message.

**Namespace:**&nbsp;<a href="N_Lextm_SharpSnmpPro_Mib_Validation">Lextm.SharpSnmpPro.Mib.Validation</a><br />**Assembly:**&nbsp;SharpSnmpPro.Mib (in SharpSnmpPro.Mib.dll) Version: 2.1.2

## Syntax

**C#**<br />
``` C#
public void AddMessage(
	MessageCategory category,
	string message,
	IToken token,
	string fileName
)
```

**VB**<br />
``` VB
Public Sub AddMessage ( 
	category As MessageCategory,
	message As String,
	token As IToken,
	fileName As String
)
```

**C++**<br />
``` C++
public:
void AddMessage(
	MessageCategory category, 
	String^ message, 
	IToken^ token, 
	String^ fileName
)
```

**F#**<br />
``` F#
member AddMessage : 
        category : MessageCategory * 
        message : string * 
        token : IToken * 
        fileName : string -> unit 

```


#### Parameters
&nbsp;<dl><dt>category</dt><dd>Type: <a href="T_Lextm_SharpSnmpPro_Mib_Validation_MessageCategory">Lextm.SharpSnmpPro.Mib.Validation.MessageCategory</a><br />The category.</dd><dt>message</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.string" target="_blank" rel="noopener noreferrer">System.String</a><br />The message.</dd><dt>token</dt><dd>Type: IToken<br />The token.</dd><dt>fileName</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.string" target="_blank" rel="noopener noreferrer">System.String</a><br />Name of the file.</dd></dl>

## See Also


#### Reference
<a href="T_Lextm_SharpSnmpPro_Mib_Validation_ErrorRegistry">ErrorRegistry Class</a><br /><a href="Overload_Lextm_SharpSnmpPro_Mib_Validation_ErrorRegistry_AddMessage">AddMessage Overload</a><br /><a href="N_Lextm_SharpSnmpPro_Mib_Validation">Lextm.SharpSnmpPro.Mib.Validation Namespace</a><br />