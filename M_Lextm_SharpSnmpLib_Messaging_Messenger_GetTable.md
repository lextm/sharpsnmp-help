# Messenger.GetTable Method 
 

**Note: This API is now obsolete.**

**Namespace:**&nbsp;<a href="N_Lextm_SharpSnmpLib_Messaging">Lextm.SharpSnmpLib.Messaging</a><br />**Assembly:**&nbsp;SharpSnmpLib (in SharpSnmpLib.dll) Version: 12.4.0+601762d0e653a71ebb69af963204dfbfb6c26b74

## Syntax

**C#**<br />
``` C#
[ObsoleteAttribute("This method only works for a few scenarios. Might be replaced by new methods in the future. If it does not work for you, parse WALK result on your own.")]
public static Variable[,] GetTable(
	VersionCode version,
	IPEndPoint endpoint,
	OctetString community,
	ObjectIdentifier table,
	int timeout,
	int maxRepetitions
)
```

**VB**<br />
``` VB
<ObsoleteAttribute("This method only works for a few scenarios. Might be replaced by new methods in the future. If it does not work for you, parse WALK result on your own.")>
Public Shared Function GetTable ( 
	version As VersionCode,
	endpoint As IPEndPoint,
	community As OctetString,
	table As ObjectIdentifier,
	timeout As Integer,
	maxRepetitions As Integer
) As Variable(,)
```

**C++**<br />
``` C++
public:
[ObsoleteAttribute(L"This method only works for a few scenarios. Might be replaced by new methods in the future. If it does not work for you, parse WALK result on your own.")]
static array<Variable^,2>^ GetTable(
	VersionCode version, 
	IPEndPoint^ endpoint, 
	OctetString^ community, 
	ObjectIdentifier^ table, 
	int timeout, 
	int maxRepetitions
)
```

**F#**<br />
``` F#
[<ObsoleteAttribute("This method only works for a few scenarios. Might be replaced by new methods in the future. If it does not work for you, parse WALK result on your own.")>]
static member GetTable : 
        version : VersionCode * 
        endpoint : IPEndPoint * 
        community : OctetString * 
        table : ObjectIdentifier * 
        timeout : int * 
        maxRepetitions : int -> Variable[,] 

```


#### Parameters
&nbsp;<dl><dt>version</dt><dd>Type: <a href="T_Lextm_SharpSnmpLib_VersionCode">Lextm.SharpSnmpLib.VersionCode</a><br /></dd><dt>endpoint</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.net.ipendpoint" target="_blank" rel="noopener noreferrer">System.Net.IPEndPoint</a><br /></dd><dt>community</dt><dd>Type: <a href="T_Lextm_SharpSnmpLib_OctetString">Lextm.SharpSnmpLib.OctetString</a><br /></dd><dt>table</dt><dd>Type: <a href="T_Lextm_SharpSnmpLib_ObjectIdentifier">Lextm.SharpSnmpLib.ObjectIdentifier</a><br /></dd><dt>timeout</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.int32" target="_blank" rel="noopener noreferrer">System.Int32</a><br /></dd><dt>maxRepetitions</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.int32" target="_blank" rel="noopener noreferrer">System.Int32</a><br /></dd></dl>

#### Return Value
Type: <a href="T_Lextm_SharpSnmpLib_Variable">Variable</a>[,]

## See Also


#### Reference
<a href="T_Lextm_SharpSnmpLib_Messaging_Messenger">Messenger Class</a><br /><a href="N_Lextm_SharpSnmpLib_Messaging">Lextm.SharpSnmpLib.Messaging Namespace</a><br />