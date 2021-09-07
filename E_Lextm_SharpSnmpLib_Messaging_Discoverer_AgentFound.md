# Discoverer.AgentFound Event
 

**Namespace:**&nbsp;<a href="N_Lextm_SharpSnmpLib_Messaging">Lextm.SharpSnmpLib.Messaging</a><br />**Assembly:**&nbsp;SharpSnmpLib (in SharpSnmpLib.dll) Version: 12.4.0+601762d0e653a71ebb69af963204dfbfb6c26b74

## Syntax

**C#**<br />
``` C#
public event EventHandler<AgentFoundEventArgs> AgentFound
```

**VB**<br />
``` VB
Public Event AgentFound As EventHandler(Of AgentFoundEventArgs)
```

**C++**<br />
``` C++
public:
 event EventHandler<AgentFoundEventArgs^>^ AgentFound {
	void add (EventHandler<AgentFoundEventArgs^>^ value);
	void remove (EventHandler<AgentFoundEventArgs^>^ value);
}
```

**F#**<br />
``` F#
member AgentFound : IEvent<EventHandler<AgentFoundEventArgs>,
    AgentFoundEventArgs>

```


#### Value
Type: <a href="https://docs.microsoft.com/dotnet/api/system.eventhandler-1" target="_blank" rel="noopener noreferrer">System.EventHandler</a>(<a href="T_Lextm_SharpSnmpLib_Messaging_AgentFoundEventArgs">AgentFoundEventArgs</a>)

## See Also


#### Reference
<a href="T_Lextm_SharpSnmpLib_Messaging_Discoverer">Discoverer Class</a><br /><a href="N_Lextm_SharpSnmpLib_Messaging">Lextm.SharpSnmpLib.Messaging Namespace</a><br />