# Discoverer.DiscoverAsync Method 
 

**Namespace:**&nbsp;<a href="N_Lextm_SharpSnmpLib_Messaging">Lextm.SharpSnmpLib.Messaging</a><br />**Assembly:**&nbsp;SharpSnmpLib (in SharpSnmpLib.dll) Version: 12.4.0+601762d0e653a71ebb69af963204dfbfb6c26b74

## Syntax

**C#**<br />
``` C#
public Task DiscoverAsync(
	VersionCode version,
	IPEndPoint broadcastAddress,
	OctetString community,
	int interval
)
```

**VB**<br />
``` VB
Public Function DiscoverAsync ( 
	version As VersionCode,
	broadcastAddress As IPEndPoint,
	community As OctetString,
	interval As Integer
) As Task
```

**C++**<br />
``` C++
public:
Task^ DiscoverAsync(
	VersionCode version, 
	IPEndPoint^ broadcastAddress, 
	OctetString^ community, 
	int interval
)
```

**F#**<br />
``` F#
member DiscoverAsync : 
        version : VersionCode * 
        broadcastAddress : IPEndPoint * 
        community : OctetString * 
        interval : int -> Task 

```


#### Parameters
&nbsp;<dl><dt>version</dt><dd>Type: <a href="T_Lextm_SharpSnmpLib_VersionCode">Lextm.SharpSnmpLib.VersionCode</a><br /></dd><dt>broadcastAddress</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.net.ipendpoint" target="_blank" rel="noopener noreferrer">System.Net.IPEndPoint</a><br /></dd><dt>community</dt><dd>Type: <a href="T_Lextm_SharpSnmpLib_OctetString">Lextm.SharpSnmpLib.OctetString</a><br /></dd><dt>interval</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.int32" target="_blank" rel="noopener noreferrer">System.Int32</a><br /></dd></dl>

#### Return Value
Type: <a href="https://docs.microsoft.com/dotnet/api/system.threading.tasks.task" target="_blank" rel="noopener noreferrer">Task</a>

## See Also


#### Reference
<a href="T_Lextm_SharpSnmpLib_Messaging_Discoverer">Discoverer Class</a><br /><a href="N_Lextm_SharpSnmpLib_Messaging">Lextm.SharpSnmpLib.Messaging Namespace</a><br />