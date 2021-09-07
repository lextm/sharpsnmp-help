# Messenger.SendInform Method (Int32, VersionCode, IPEndPoint, OctetString, OctetString, ObjectIdentifier, UInt32, IList(Variable), Int32, IPrivacyProvider, ISnmpMessage)
 

**Namespace:**&nbsp;<a href="N_Lextm_SharpSnmpLib_Messaging">Lextm.SharpSnmpLib.Messaging</a><br />**Assembly:**&nbsp;SharpSnmpLib (in SharpSnmpLib.dll) Version: 12.4.0+601762d0e653a71ebb69af963204dfbfb6c26b74

## Syntax

**C#**<br />
``` C#
public static void SendInform(
	int requestId,
	VersionCode version,
	IPEndPoint receiver,
	OctetString community,
	OctetString contextName,
	ObjectIdentifier enterprise,
	uint timestamp,
	IList<Variable> variables,
	int timeout,
	IPrivacyProvider privacy,
	ISnmpMessage report
)
```

**VB**<br />
``` VB
Public Shared Sub SendInform ( 
	requestId As Integer,
	version As VersionCode,
	receiver As IPEndPoint,
	community As OctetString,
	contextName As OctetString,
	enterprise As ObjectIdentifier,
	timestamp As UInteger,
	variables As IList(Of Variable),
	timeout As Integer,
	privacy As IPrivacyProvider,
	report As ISnmpMessage
)
```

**C++**<br />
``` C++
public:
static void SendInform(
	int requestId, 
	VersionCode version, 
	IPEndPoint^ receiver, 
	OctetString^ community, 
	OctetString^ contextName, 
	ObjectIdentifier^ enterprise, 
	unsigned int timestamp, 
	IList<Variable^>^ variables, 
	int timeout, 
	IPrivacyProvider^ privacy, 
	ISnmpMessage^ report
)
```

**F#**<br />
``` F#
static member SendInform : 
        requestId : int * 
        version : VersionCode * 
        receiver : IPEndPoint * 
        community : OctetString * 
        contextName : OctetString * 
        enterprise : ObjectIdentifier * 
        timestamp : uint32 * 
        variables : IList<Variable> * 
        timeout : int * 
        privacy : IPrivacyProvider * 
        report : ISnmpMessage -> unit 

```


#### Parameters
&nbsp;<dl><dt>requestId</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.int32" target="_blank" rel="noopener noreferrer">System.Int32</a><br /></dd><dt>version</dt><dd>Type: <a href="T_Lextm_SharpSnmpLib_VersionCode">Lextm.SharpSnmpLib.VersionCode</a><br /></dd><dt>receiver</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.net.ipendpoint" target="_blank" rel="noopener noreferrer">System.Net.IPEndPoint</a><br /></dd><dt>community</dt><dd>Type: <a href="T_Lextm_SharpSnmpLib_OctetString">Lextm.SharpSnmpLib.OctetString</a><br /></dd><dt>contextName</dt><dd>Type: <a href="T_Lextm_SharpSnmpLib_OctetString">Lextm.SharpSnmpLib.OctetString</a><br /></dd><dt>enterprise</dt><dd>Type: <a href="T_Lextm_SharpSnmpLib_ObjectIdentifier">Lextm.SharpSnmpLib.ObjectIdentifier</a><br /></dd><dt>timestamp</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.uint32" target="_blank" rel="noopener noreferrer">System.UInt32</a><br /></dd><dt>variables</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.collections.generic.ilist-1" target="_blank" rel="noopener noreferrer">System.Collections.Generic.IList</a>(<a href="T_Lextm_SharpSnmpLib_Variable">Variable</a>)<br /></dd><dt>timeout</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.int32" target="_blank" rel="noopener noreferrer">System.Int32</a><br /></dd><dt>privacy</dt><dd>Type: <a href="T_Lextm_SharpSnmpLib_Security_IPrivacyProvider">Lextm.SharpSnmpLib.Security.IPrivacyProvider</a><br /></dd><dt>report</dt><dd>Type: <a href="T_Lextm_SharpSnmpLib_Messaging_ISnmpMessage">Lextm.SharpSnmpLib.Messaging.ISnmpMessage</a><br /></dd></dl>

## See Also


#### Reference
<a href="T_Lextm_SharpSnmpLib_Messaging_Messenger">Messenger Class</a><br /><a href="Overload_Lextm_SharpSnmpLib_Messaging_Messenger_SendInform">SendInform Overload</a><br /><a href="N_Lextm_SharpSnmpLib_Messaging">Lextm.SharpSnmpLib.Messaging Namespace</a><br />