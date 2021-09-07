# ErrorRegistry.ErrorAdded Event
 

Occurs when an error is added.

**Namespace:**&nbsp;<a href="N_Lextm_SharpSnmpPro_Mib_Validation">Lextm.SharpSnmpPro.Mib.Validation</a><br />**Assembly:**&nbsp;SharpSnmpPro.Mib (in SharpSnmpPro.Mib.dll) Version: 2.1.2

## Syntax

**C#**<br />
``` C#
public event EventHandler<CompilerError> ErrorAdded
```

**VB**<br />
``` VB
Public Event ErrorAdded As EventHandler(Of CompilerError)
```

**C++**<br />
``` C++
public:
 event EventHandler<CompilerError^>^ ErrorAdded {
	void add (EventHandler<CompilerError^>^ value);
	void remove (EventHandler<CompilerError^>^ value);
}
```

**F#**<br />
``` F#
member ErrorAdded : IEvent<EventHandler<CompilerError>,
    CompilerError>

```


#### Value
Type: <a href="https://docs.microsoft.com/dotnet/api/system.eventhandler-1" target="_blank" rel="noopener noreferrer">System.EventHandler</a>(<a href="T_Lextm_SharpSnmpPro_Mib_Validation_CompilerError">CompilerError</a>)

## See Also


#### Reference
<a href="T_Lextm_SharpSnmpPro_Mib_Validation_ErrorRegistry">ErrorRegistry Class</a><br /><a href="N_Lextm_SharpSnmpPro_Mib_Validation">Lextm.SharpSnmpPro.Mib.Validation Namespace</a><br />