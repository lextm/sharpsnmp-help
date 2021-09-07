# ErrorRegistry.OnMessageAdded Method 
 

Called when a message is added.

**Namespace:**&nbsp;<a href="N_Lextm_SharpSnmpPro_Mib_Validation">Lextm.SharpSnmpPro.Mib.Validation</a><br />**Assembly:**&nbsp;SharpSnmpPro.Mib (in SharpSnmpPro.Mib.dll) Version: 2.1.2

## Syntax

**C#**<br />
``` C#
protected virtual void OnMessageAdded(
	Object sender,
	CompilerMessage message
)
```

**VB**<br />
``` VB
Protected Overridable Sub OnMessageAdded ( 
	sender As Object,
	message As CompilerMessage
)
```

**C++**<br />
``` C++
protected:
virtual void OnMessageAdded(
	Object^ sender, 
	CompilerMessage^ message
)
```

**F#**<br />
``` F#
abstract OnMessageAdded : 
        sender : Object * 
        message : CompilerMessage -> unit 
override OnMessageAdded : 
        sender : Object * 
        message : CompilerMessage -> unit 
```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.object" target="_blank" rel="noopener noreferrer">System.Object</a><br />The sender.</dd><dt>message</dt><dd>Type: <a href="T_Lextm_SharpSnmpPro_Mib_Validation_CompilerMessage">Lextm.SharpSnmpPro.Mib.Validation.CompilerMessage</a><br />The message.</dd></dl>

## See Also


#### Reference
<a href="T_Lextm_SharpSnmpPro_Mib_Validation_ErrorRegistry">ErrorRegistry Class</a><br /><a href="N_Lextm_SharpSnmpPro_Mib_Validation">Lextm.SharpSnmpPro.Mib.Validation Namespace</a><br />