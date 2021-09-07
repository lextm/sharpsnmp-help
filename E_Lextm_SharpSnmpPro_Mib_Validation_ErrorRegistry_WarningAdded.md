# ErrorRegistry.WarningAdded Event
 

Occurs when a warning is added.

**Namespace:**&nbsp;<a href="N_Lextm_SharpSnmpPro_Mib_Validation">Lextm.SharpSnmpPro.Mib.Validation</a><br />**Assembly:**&nbsp;SharpSnmpPro.Mib (in SharpSnmpPro.Mib.dll) Version: 2.1.2

## Syntax

**C#**<br />
``` C#
public event EventHandler<CompilerWarning> WarningAdded
```

**VB**<br />
``` VB
Public Event WarningAdded As EventHandler(Of CompilerWarning)
```

**C++**<br />
``` C++
public:
 event EventHandler<CompilerWarning^>^ WarningAdded {
	void add (EventHandler<CompilerWarning^>^ value);
	void remove (EventHandler<CompilerWarning^>^ value);
}
```

**F#**<br />
``` F#
member WarningAdded : IEvent<EventHandler<CompilerWarning>,
    CompilerWarning>

```


#### Value
Type: <a href="https://docs.microsoft.com/dotnet/api/system.eventhandler-1" target="_blank" rel="noopener noreferrer">System.EventHandler</a>(<a href="T_Lextm_SharpSnmpPro_Mib_Validation_CompilerWarning">CompilerWarning</a>)

## See Also


#### Reference
<a href="T_Lextm_SharpSnmpPro_Mib_Validation_ErrorRegistry">ErrorRegistry Class</a><br /><a href="N_Lextm_SharpSnmpPro_Mib_Validation">Lextm.SharpSnmpPro.Mib.Validation Namespace</a><br />