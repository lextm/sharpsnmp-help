# CompilerError Constructor (ErrorCategory, String, IConstruct[])
 

Initializes a new instance of the <a href="T_Lextm_SharpSnmpPro_Mib_Validation_CompilerError">CompilerError</a> class.

**Namespace:**&nbsp;<a href="N_Lextm_SharpSnmpPro_Mib_Validation">Lextm.SharpSnmpPro.Mib.Validation</a><br />**Assembly:**&nbsp;SharpSnmpPro.Mib (in SharpSnmpPro.Mib.dll) Version: 2.1.2

## Syntax

**C#**<br />
``` C#
public CompilerError(
	ErrorCategory category,
	string message,
	params IConstruct[] constructs
)
```

**VB**<br />
``` VB
Public Sub New ( 
	category As ErrorCategory,
	message As String,
	ParamArray constructs As IConstruct()
)
```

**C++**<br />
``` C++
public:
CompilerError(
	ErrorCategory category, 
	String^ message, 
	... array<IConstruct^>^ constructs
)
```

**F#**<br />
``` F#
new : 
        category : ErrorCategory * 
        message : string * 
        constructs : IConstruct[] -> CompilerError
```


#### Parameters
&nbsp;<dl><dt>category</dt><dd>Type: <a href="T_Lextm_SharpSnmpPro_Mib_Validation_ErrorCategory">Lextm.SharpSnmpPro.Mib.Validation.ErrorCategory</a><br />The category.</dd><dt>message</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.string" target="_blank" rel="noopener noreferrer">System.String</a><br />The message.</dd><dt>constructs</dt><dd>Type: <a href="T_Lextm_SharpSnmpPro_Mib_IConstruct">Lextm.SharpSnmpPro.Mib.IConstruct</a>[]<br />The constructs.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td><a href="https://docs.microsoft.com/dotnet/api/system.argumentexception" target="_blank" rel="noopener noreferrer">ArgumentException</a></td><td>Qualified constructs must be provided;constructs</td></tr></table>

## See Also


#### Reference
<a href="T_Lextm_SharpSnmpPro_Mib_Validation_CompilerError">CompilerError Class</a><br /><a href="Overload_Lextm_SharpSnmpPro_Mib_Validation_CompilerError__ctor">CompilerError Overload</a><br /><a href="N_Lextm_SharpSnmpPro_Mib_Validation">Lextm.SharpSnmpPro.Mib.Validation Namespace</a><br />