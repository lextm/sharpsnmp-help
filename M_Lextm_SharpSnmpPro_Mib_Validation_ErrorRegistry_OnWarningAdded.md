# ErrorRegistry.OnWarningAdded Method 
 

Called when a warning is added.

**Namespace:**&nbsp;<a href="N_Lextm_SharpSnmpPro_Mib_Validation">Lextm.SharpSnmpPro.Mib.Validation</a><br />**Assembly:**&nbsp;SharpSnmpPro.Mib (in SharpSnmpPro.Mib.dll) Version: 2.1.2

## Syntax

**C#**<br />
``` C#
protected virtual void OnWarningAdded(
	Object sender,
	CompilerWarning warning
)
```

**VB**<br />
``` VB
Protected Overridable Sub OnWarningAdded ( 
	sender As Object,
	warning As CompilerWarning
)
```

**C++**<br />
``` C++
protected:
virtual void OnWarningAdded(
	Object^ sender, 
	CompilerWarning^ warning
)
```

**F#**<br />
``` F#
abstract OnWarningAdded : 
        sender : Object * 
        warning : CompilerWarning -> unit 
override OnWarningAdded : 
        sender : Object * 
        warning : CompilerWarning -> unit 
```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.object" target="_blank" rel="noopener noreferrer">System.Object</a><br />The sender.</dd><dt>warning</dt><dd>Type: <a href="T_Lextm_SharpSnmpPro_Mib_Validation_CompilerWarning">Lextm.SharpSnmpPro.Mib.Validation.CompilerWarning</a><br />The warning.</dd></dl>

## See Also


#### Reference
<a href="T_Lextm_SharpSnmpPro_Mib_Validation_ErrorRegistry">ErrorRegistry Class</a><br /><a href="N_Lextm_SharpSnmpPro_Mib_Validation">Lextm.SharpSnmpPro.Mib.Validation Namespace</a><br />