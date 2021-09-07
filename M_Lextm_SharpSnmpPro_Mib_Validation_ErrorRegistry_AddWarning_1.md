# ErrorRegistry.AddWarning Method (WarningCategory, String, IConstruct[])
 

Adds a warning.

**Namespace:**&nbsp;<a href="N_Lextm_SharpSnmpPro_Mib_Validation">Lextm.SharpSnmpPro.Mib.Validation</a><br />**Assembly:**&nbsp;SharpSnmpPro.Mib (in SharpSnmpPro.Mib.dll) Version: 2.1.2

## Syntax

**C#**<br />
``` C#
public void AddWarning(
	WarningCategory category,
	string message,
	params IConstruct[] constructs
)
```

**VB**<br />
``` VB
Public Sub AddWarning ( 
	category As WarningCategory,
	message As String,
	ParamArray constructs As IConstruct()
)
```

**C++**<br />
``` C++
public:
void AddWarning(
	WarningCategory category, 
	String^ message, 
	... array<IConstruct^>^ constructs
)
```

**F#**<br />
``` F#
member AddWarning : 
        category : WarningCategory * 
        message : string * 
        constructs : IConstruct[] -> unit 

```


#### Parameters
&nbsp;<dl><dt>category</dt><dd>Type: <a href="T_Lextm_SharpSnmpPro_Mib_Validation_WarningCategory">Lextm.SharpSnmpPro.Mib.Validation.WarningCategory</a><br />The category.</dd><dt>message</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.string" target="_blank" rel="noopener noreferrer">System.String</a><br />The message.</dd><dt>constructs</dt><dd>Type: <a href="T_Lextm_SharpSnmpPro_Mib_IConstruct">Lextm.SharpSnmpPro.Mib.IConstruct</a>[]<br />The constructs.</dd></dl>

## See Also


#### Reference
<a href="T_Lextm_SharpSnmpPro_Mib_Validation_ErrorRegistry">ErrorRegistry Class</a><br /><a href="Overload_Lextm_SharpSnmpPro_Mib_Validation_ErrorRegistry_AddWarning">AddWarning Overload</a><br /><a href="N_Lextm_SharpSnmpPro_Mib_Validation">Lextm.SharpSnmpPro.Mib.Validation Namespace</a><br />