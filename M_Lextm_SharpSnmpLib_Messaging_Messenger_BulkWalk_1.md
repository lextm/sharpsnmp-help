# Messenger.BulkWalk Method (VersionCode, IPEndPoint, OctetString, OctetString, ObjectIdentifier, IList(Variable), Int32, Int32, WalkMode, IPrivacyProvider, ISnmpMessage)
 

**Namespace:**&nbsp;<a href="N_Lextm_SharpSnmpLib_Messaging">Lextm.SharpSnmpLib.Messaging</a><br />**Assembly:**&nbsp;SharpSnmpLib (in SharpSnmpLib.dll) Version: 12.4.0+601762d0e653a71ebb69af963204dfbfb6c26b74

## Syntax

**C#**<br />
``` C#
public static int BulkWalk(
	VersionCode version,
	IPEndPoint endpoint,
	OctetString community,
	OctetString contextName,
	ObjectIdentifier table,
	IList<Variable> list,
	int timeout,
	int maxRepetitions,
	WalkMode mode,
	IPrivacyProvider privacy,
	ISnmpMessage report
)
```

**VB**<br />
``` VB
Public Shared Function BulkWalk ( 
	version As VersionCode,
	endpoint As IPEndPoint,
	community As OctetString,
	contextName As OctetString,
	table As ObjectIdentifier,
	list As IList(Of Variable),
	timeout As Integer,
	maxRepetitions As Integer,
	mode As WalkMode,
	privacy As IPrivacyProvider,
	report As ISnmpMessage
) As Integer
```

**C++**<br />
``` C++
public:
static int BulkWalk(
	VersionCode version, 
	IPEndPoint^ endpoint, 
	OctetString^ community, 
	OctetString^ contextName, 
	ObjectIdentifier^ table, 
	IList<Variable^>^ list, 
	int timeout, 
	int maxRepetitions, 
	WalkMode mode, 
	IPrivacyProvider^ privacy, 
	ISnmpMessage^ report
)
```

**F#**<br />
``` F#
static member BulkWalk : 
        version : VersionCode * 
        endpoint : IPEndPoint * 
        community : OctetString * 
        contextName : OctetString * 
        table : ObjectIdentifier * 
        list : IList<Variable> * 
        timeout : int * 
        maxRepetitions : int * 
        mode : WalkMode * 
        privacy : IPrivacyProvider * 
        report : ISnmpMessage -> int 

```


#### Parameters
&nbsp;<dl><dt>version</dt><dd>Type: <a href="T_Lextm_SharpSnmpLib_VersionCode">Lextm.SharpSnmpLib.VersionCode</a><br /></dd><dt>endpoint</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.net.ipendpoint" target="_blank" rel="noopener noreferrer">System.Net.IPEndPoint</a><br /></dd><dt>community</dt><dd>Type: <a href="T_Lextm_SharpSnmpLib_OctetString">Lextm.SharpSnmpLib.OctetString</a><br /></dd><dt>contextName</dt><dd>Type: <a href="T_Lextm_SharpSnmpLib_OctetString">Lextm.SharpSnmpLib.OctetString</a><br /></dd><dt>table</dt><dd>Type: <a href="T_Lextm_SharpSnmpLib_ObjectIdentifier">Lextm.SharpSnmpLib.ObjectIdentifier</a><br /></dd><dt>list</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.collections.generic.ilist-1" target="_blank" rel="noopener noreferrer">System.Collections.Generic.IList</a>(<a href="T_Lextm_SharpSnmpLib_Variable">Variable</a>)<br /></dd><dt>timeout</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.int32" target="_blank" rel="noopener noreferrer">System.Int32</a><br /></dd><dt>maxRepetitions</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.int32" target="_blank" rel="noopener noreferrer">System.Int32</a><br /></dd><dt>mode</dt><dd>Type: <a href="T_Lextm_SharpSnmpLib_Messaging_WalkMode">Lextm.SharpSnmpLib.Messaging.WalkMode</a><br /></dd><dt>privacy</dt><dd>Type: <a href="T_Lextm_SharpSnmpLib_Security_IPrivacyProvider">Lextm.SharpSnmpLib.Security.IPrivacyProvider</a><br /></dd><dt>report</dt><dd>Type: <a href="T_Lextm_SharpSnmpLib_Messaging_ISnmpMessage">Lextm.SharpSnmpLib.Messaging.ISnmpMessage</a><br /></dd></dl>

#### Return Value
Type: <a href="https://docs.microsoft.com/dotnet/api/system.int32" target="_blank" rel="noopener noreferrer">Int32</a>

## See Also


#### Reference
<a href="T_Lextm_SharpSnmpLib_Messaging_Messenger">Messenger Class</a><br /><a href="Overload_Lextm_SharpSnmpLib_Messaging_Messenger_BulkWalk">BulkWalk Overload</a><br /><a href="N_Lextm_SharpSnmpLib_Messaging">Lextm.SharpSnmpLib.Messaging Namespace</a><br />