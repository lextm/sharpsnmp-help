# Messenger.Get Method 
 

**Namespace:**&nbsp;<a href="N_Lextm_SharpSnmpLib_Messaging">Lextm.SharpSnmpLib.Messaging</a><br />**Assembly:**&nbsp;SharpSnmpLib (in SharpSnmpLib.dll) Version: 12.4.0+601762d0e653a71ebb69af963204dfbfb6c26b74

## Syntax

**C#**<br />
``` C#
public static IList<Variable> Get(
	VersionCode version,
	IPEndPoint endpoint,
	OctetString community,
	IList<Variable> variables,
	int timeout
)
```

**VB**<br />
``` VB
Public Shared Function Get ( 
	version As VersionCode,
	endpoint As IPEndPoint,
	community As OctetString,
	variables As IList(Of Variable),
	timeout As Integer
) As IList(Of Variable)
```

**C++**<br />
``` C++
public:
static IList<Variable^>^ Get(
	VersionCode version, 
	IPEndPoint^ endpoint, 
	OctetString^ community, 
	IList<Variable^>^ variables, 
	int timeout
)
```

**F#**<br />
``` F#
static member Get : 
        version : VersionCode * 
        endpoint : IPEndPoint * 
        community : OctetString * 
        variables : IList<Variable> * 
        timeout : int -> IList<Variable> 

```


#### Parameters
&nbsp;<dl><dt>version</dt><dd>Type: <a href="T_Lextm_SharpSnmpLib_VersionCode">Lextm.SharpSnmpLib.VersionCode</a><br /></dd><dt>endpoint</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.net.ipendpoint" target="_blank" rel="noopener noreferrer">System.Net.IPEndPoint</a><br /></dd><dt>community</dt><dd>Type: <a href="T_Lextm_SharpSnmpLib_OctetString">Lextm.SharpSnmpLib.OctetString</a><br /></dd><dt>variables</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.collections.generic.ilist-1" target="_blank" rel="noopener noreferrer">System.Collections.Generic.IList</a>(<a href="T_Lextm_SharpSnmpLib_Variable">Variable</a>)<br /></dd><dt>timeout</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.int32" target="_blank" rel="noopener noreferrer">System.Int32</a><br /></dd></dl>

#### Return Value
Type: <a href="https://docs.microsoft.com/dotnet/api/system.collections.generic.ilist-1" target="_blank" rel="noopener noreferrer">IList</a>(<a href="T_Lextm_SharpSnmpLib_Variable">Variable</a>)

## See Also


#### Reference
<a href="T_Lextm_SharpSnmpLib_Messaging_Messenger">Messenger Class</a><br /><a href="N_Lextm_SharpSnmpLib_Messaging">Lextm.SharpSnmpLib.Messaging Namespace</a><br />