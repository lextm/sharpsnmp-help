# Messenger.SendTrapV1 Method 
 

**Namespace:**&nbsp;<a href="N_Lextm_SharpSnmpLib_Messaging">Lextm.SharpSnmpLib.Messaging</a><br />**Assembly:**&nbsp;SharpSnmpLib (in SharpSnmpLib.dll) Version: 12.4.0+601762d0e653a71ebb69af963204dfbfb6c26b74

## Syntax

**C#**<br />
``` C#
public static void SendTrapV1(
	EndPoint receiver,
	IPAddress agent,
	OctetString community,
	ObjectIdentifier enterprise,
	GenericCode generic,
	int specific,
	uint timestamp,
	IList<Variable> variables
)
```

**VB**<br />
``` VB
Public Shared Sub SendTrapV1 ( 
	receiver As EndPoint,
	agent As IPAddress,
	community As OctetString,
	enterprise As ObjectIdentifier,
	generic As GenericCode,
	specific As Integer,
	timestamp As UInteger,
	variables As IList(Of Variable)
)
```

**C++**<br />
``` C++
public:
static void SendTrapV1(
	EndPoint^ receiver, 
	IPAddress^ agent, 
	OctetString^ community, 
	ObjectIdentifier^ enterprise, 
	GenericCode generic, 
	int specific, 
	unsigned int timestamp, 
	IList<Variable^>^ variables
)
```

**F#**<br />
``` F#
static member SendTrapV1 : 
        receiver : EndPoint * 
        agent : IPAddress * 
        community : OctetString * 
        enterprise : ObjectIdentifier * 
        generic : GenericCode * 
        specific : int * 
        timestamp : uint32 * 
        variables : IList<Variable> -> unit 

```


#### Parameters
&nbsp;<dl><dt>receiver</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.net.endpoint" target="_blank" rel="noopener noreferrer">System.Net.EndPoint</a><br /></dd><dt>agent</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.net.ipaddress" target="_blank" rel="noopener noreferrer">System.Net.IPAddress</a><br /></dd><dt>community</dt><dd>Type: <a href="T_Lextm_SharpSnmpLib_OctetString">Lextm.SharpSnmpLib.OctetString</a><br /></dd><dt>enterprise</dt><dd>Type: <a href="T_Lextm_SharpSnmpLib_ObjectIdentifier">Lextm.SharpSnmpLib.ObjectIdentifier</a><br /></dd><dt>generic</dt><dd>Type: <a href="T_Lextm_SharpSnmpLib_GenericCode">Lextm.SharpSnmpLib.GenericCode</a><br /></dd><dt>specific</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.int32" target="_blank" rel="noopener noreferrer">System.Int32</a><br /></dd><dt>timestamp</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.uint32" target="_blank" rel="noopener noreferrer">System.UInt32</a><br /></dd><dt>variables</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.collections.generic.ilist-1" target="_blank" rel="noopener noreferrer">System.Collections.Generic.IList</a>(<a href="T_Lextm_SharpSnmpLib_Variable">Variable</a>)<br /></dd></dl>

## See Also


#### Reference
<a href="T_Lextm_SharpSnmpLib_Messaging_Messenger">Messenger Class</a><br /><a href="N_Lextm_SharpSnmpLib_Messaging">Lextm.SharpSnmpLib.Messaging Namespace</a><br />