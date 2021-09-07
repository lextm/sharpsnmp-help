# TrapV1Message Constructor (VersionCode, IPAddress, OctetString, ObjectIdentifier, GenericCode, Int32, UInt32, IList(Variable))
 

Initializes a new instance of the <a href="T_Lextm_SharpSnmpLib_Messaging_TrapV1Message">TrapV1Message</a> class

**Namespace:**&nbsp;<a href="N_Lextm_SharpSnmpLib_Messaging">Lextm.SharpSnmpLib.Messaging</a><br />**Assembly:**&nbsp;SharpSnmpLib (in SharpSnmpLib.dll) Version: 12.4.0+601762d0e653a71ebb69af963204dfbfb6c26b74

## Syntax

**C#**<br />
``` C#
public TrapV1Message(
	VersionCode version,
	IPAddress agent,
	OctetString community,
	ObjectIdentifier enterprise,
	GenericCode generic,
	int specific,
	uint time,
	IList<Variable> variables
)
```

**VB**<br />
``` VB
Public Sub New ( 
	version As VersionCode,
	agent As IPAddress,
	community As OctetString,
	enterprise As ObjectIdentifier,
	generic As GenericCode,
	specific As Integer,
	time As UInteger,
	variables As IList(Of Variable)
)
```

**C++**<br />
``` C++
public:
TrapV1Message(
	VersionCode version, 
	IPAddress^ agent, 
	OctetString^ community, 
	ObjectIdentifier^ enterprise, 
	GenericCode generic, 
	int specific, 
	unsigned int time, 
	IList<Variable^>^ variables
)
```

**F#**<br />
``` F#
new : 
        version : VersionCode * 
        agent : IPAddress * 
        community : OctetString * 
        enterprise : ObjectIdentifier * 
        generic : GenericCode * 
        specific : int * 
        time : uint32 * 
        variables : IList<Variable> -> TrapV1Message
```


#### Parameters
&nbsp;<dl><dt>version</dt><dd>Type: <a href="T_Lextm_SharpSnmpLib_VersionCode">Lextm.SharpSnmpLib.VersionCode</a><br /></dd><dt>agent</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.net.ipaddress" target="_blank" rel="noopener noreferrer">System.Net.IPAddress</a><br /></dd><dt>community</dt><dd>Type: <a href="T_Lextm_SharpSnmpLib_OctetString">Lextm.SharpSnmpLib.OctetString</a><br /></dd><dt>enterprise</dt><dd>Type: <a href="T_Lextm_SharpSnmpLib_ObjectIdentifier">Lextm.SharpSnmpLib.ObjectIdentifier</a><br /></dd><dt>generic</dt><dd>Type: <a href="T_Lextm_SharpSnmpLib_GenericCode">Lextm.SharpSnmpLib.GenericCode</a><br /></dd><dt>specific</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.int32" target="_blank" rel="noopener noreferrer">System.Int32</a><br /></dd><dt>time</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.uint32" target="_blank" rel="noopener noreferrer">System.UInt32</a><br /></dd><dt>variables</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.collections.generic.ilist-1" target="_blank" rel="noopener noreferrer">System.Collections.Generic.IList</a>(<a href="T_Lextm_SharpSnmpLib_Variable">Variable</a>)<br /></dd></dl>

## See Also


#### Reference
<a href="T_Lextm_SharpSnmpLib_Messaging_TrapV1Message">TrapV1Message Class</a><br /><a href="Overload_Lextm_SharpSnmpLib_Messaging_TrapV1Message__ctor">TrapV1Message Overload</a><br /><a href="N_Lextm_SharpSnmpLib_Messaging">Lextm.SharpSnmpLib.Messaging Namespace</a><br />