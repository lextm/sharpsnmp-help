# ResponseMessage Constructor (Int32, VersionCode, OctetString, ErrorCode, Int32, IList(Variable))
 

Initializes a new instance of the <a href="T_Lextm_SharpSnmpLib_Messaging_ResponseMessage">ResponseMessage</a> class

**Namespace:**&nbsp;<a href="N_Lextm_SharpSnmpLib_Messaging">Lextm.SharpSnmpLib.Messaging</a><br />**Assembly:**&nbsp;SharpSnmpLib (in SharpSnmpLib.dll) Version: 12.4.0+601762d0e653a71ebb69af963204dfbfb6c26b74

## Syntax

**C#**<br />
``` C#
public ResponseMessage(
	int requestId,
	VersionCode version,
	OctetString community,
	ErrorCode error,
	int index,
	IList<Variable> variables
)
```

**VB**<br />
``` VB
Public Sub New ( 
	requestId As Integer,
	version As VersionCode,
	community As OctetString,
	error As ErrorCode,
	index As Integer,
	variables As IList(Of Variable)
)
```

**C++**<br />
``` C++
public:
ResponseMessage(
	int requestId, 
	VersionCode version, 
	OctetString^ community, 
	ErrorCode error, 
	int index, 
	IList<Variable^>^ variables
)
```

**F#**<br />
``` F#
new : 
        requestId : int * 
        version : VersionCode * 
        community : OctetString * 
        error : ErrorCode * 
        index : int * 
        variables : IList<Variable> -> ResponseMessage
```


#### Parameters
&nbsp;<dl><dt>requestId</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.int32" target="_blank" rel="noopener noreferrer">System.Int32</a><br /></dd><dt>version</dt><dd>Type: <a href="T_Lextm_SharpSnmpLib_VersionCode">Lextm.SharpSnmpLib.VersionCode</a><br /></dd><dt>community</dt><dd>Type: <a href="T_Lextm_SharpSnmpLib_OctetString">Lextm.SharpSnmpLib.OctetString</a><br /></dd><dt>error</dt><dd>Type: <a href="T_Lextm_SharpSnmpLib_ErrorCode">Lextm.SharpSnmpLib.ErrorCode</a><br /></dd><dt>index</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.int32" target="_blank" rel="noopener noreferrer">System.Int32</a><br /></dd><dt>variables</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.collections.generic.ilist-1" target="_blank" rel="noopener noreferrer">System.Collections.Generic.IList</a>(<a href="T_Lextm_SharpSnmpLib_Variable">Variable</a>)<br /></dd></dl>

## See Also


#### Reference
<a href="T_Lextm_SharpSnmpLib_Messaging_ResponseMessage">ResponseMessage Class</a><br /><a href="Overload_Lextm_SharpSnmpLib_Messaging_ResponseMessage__ctor">ResponseMessage Overload</a><br /><a href="N_Lextm_SharpSnmpLib_Messaging">Lextm.SharpSnmpLib.Messaging Namespace</a><br />