# ErrorRegistry.OnErrorAdded Method 
 

Called when an error is added.

**Namespace:**&nbsp;<a href="N_Lextm_SharpSnmpPro_Mib_Validation">Lextm.SharpSnmpPro.Mib.Validation</a><br />**Assembly:**&nbsp;SharpSnmpPro.Mib (in SharpSnmpPro.Mib.dll) Version: 2.1.2

## Syntax

**C#**<br />
``` C#
protected virtual void OnErrorAdded(
	Object sender,
	CompilerError error
)
```

**VB**<br />
``` VB
Protected Overridable Sub OnErrorAdded ( 
	sender As Object,
	error As CompilerError
)
```

**C++**<br />
``` C++
protected:
virtual void OnErrorAdded(
	Object^ sender, 
	CompilerError^ error
)
```

**F#**<br />
``` F#
abstract OnErrorAdded : 
        sender : Object * 
        error : CompilerError -> unit 
override OnErrorAdded : 
        sender : Object * 
        error : CompilerError -> unit 
```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.object" target="_blank" rel="noopener noreferrer">System.Object</a><br />The sender.</dd><dt>error</dt><dd>Type: <a href="T_Lextm_SharpSnmpPro_Mib_Validation_CompilerError">Lextm.SharpSnmpPro.Mib.Validation.CompilerError</a><br />The error.</dd></dl>

## See Also


#### Reference
<a href="T_Lextm_SharpSnmpPro_Mib_Validation_ErrorRegistry">ErrorRegistry Class</a><br /><a href="N_Lextm_SharpSnmpPro_Mib_Validation">Lextm.SharpSnmpPro.Mib.Validation Namespace</a><br />