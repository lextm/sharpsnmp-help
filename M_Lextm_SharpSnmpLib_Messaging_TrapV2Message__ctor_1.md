# TrapV2Message Constructor (Int32, VersionCode, OctetString, ObjectIdentifier, UInt32, IList(Variable))
 

Initializes a new instance of the <a href="T_Lextm_SharpSnmpLib_Messaging_TrapV2Message">TrapV2Message</a> class

**Namespace:**&nbsp;<a href="N_Lextm_SharpSnmpLib_Messaging">Lextm.SharpSnmpLib.Messaging</a><br />**Assembly:**&nbsp;SharpSnmpLib (in SharpSnmpLib.dll) Version: 12.4.0+601762d0e653a71ebb69af963204dfbfb6c26b74

## Syntax

**C#**<br />
``` C#
public TrapV2Message(
	int requestId,
	VersionCode version,
	OctetString community,
	ObjectIdentifier enterprise,
	uint time,
	IList<Variable> variables
)
```

**VB**<br />
``` VB
Public Sub New ( 
	requestId As Integer,
	version As VersionCode,
	community As OctetString,
	enterprise As ObjectIdentifier,
	time As UInteger,
	variables As IList(Of Variable)
)
```

**C++**<br />
``` C++
public:
TrapV2Message(
	int requestId, 
	VersionCode version, 
	OctetString^ community, 
	ObjectIdentifier^ enterprise, 
	unsigned int time, 
	IList<Variable^>^ variables
)
```

**F#**<br />
``` F#
new : 
        requestId : int * 
        version : VersionCode * 
        community : OctetString * 
        enterprise : ObjectIdentifier * 
        time : uint32 * 
        variables : IList<Variable> -> TrapV2Message
```


#### Parameters
&nbsp;<dl><dt>requestId</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.int32" target="_blank" rel="noopener noreferrer">System.Int32</a><br /></dd><dt>version</dt><dd>Type: <a href="T_Lextm_SharpSnmpLib_VersionCode">Lextm.SharpSnmpLib.VersionCode</a><br /></dd><dt>community</dt><dd>Type: <a href="T_Lextm_SharpSnmpLib_OctetString">Lextm.SharpSnmpLib.OctetString</a><br /></dd><dt>enterprise</dt><dd>Type: <a href="T_Lextm_SharpSnmpLib_ObjectIdentifier">Lextm.SharpSnmpLib.ObjectIdentifier</a><br /></dd><dt>time</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.uint32" target="_blank" rel="noopener noreferrer">System.UInt32</a><br /></dd><dt>variables</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.collections.generic.ilist-1" target="_blank" rel="noopener noreferrer">System.Collections.Generic.IList</a>(<a href="T_Lextm_SharpSnmpLib_Variable">Variable</a>)<br /></dd></dl>

## See Also


#### Reference
<a href="T_Lextm_SharpSnmpLib_Messaging_TrapV2Message">TrapV2Message Class</a><br /><a href="Overload_Lextm_SharpSnmpLib_Messaging_TrapV2Message__ctor">TrapV2Message Overload</a><br /><a href="N_Lextm_SharpSnmpLib_Messaging">Lextm.SharpSnmpLib.Messaging Namespace</a><br />