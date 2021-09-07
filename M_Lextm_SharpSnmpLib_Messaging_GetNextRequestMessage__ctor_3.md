# GetNextRequestMessage Constructor (Int32, VersionCode, OctetString, IList(Variable))
 

Initializes a new instance of the <a href="T_Lextm_SharpSnmpLib_Messaging_GetNextRequestMessage">GetNextRequestMessage</a> class

**Namespace:**&nbsp;<a href="N_Lextm_SharpSnmpLib_Messaging">Lextm.SharpSnmpLib.Messaging</a><br />**Assembly:**&nbsp;SharpSnmpLib (in SharpSnmpLib.dll) Version: 12.4.0+601762d0e653a71ebb69af963204dfbfb6c26b74

## Syntax

**C#**<br />
``` C#
public GetNextRequestMessage(
	int requestId,
	VersionCode version,
	OctetString community,
	IList<Variable> variables
)
```

**VB**<br />
``` VB
Public Sub New ( 
	requestId As Integer,
	version As VersionCode,
	community As OctetString,
	variables As IList(Of Variable)
)
```

**C++**<br />
``` C++
public:
GetNextRequestMessage(
	int requestId, 
	VersionCode version, 
	OctetString^ community, 
	IList<Variable^>^ variables
)
```

**F#**<br />
``` F#
new : 
        requestId : int * 
        version : VersionCode * 
        community : OctetString * 
        variables : IList<Variable> -> GetNextRequestMessage
```


#### Parameters
&nbsp;<dl><dt>requestId</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.int32" target="_blank" rel="noopener noreferrer">System.Int32</a><br /></dd><dt>version</dt><dd>Type: <a href="T_Lextm_SharpSnmpLib_VersionCode">Lextm.SharpSnmpLib.VersionCode</a><br /></dd><dt>community</dt><dd>Type: <a href="T_Lextm_SharpSnmpLib_OctetString">Lextm.SharpSnmpLib.OctetString</a><br /></dd><dt>variables</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.collections.generic.ilist-1" target="_blank" rel="noopener noreferrer">System.Collections.Generic.IList</a>(<a href="T_Lextm_SharpSnmpLib_Variable">Variable</a>)<br /></dd></dl>

## See Also


#### Reference
<a href="T_Lextm_SharpSnmpLib_Messaging_GetNextRequestMessage">GetNextRequestMessage Class</a><br /><a href="Overload_Lextm_SharpSnmpLib_Messaging_GetNextRequestMessage__ctor">GetNextRequestMessage Overload</a><br /><a href="N_Lextm_SharpSnmpLib_Messaging">Lextm.SharpSnmpLib.Messaging Namespace</a><br />