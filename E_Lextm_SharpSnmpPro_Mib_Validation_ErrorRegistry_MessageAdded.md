# ErrorRegistry.MessageAdded Event
 

Occurs when a message is added.

**Namespace:**&nbsp;<a href="N_Lextm_SharpSnmpPro_Mib_Validation">Lextm.SharpSnmpPro.Mib.Validation</a><br />**Assembly:**&nbsp;SharpSnmpPro.Mib (in SharpSnmpPro.Mib.dll) Version: 2.1.2

## Syntax

**C#**<br />
``` C#
public event EventHandler<CompilerMessage> MessageAdded
```

**VB**<br />
``` VB
Public Event MessageAdded As EventHandler(Of CompilerMessage)
```

**C++**<br />
``` C++
public:
 event EventHandler<CompilerMessage^>^ MessageAdded {
	void add (EventHandler<CompilerMessage^>^ value);
	void remove (EventHandler<CompilerMessage^>^ value);
}
```

**F#**<br />
``` F#
member MessageAdded : IEvent<EventHandler<CompilerMessage>,
    CompilerMessage>

```


#### Value
Type: <a href="https://docs.microsoft.com/dotnet/api/system.eventhandler-1" target="_blank" rel="noopener noreferrer">System.EventHandler</a>(<a href="T_Lextm_SharpSnmpPro_Mib_Validation_CompilerMessage">CompilerMessage</a>)

## See Also


#### Reference
<a href="T_Lextm_SharpSnmpPro_Mib_Validation_ErrorRegistry">ErrorRegistry Class</a><br /><a href="N_Lextm_SharpSnmpPro_Mib_Validation">Lextm.SharpSnmpPro.Mib.Validation Namespace</a><br />