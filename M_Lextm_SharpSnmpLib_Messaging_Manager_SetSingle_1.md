# Manager.SetSingle Method (IPEndPoint, String, Variable)
 

**Namespace:**&nbsp;<a href="N_Lextm_SharpSnmpLib_Messaging">Lextm.SharpSnmpLib.Messaging</a><br />**Assembly:**&nbsp;SharpSnmpLib (in SharpSnmpLib.dll) Version: 12.4.0+601762d0e653a71ebb69af963204dfbfb6c26b74

## Syntax

**C#**<br />
``` C#
public Variable SetSingle(
	IPEndPoint endpoint,
	string community,
	Variable variable
)
```

**VB**<br />
``` VB
Public Function SetSingle ( 
	endpoint As IPEndPoint,
	community As String,
	variable As Variable
) As Variable
```

**C++**<br />
``` C++
public:
Variable^ SetSingle(
	IPEndPoint^ endpoint, 
	String^ community, 
	Variable^ variable
)
```

**F#**<br />
``` F#
member SetSingle : 
        endpoint : IPEndPoint * 
        community : string * 
        variable : Variable -> Variable 

```


#### Parameters
&nbsp;<dl><dt>endpoint</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.net.ipendpoint" target="_blank" rel="noopener noreferrer">System.Net.IPEndPoint</a><br /></dd><dt>community</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.string" target="_blank" rel="noopener noreferrer">System.String</a><br /></dd><dt>variable</dt><dd>Type: <a href="T_Lextm_SharpSnmpLib_Variable">Lextm.SharpSnmpLib.Variable</a><br /></dd></dl>

#### Return Value
Type: <a href="T_Lextm_SharpSnmpLib_Variable">Variable</a>

## See Also


#### Reference
<a href="T_Lextm_SharpSnmpLib_Messaging_Manager">Manager Class</a><br /><a href="Overload_Lextm_SharpSnmpLib_Messaging_Manager_SetSingle">SetSingle Overload</a><br /><a href="N_Lextm_SharpSnmpLib_Messaging">Lextm.SharpSnmpLib.Messaging Namespace</a><br />