# PrivacyProviderExtension.ToSecurityLevel Method 
 

**Namespace:**&nbsp;<a href="N_Lextm_SharpSnmpLib_Security">Lextm.SharpSnmpLib.Security</a><br />**Assembly:**&nbsp;SharpSnmpLib (in SharpSnmpLib.dll) Version: 12.4.0+601762d0e653a71ebb69af963204dfbfb6c26b74

## Syntax

**C#**<br />
``` C#
public static Levels ToSecurityLevel(
	this IPrivacyProvider privacy
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
Public Shared Function ToSecurityLevel ( 
	privacy As IPrivacyProvider
) As Levels
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
static Levels ToSecurityLevel(
	IPrivacyProvider^ privacy
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
static member ToSecurityLevel : 
        privacy : IPrivacyProvider -> Levels 

```


#### Parameters
&nbsp;<dl><dt>privacy</dt><dd>Type: <a href="T_Lextm_SharpSnmpLib_Security_IPrivacyProvider">Lextm.SharpSnmpLib.Security.IPrivacyProvider</a><br /></dd></dl>

#### Return Value
Type: <a href="T_Lextm_SharpSnmpLib_Levels">Levels</a>

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type <a href="T_Lextm_SharpSnmpLib_Security_IPrivacyProvider">IPrivacyProvider</a>. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods" target="_blank" rel="noopener noreferrer">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods" target="_blank" rel="noopener noreferrer">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_Lextm_SharpSnmpLib_Security_PrivacyProviderExtension">PrivacyProviderExtension Class</a><br /><a href="N_Lextm_SharpSnmpLib_Security">Lextm.SharpSnmpLib.Security Namespace</a><br />