# Messenger.SendTrapV2Async Method 
 

**Namespace:**&nbsp;<a href="N_Lextm_SharpSnmpLib_Messaging">Lextm.SharpSnmpLib.Messaging</a><br />**Assembly:**&nbsp;SharpSnmpLib (in SharpSnmpLib.dll) Version: 12.4.0+601762d0e653a71ebb69af963204dfbfb6c26b74

## Syntax

**C#**<br />
``` C#
public static Task SendTrapV2Async(
	int requestId,
	VersionCode version,
	EndPoint receiver,
	OctetString community,
	ObjectIdentifier enterprise,
	uint timestamp,
	IList<Variable> variables
)
```

**VB**<br />
``` VB
Public Shared Function SendTrapV2Async ( 
	requestId As Integer,
	version As VersionCode,
	receiver As EndPoint,
	community As OctetString,
	enterprise As ObjectIdentifier,
	timestamp As UInteger,
	variables As IList(Of Variable)
) As Task
```

**C++**<br />
``` C++
public:
static Task^ SendTrapV2Async(
	int requestId, 
	VersionCode version, 
	EndPoint^ receiver, 
	OctetString^ community, 
	ObjectIdentifier^ enterprise, 
	unsigned int timestamp, 
	IList<Variable^>^ variables
)
```

**F#**<br />
``` F#
static member SendTrapV2Async : 
        requestId : int * 
        version : VersionCode * 
        receiver : EndPoint * 
        community : OctetString * 
        enterprise : ObjectIdentifier * 
        timestamp : uint32 * 
        variables : IList<Variable> -> Task 

```


#### Parameters
&nbsp;<dl><dt>requestId</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.int32" target="_blank" rel="noopener noreferrer">System.Int32</a><br /></dd><dt>version</dt><dd>Type: <a href="T_Lextm_SharpSnmpLib_VersionCode">Lextm.SharpSnmpLib.VersionCode</a><br /></dd><dt>receiver</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.net.endpoint" target="_blank" rel="noopener noreferrer">System.Net.EndPoint</a><br /></dd><dt>community</dt><dd>Type: <a href="T_Lextm_SharpSnmpLib_OctetString">Lextm.SharpSnmpLib.OctetString</a><br /></dd><dt>enterprise</dt><dd>Type: <a href="T_Lextm_SharpSnmpLib_ObjectIdentifier">Lextm.SharpSnmpLib.ObjectIdentifier</a><br /></dd><dt>timestamp</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.uint32" target="_blank" rel="noopener noreferrer">System.UInt32</a><br /></dd><dt>variables</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.collections.generic.ilist-1" target="_blank" rel="noopener noreferrer">System.Collections.Generic.IList</a>(<a href="T_Lextm_SharpSnmpLib_Variable">Variable</a>)<br /></dd></dl>

#### Return Value
Type: <a href="https://docs.microsoft.com/dotnet/api/system.threading.tasks.task" target="_blank" rel="noopener noreferrer">Task</a>

## See Also


#### Reference
<a href="T_Lextm_SharpSnmpLib_Messaging_Messenger">Messenger Class</a><br /><a href="N_Lextm_SharpSnmpLib_Messaging">Lextm.SharpSnmpLib.Messaging Namespace</a><br />