# MessageFactory.ParseMessages Method (IEnumerable(Char), UserRegistry)
 

**Namespace:**&nbsp;<a href="N_Lextm_SharpSnmpLib_Messaging">Lextm.SharpSnmpLib.Messaging</a><br />**Assembly:**&nbsp;SharpSnmpLib (in SharpSnmpLib.dll) Version: 12.4.0+601762d0e653a71ebb69af963204dfbfb6c26b74

## Syntax

**C#**<br />
``` C#
public static IList<ISnmpMessage> ParseMessages(
	IEnumerable<char> bytes,
	UserRegistry registry
)
```

**VB**<br />
``` VB
Public Shared Function ParseMessages ( 
	bytes As IEnumerable(Of Char),
	registry As UserRegistry
) As IList(Of ISnmpMessage)
```

**C++**<br />
``` C++
public:
static IList<ISnmpMessage^>^ ParseMessages(
	IEnumerable<wchar_t>^ bytes, 
	UserRegistry^ registry
)
```

**F#**<br />
``` F#
static member ParseMessages : 
        bytes : IEnumerable<char> * 
        registry : UserRegistry -> IList<ISnmpMessage> 

```


#### Parameters
&nbsp;<dl><dt>bytes</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.collections.generic.ienumerable-1" target="_blank" rel="noopener noreferrer">System.Collections.Generic.IEnumerable</a>(<a href="https://docs.microsoft.com/dotnet/api/system.char" target="_blank" rel="noopener noreferrer">Char</a>)<br /></dd><dt>registry</dt><dd>Type: <a href="T_Lextm_SharpSnmpLib_Security_UserRegistry">Lextm.SharpSnmpLib.Security.UserRegistry</a><br /></dd></dl>

#### Return Value
Type: <a href="https://docs.microsoft.com/dotnet/api/system.collections.generic.ilist-1" target="_blank" rel="noopener noreferrer">IList</a>(<a href="T_Lextm_SharpSnmpLib_Messaging_ISnmpMessage">ISnmpMessage</a>)

## See Also


#### Reference
<a href="T_Lextm_SharpSnmpLib_Messaging_MessageFactory">MessageFactory Class</a><br /><a href="Overload_Lextm_SharpSnmpLib_Messaging_MessageFactory_ParseMessages">ParseMessages Overload</a><br /><a href="N_Lextm_SharpSnmpLib_Messaging">Lextm.SharpSnmpLib.Messaging Namespace</a><br />