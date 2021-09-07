# InformRequestMessage Constructor (VersionCode, Int32, Int32, OctetString, ObjectIdentifier, UInt32, IList(Variable), IPrivacyProvider, ISnmpMessage)
 

**Note: This API is now obsolete.**

Initializes a new instance of the <a href="T_Lextm_SharpSnmpLib_Messaging_InformRequestMessage">InformRequestMessage</a> class

**Namespace:**&nbsp;<a href="N_Lextm_SharpSnmpLib_Messaging">Lextm.SharpSnmpLib.Messaging</a><br />**Assembly:**&nbsp;SharpSnmpLib (in SharpSnmpLib.dll) Version: 12.4.0+601762d0e653a71ebb69af963204dfbfb6c26b74

## Syntax

**C#**<br />
``` C#
[ObsoleteAttribute("Please use other overloading ones.")]
public InformRequestMessage(
	VersionCode version,
	int messageId,
	int requestId,
	OctetString userName,
	ObjectIdentifier enterprise,
	uint time,
	IList<Variable> variables,
	IPrivacyProvider privacy,
	ISnmpMessage report
)
```

**VB**<br />
``` VB
<ObsoleteAttribute("Please use other overloading ones.")>
Public Sub New ( 
	version As VersionCode,
	messageId As Integer,
	requestId As Integer,
	userName As OctetString,
	enterprise As ObjectIdentifier,
	time As UInteger,
	variables As IList(Of Variable),
	privacy As IPrivacyProvider,
	report As ISnmpMessage
)
```

**C++**<br />
``` C++
public:
[ObsoleteAttribute(L"Please use other overloading ones.")]
InformRequestMessage(
	VersionCode version, 
	int messageId, 
	int requestId, 
	OctetString^ userName, 
	ObjectIdentifier^ enterprise, 
	unsigned int time, 
	IList<Variable^>^ variables, 
	IPrivacyProvider^ privacy, 
	ISnmpMessage^ report
)
```

**F#**<br />
``` F#
[<ObsoleteAttribute("Please use other overloading ones.")>]
new : 
        version : VersionCode * 
        messageId : int * 
        requestId : int * 
        userName : OctetString * 
        enterprise : ObjectIdentifier * 
        time : uint32 * 
        variables : IList<Variable> * 
        privacy : IPrivacyProvider * 
        report : ISnmpMessage -> InformRequestMessage
```


#### Parameters
&nbsp;<dl><dt>version</dt><dd>Type: <a href="T_Lextm_SharpSnmpLib_VersionCode">Lextm.SharpSnmpLib.VersionCode</a><br /></dd><dt>messageId</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.int32" target="_blank" rel="noopener noreferrer">System.Int32</a><br /></dd><dt>requestId</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.int32" target="_blank" rel="noopener noreferrer">System.Int32</a><br /></dd><dt>userName</dt><dd>Type: <a href="T_Lextm_SharpSnmpLib_OctetString">Lextm.SharpSnmpLib.OctetString</a><br /></dd><dt>enterprise</dt><dd>Type: <a href="T_Lextm_SharpSnmpLib_ObjectIdentifier">Lextm.SharpSnmpLib.ObjectIdentifier</a><br /></dd><dt>time</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.uint32" target="_blank" rel="noopener noreferrer">System.UInt32</a><br /></dd><dt>variables</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.collections.generic.ilist-1" target="_blank" rel="noopener noreferrer">System.Collections.Generic.IList</a>(<a href="T_Lextm_SharpSnmpLib_Variable">Variable</a>)<br /></dd><dt>privacy</dt><dd>Type: <a href="T_Lextm_SharpSnmpLib_Security_IPrivacyProvider">Lextm.SharpSnmpLib.Security.IPrivacyProvider</a><br /></dd><dt>report</dt><dd>Type: <a href="T_Lextm_SharpSnmpLib_Messaging_ISnmpMessage">Lextm.SharpSnmpLib.Messaging.ISnmpMessage</a><br /></dd></dl>

## See Also


#### Reference
<a href="T_Lextm_SharpSnmpLib_Messaging_InformRequestMessage">InformRequestMessage Class</a><br /><a href="Overload_Lextm_SharpSnmpLib_Messaging_InformRequestMessage__ctor">InformRequestMessage Overload</a><br /><a href="N_Lextm_SharpSnmpLib_Messaging">Lextm.SharpSnmpLib.Messaging Namespace</a><br />