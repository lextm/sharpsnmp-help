# ObjectRegistryBase.OnChanged Event
 

This event occurs when new documents are loaded.

**Namespace:**&nbsp;<a href="N_Lextm_SharpSnmpPro_Mib_Registry">Lextm.SharpSnmpPro.Mib.Registry</a><br />**Assembly:**&nbsp;SharpSnmpPro.Mib (in SharpSnmpPro.Mib.dll) Version: 2.1.2

## Syntax

**C#**<br />
``` C#
public event EventHandler<EventArgs> OnChanged
```

**VB**<br />
``` VB
Public Event OnChanged As EventHandler(Of EventArgs)
```

**C++**<br />
``` C++
public:
 event EventHandler<EventArgs^>^ OnChanged {
	void add (EventHandler<EventArgs^>^ value);
	void remove (EventHandler<EventArgs^>^ value);
}
```

**F#**<br />
``` F#
member OnChanged : IEvent<EventHandler<EventArgs>,
    EventArgs>

```


#### Value
Type: <a href="https://docs.microsoft.com/dotnet/api/system.eventhandler-1" target="_blank" rel="noopener noreferrer">System.EventHandler</a>(<a href="https://docs.microsoft.com/dotnet/api/system.eventargs" target="_blank" rel="noopener noreferrer">EventArgs</a>)

## See Also


#### Reference
<a href="T_Lextm_SharpSnmpPro_Mib_Registry_ObjectRegistryBase">ObjectRegistryBase Class</a><br /><a href="N_Lextm_SharpSnmpPro_Mib_Registry">Lextm.SharpSnmpPro.Mib.Registry Namespace</a><br />