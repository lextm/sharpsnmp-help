# TrapV1Pdu Constructor (ObjectIdentifier, IP, Integer32, Integer32, TimeTicks, IList(Variable))
 

Initializes a new instance of the <a href="T_Lextm_SharpSnmpLib_TrapV1Pdu">TrapV1Pdu</a> class

**Namespace:**&nbsp;<a href="N_Lextm_SharpSnmpLib">Lextm.SharpSnmpLib</a><br />**Assembly:**&nbsp;SharpSnmpLib (in SharpSnmpLib.dll) Version: 12.4.0+601762d0e653a71ebb69af963204dfbfb6c26b74

## Syntax

**C#**<br />
``` C#
public TrapV1Pdu(
	ObjectIdentifier enterprise,
	IP agent,
	Integer32 generic,
	Integer32 specific,
	TimeTicks timestamp,
	IList<Variable> variables
)
```

**VB**<br />
``` VB
Public Sub New ( 
	enterprise As ObjectIdentifier,
	agent As IP,
	generic As Integer32,
	specific As Integer32,
	timestamp As TimeTicks,
	variables As IList(Of Variable)
)
```

**C++**<br />
``` C++
public:
TrapV1Pdu(
	ObjectIdentifier^ enterprise, 
	IP^ agent, 
	Integer32^ generic, 
	Integer32^ specific, 
	TimeTicks^ timestamp, 
	IList<Variable^>^ variables
)
```

**F#**<br />
``` F#
new : 
        enterprise : ObjectIdentifier * 
        agent : IP * 
        generic : Integer32 * 
        specific : Integer32 * 
        timestamp : TimeTicks * 
        variables : IList<Variable> -> TrapV1Pdu
```


#### Parameters
&nbsp;<dl><dt>enterprise</dt><dd>Type: <a href="T_Lextm_SharpSnmpLib_ObjectIdentifier">Lextm.SharpSnmpLib.ObjectIdentifier</a><br /></dd><dt>agent</dt><dd>Type: <a href="T_Lextm_SharpSnmpLib_IP">Lextm.SharpSnmpLib.IP</a><br /></dd><dt>generic</dt><dd>Type: <a href="T_Lextm_SharpSnmpLib_Integer32">Lextm.SharpSnmpLib.Integer32</a><br /></dd><dt>specific</dt><dd>Type: <a href="T_Lextm_SharpSnmpLib_Integer32">Lextm.SharpSnmpLib.Integer32</a><br /></dd><dt>timestamp</dt><dd>Type: <a href="T_Lextm_SharpSnmpLib_TimeTicks">Lextm.SharpSnmpLib.TimeTicks</a><br /></dd><dt>variables</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.collections.generic.ilist-1" target="_blank" rel="noopener noreferrer">System.Collections.Generic.IList</a>(<a href="T_Lextm_SharpSnmpLib_Variable">Variable</a>)<br /></dd></dl>

## See Also


#### Reference
<a href="T_Lextm_SharpSnmpLib_TrapV1Pdu">TrapV1Pdu Class</a><br /><a href="Overload_Lextm_SharpSnmpLib_TrapV1Pdu__ctor">TrapV1Pdu Overload</a><br /><a href="N_Lextm_SharpSnmpLib">Lextm.SharpSnmpLib Namespace</a><br />