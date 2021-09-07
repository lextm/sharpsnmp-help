# MessageFactory.ParseMessages Method (Byte[], Int32, Int32, UserRegistry)
 

**Namespace:**&nbsp;<a href="N_Lextm_SharpSnmpLib_Messaging">Lextm.SharpSnmpLib.Messaging</a><br />**Assembly:**&nbsp;SharpSnmpLib (in SharpSnmpLib.dll) Version: 12.4.0+601762d0e653a71ebb69af963204dfbfb6c26b74

## Syntax

**C#**<br />
``` C#
public static IList<ISnmpMessage> ParseMessages(
	byte[] buffer,
	int index,
	int length,
	UserRegistry registry
)
```

**VB**<br />
``` VB
Public Shared Function ParseMessages ( 
	buffer As Byte(),
	index As Integer,
	length As Integer,
	registry As UserRegistry
) As IList(Of ISnmpMessage)
```

**C++**<br />
``` C++
public:
static IList<ISnmpMessage^>^ ParseMessages(
	array<unsigned char>^ buffer, 
	int index, 
	int length, 
	UserRegistry^ registry
)
```

**F#**<br />
``` F#
static member ParseMessages : 
        buffer : byte[] * 
        index : int * 
        length : int * 
        registry : UserRegistry -> IList<ISnmpMessage> 

```


#### Parameters
&nbsp;<dl><dt>buffer</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.byte" target="_blank" rel="noopener noreferrer">System.Byte</a>[]<br /></dd><dt>index</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.int32" target="_blank" rel="noopener noreferrer">System.Int32</a><br /></dd><dt>length</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.int32" target="_blank" rel="noopener noreferrer">System.Int32</a><br /></dd><dt>registry</dt><dd>Type: <a href="T_Lextm_SharpSnmpLib_Security_UserRegistry">Lextm.SharpSnmpLib.Security.UserRegistry</a><br /></dd></dl>

#### Return Value
Type: <a href="https://docs.microsoft.com/dotnet/api/system.collections.generic.ilist-1" target="_blank" rel="noopener noreferrer">IList</a>(<a href="T_Lextm_SharpSnmpLib_Messaging_ISnmpMessage">ISnmpMessage</a>)

## See Also


#### Reference
<a href="T_Lextm_SharpSnmpLib_Messaging_MessageFactory">MessageFactory Class</a><br /><a href="Overload_Lextm_SharpSnmpLib_Messaging_MessageFactory_ParseMessages">ParseMessages Overload</a><br /><a href="N_Lextm_SharpSnmpLib_Messaging">Lextm.SharpSnmpLib.Messaging Namespace</a><br />