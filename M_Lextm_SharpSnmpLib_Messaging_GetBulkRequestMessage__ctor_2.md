# GetBulkRequestMessage Constructor (VersionCode, Int32, Int32, OctetString, Int32, Int32, IList(Variable), IPrivacyProvider, Int32, ISnmpMessage)
 

Initializes a new instance of the <a href="T_Lextm_SharpSnmpLib_Messaging_GetBulkRequestMessage">GetBulkRequestMessage</a> class

**Namespace:**&nbsp;<a href="N_Lextm_SharpSnmpLib_Messaging">Lextm.SharpSnmpLib.Messaging</a><br />**Assembly:**&nbsp;SharpSnmpLib (in SharpSnmpLib.dll) Version: 12.4.0+601762d0e653a71ebb69af963204dfbfb6c26b74

## Syntax

**C#**<br />
``` C#
public GetBulkRequestMessage(
	VersionCode version,
	int messageId,
	int requestId,
	OctetString userName,
	int nonRepeaters,
	int maxRepetitions,
	IList<Variable> variables,
	IPrivacyProvider privacy,
	int maxMessageSize,
	ISnmpMessage report
)
```

**VB**<br />
``` VB
Public Sub New ( 
	version As VersionCode,
	messageId As Integer,
	requestId As Integer,
	userName As OctetString,
	nonRepeaters As Integer,
	maxRepetitions As Integer,
	variables As IList(Of Variable),
	privacy As IPrivacyProvider,
	maxMessageSize As Integer,
	report As ISnmpMessage
)
```

**C++**<br />
``` C++
public:
GetBulkRequestMessage(
	VersionCode version, 
	int messageId, 
	int requestId, 
	OctetString^ userName, 
	int nonRepeaters, 
	int maxRepetitions, 
	IList<Variable^>^ variables, 
	IPrivacyProvider^ privacy, 
	int maxMessageSize, 
	ISnmpMessage^ report
)
```

**F#**<br />
``` F#
new : 
        version : VersionCode * 
        messageId : int * 
        requestId : int * 
        userName : OctetString * 
        nonRepeaters : int * 
        maxRepetitions : int * 
        variables : IList<Variable> * 
        privacy : IPrivacyProvider * 
        maxMessageSize : int * 
        report : ISnmpMessage -> GetBulkRequestMessage
```


#### Parameters
&nbsp;<dl><dt>version</dt><dd>Type: <a href="T_Lextm_SharpSnmpLib_VersionCode">Lextm.SharpSnmpLib.VersionCode</a><br /></dd><dt>messageId</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.int32" target="_blank" rel="noopener noreferrer">System.Int32</a><br /></dd><dt>requestId</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.int32" target="_blank" rel="noopener noreferrer">System.Int32</a><br /></dd><dt>userName</dt><dd>Type: <a href="T_Lextm_SharpSnmpLib_OctetString">Lextm.SharpSnmpLib.OctetString</a><br /></dd><dt>nonRepeaters</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.int32" target="_blank" rel="noopener noreferrer">System.Int32</a><br /></dd><dt>maxRepetitions</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.int32" target="_blank" rel="noopener noreferrer">System.Int32</a><br /></dd><dt>variables</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.collections.generic.ilist-1" target="_blank" rel="noopener noreferrer">System.Collections.Generic.IList</a>(<a href="T_Lextm_SharpSnmpLib_Variable">Variable</a>)<br /></dd><dt>privacy</dt><dd>Type: <a href="T_Lextm_SharpSnmpLib_Security_IPrivacyProvider">Lextm.SharpSnmpLib.Security.IPrivacyProvider</a><br /></dd><dt>maxMessageSize</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.int32" target="_blank" rel="noopener noreferrer">System.Int32</a><br /></dd><dt>report</dt><dd>Type: <a href="T_Lextm_SharpSnmpLib_Messaging_ISnmpMessage">Lextm.SharpSnmpLib.Messaging.ISnmpMessage</a><br /></dd></dl>

## See Also


#### Reference
<a href="T_Lextm_SharpSnmpLib_Messaging_GetBulkRequestMessage">GetBulkRequestMessage Class</a><br /><a href="Overload_Lextm_SharpSnmpLib_Messaging_GetBulkRequestMessage__ctor">GetBulkRequestMessage Overload</a><br /><a href="N_Lextm_SharpSnmpLib_Messaging">Lextm.SharpSnmpLib.Messaging Namespace</a><br />