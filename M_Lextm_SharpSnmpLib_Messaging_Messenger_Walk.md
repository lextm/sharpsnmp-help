# Messenger.Walk Method 
 

**Namespace:**&nbsp;<a href="N_Lextm_SharpSnmpLib_Messaging">Lextm.SharpSnmpLib.Messaging</a><br />**Assembly:**&nbsp;SharpSnmpLib (in SharpSnmpLib.dll) Version: 12.4.0+601762d0e653a71ebb69af963204dfbfb6c26b74

## Syntax

**C#**<br />
``` C#
public static int Walk(
	VersionCode version,
	IPEndPoint endpoint,
	OctetString community,
	ObjectIdentifier table,
	IList<Variable> list,
	int timeout,
	WalkMode mode
)
```

**VB**<br />
``` VB
Public Shared Function Walk ( 
	version As VersionCode,
	endpoint As IPEndPoint,
	community As OctetString,
	table As ObjectIdentifier,
	list As IList(Of Variable),
	timeout As Integer,
	mode As WalkMode
) As Integer
```

**C++**<br />
``` C++
public:
static int Walk(
	VersionCode version, 
	IPEndPoint^ endpoint, 
	OctetString^ community, 
	ObjectIdentifier^ table, 
	IList<Variable^>^ list, 
	int timeout, 
	WalkMode mode
)
```

**F#**<br />
``` F#
static member Walk : 
        version : VersionCode * 
        endpoint : IPEndPoint * 
        community : OctetString * 
        table : ObjectIdentifier * 
        list : IList<Variable> * 
        timeout : int * 
        mode : WalkMode -> int 

```


#### Parameters
&nbsp;<dl><dt>version</dt><dd>Type: <a href="T_Lextm_SharpSnmpLib_VersionCode">Lextm.SharpSnmpLib.VersionCode</a><br /></dd><dt>endpoint</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.net.ipendpoint" target="_blank" rel="noopener noreferrer">System.Net.IPEndPoint</a><br /></dd><dt>community</dt><dd>Type: <a href="T_Lextm_SharpSnmpLib_OctetString">Lextm.SharpSnmpLib.OctetString</a><br /></dd><dt>table</dt><dd>Type: <a href="T_Lextm_SharpSnmpLib_ObjectIdentifier">Lextm.SharpSnmpLib.ObjectIdentifier</a><br /></dd><dt>list</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.collections.generic.ilist-1" target="_blank" rel="noopener noreferrer">System.Collections.Generic.IList</a>(<a href="T_Lextm_SharpSnmpLib_Variable">Variable</a>)<br /></dd><dt>timeout</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.int32" target="_blank" rel="noopener noreferrer">System.Int32</a><br /></dd><dt>mode</dt><dd>Type: <a href="T_Lextm_SharpSnmpLib_Messaging_WalkMode">Lextm.SharpSnmpLib.Messaging.WalkMode</a><br /></dd></dl>

#### Return Value
Type: <a href="https://docs.microsoft.com/dotnet/api/system.int32" target="_blank" rel="noopener noreferrer">Int32</a>

## See Also


#### Reference
<a href="T_Lextm_SharpSnmpLib_Messaging_Messenger">Messenger Class</a><br /><a href="N_Lextm_SharpSnmpLib_Messaging">Lextm.SharpSnmpLib.Messaging Namespace</a><br />