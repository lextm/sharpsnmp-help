# CompilerError Constructor (ErrorCategory, String, IToken, String)
 

Initializes a new instance of the <a href="T_Lextm_SharpSnmpPro_Mib_Validation_CompilerError">CompilerError</a> class.

**Namespace:**&nbsp;<a href="N_Lextm_SharpSnmpPro_Mib_Validation">Lextm.SharpSnmpPro.Mib.Validation</a><br />**Assembly:**&nbsp;SharpSnmpPro.Mib (in SharpSnmpPro.Mib.dll) Version: 2.1.2

## Syntax

**C#**<br />
``` C#
public CompilerError(
	ErrorCategory category,
	string message,
	IToken token,
	string fileName
)
```

**VB**<br />
``` VB
Public Sub New ( 
	category As ErrorCategory,
	message As String,
	token As IToken,
	fileName As String
)
```

**C++**<br />
``` C++
public:
CompilerError(
	ErrorCategory category, 
	String^ message, 
	IToken^ token, 
	String^ fileName
)
```

**F#**<br />
``` F#
new : 
        category : ErrorCategory * 
        message : string * 
        token : IToken * 
        fileName : string -> CompilerError
```


#### Parameters
&nbsp;<dl><dt>category</dt><dd>Type: <a href="T_Lextm_SharpSnmpPro_Mib_Validation_ErrorCategory">Lextm.SharpSnmpPro.Mib.Validation.ErrorCategory</a><br />The category.</dd><dt>message</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.string" target="_blank" rel="noopener noreferrer">System.String</a><br />The message.</dd><dt>token</dt><dd>Type: IToken<br />The token.</dd><dt>fileName</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.string" target="_blank" rel="noopener noreferrer">System.String</a><br />Name of the file.</dd></dl>

## See Also


#### Reference
<a href="T_Lextm_SharpSnmpPro_Mib_Validation_CompilerError">CompilerError Class</a><br /><a href="Overload_Lextm_SharpSnmpPro_Mib_Validation_CompilerError__ctor">CompilerError Overload</a><br /><a href="N_Lextm_SharpSnmpPro_Mib_Validation">Lextm.SharpSnmpPro.Mib.Validation Namespace</a><br />