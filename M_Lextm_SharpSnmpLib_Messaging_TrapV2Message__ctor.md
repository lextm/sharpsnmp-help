# TrapV2Message Constructor (VersionCode, Int32, Int32, OctetString, ObjectIdentifier, UInt32, IList(Variable), IPrivacyProvider, Int32, OctetString, Int32, Int32)
 

Initializes a new instance of the <a href="T_Lextm_SharpSnmpLib_Messaging_TrapV2Message">TrapV2Message</a> class

**Namespace:**&nbsp;<a href="N_Lextm_SharpSnmpLib_Messaging">Lextm.SharpSnmpLib.Messaging</a><br />**Assembly:**&nbsp;SharpSnmpLib (in SharpSnmpLib.dll) Version: 12.4.0+601762d0e653a71ebb69af963204dfbfb6c26b74

## Syntax

**C#**<br />
``` C#
public TrapV2Message(
	VersionCode version,
	int messageId,
	int requestId,
	OctetString userName,
	ObjectIdentifier enterprise,
	uint time,
	IList<Variable> variables,
	IPrivacyProvider privacy,
	int maxMessageSize,
	OctetString engineId,
	int engineBoots,
	int engineTime
)
```

**VB**<br />
``` VB
Public Sub New ( 
	version As VersionCode,
	messageId As Integer,
	requestId As Integer,
	userName As OctetString,
	enterprise As ObjectIdentifier,
	time As UInteger,
	variables As IList(Of Variable),
	privacy As IPrivacyProvider,
	maxMessageSize As Integer,
	engineId As OctetString,
	engineBoots As Integer,
	engineTime As Integer
)
```

**C++**<br />
``` C++
public:
TrapV2Message(
	VersionCode version, 
	int messageId, 
	int requestId, 
	OctetString^ userName, 
	ObjectIdentifier^ enterprise, 
	unsigned int time, 
	IList<Variable^>^ variables, 
	IPrivacyProvider^ privacy, 
	int maxMessageSize, 
	OctetString^ engineId, 
	int engineBoots, 
	int engineTime
)
```

**F#**<br />
``` F#
new : 
        version : VersionCode * 
        messageId : int * 
        requestId : int * 
        userName : OctetString * 
        enterprise : ObjectIdentifier * 
        time : uint32 * 
        variables : IList<Variable> * 
        privacy : IPrivacyProvider * 
        maxMessageSize : int * 
        engineId : OctetString * 
        engineBoots : int * 
        engineTime : int -> TrapV2Message
```


#### Parameters
&nbsp;<dl><dt>version</dt><dd>Type: <a href="T_Lextm_SharpSnmpLib_VersionCode">Lextm.SharpSnmpLib.VersionCode</a><br /></dd><dt>messageId</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.int32" target="_blank" rel="noopener noreferrer">System.Int32</a><br /></dd><dt>requestId</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.int32" target="_blank" rel="noopener noreferrer">System.Int32</a><br /></dd><dt>userName</dt><dd>Type: <a href="T_Lextm_SharpSnmpLib_OctetString">Lextm.SharpSnmpLib.OctetString</a><br /></dd><dt>enterprise</dt><dd>Type: <a href="T_Lextm_SharpSnmpLib_ObjectIdentifier">Lextm.SharpSnmpLib.ObjectIdentifier</a><br /></dd><dt>time</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.uint32" target="_blank" rel="noopener noreferrer">System.UInt32</a><br /></dd><dt>variables</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.collections.generic.ilist-1" target="_blank" rel="noopener noreferrer">System.Collections.Generic.IList</a>(<a href="T_Lextm_SharpSnmpLib_Variable">Variable</a>)<br /></dd><dt>privacy</dt><dd>Type: <a href="T_Lextm_SharpSnmpLib_Security_IPrivacyProvider">Lextm.SharpSnmpLib.Security.IPrivacyProvider</a><br /></dd><dt>maxMessageSize</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.int32" target="_blank" rel="noopener noreferrer">System.Int32</a><br /></dd><dt>engineId</dt><dd>Type: <a href="T_Lextm_SharpSnmpLib_OctetString">Lextm.SharpSnmpLib.OctetString</a><br /></dd><dt>engineBoots</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.int32" target="_blank" rel="noopener noreferrer">System.Int32</a><br /></dd><dt>engineTime</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.int32" target="_blank" rel="noopener noreferrer">System.Int32</a><br /></dd></dl>

## See Also


#### Reference
<a href="T_Lextm_SharpSnmpLib_Messaging_TrapV2Message">TrapV2Message Class</a><br /><a href="Overload_Lextm_SharpSnmpLib_Messaging_TrapV2Message__ctor">TrapV2Message Overload</a><br /><a href="N_Lextm_SharpSnmpLib_Messaging">Lextm.SharpSnmpLib.Messaging Namespace</a><br />