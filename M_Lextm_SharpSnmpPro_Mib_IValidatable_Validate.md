# IValidatable.Validate Method 
 

Validates this entity.

**Namespace:**&nbsp;<a href="N_Lextm_SharpSnmpPro_Mib">Lextm.SharpSnmpPro.Mib</a><br />**Assembly:**&nbsp;SharpSnmpPro.Mib (in SharpSnmpPro.Mib.dll) Version: 2.1.2

## Syntax

**C#**<br />
``` C#
void Validate(
	ICollection<IConstruct> knownConstructs,
	ErrorRegistry registry
)
```

**VB**<br />
``` VB
Sub Validate ( 
	knownConstructs As ICollection(Of IConstruct),
	registry As ErrorRegistry
)
```

**C++**<br />
``` C++
void Validate(
	ICollection<IConstruct^>^ knownConstructs, 
	ErrorRegistry^ registry
)
```

**F#**<br />
``` F#
abstract Validate : 
        knownConstructs : ICollection<IConstruct> * 
        registry : ErrorRegistry -> unit 

```


#### Parameters
&nbsp;<dl><dt>knownConstructs</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.collections.generic.icollection-1" target="_blank" rel="noopener noreferrer">System.Collections.Generic.ICollection</a>(<a href="T_Lextm_SharpSnmpPro_Mib_IConstruct">IConstruct</a>)<br />Known constructs.</dd><dt>registry</dt><dd>Type: <a href="T_Lextm_SharpSnmpPro_Mib_Validation_ErrorRegistry">Lextm.SharpSnmpPro.Mib.Validation.ErrorRegistry</a><br />The registry.</dd></dl>

#### Return Value
Type: <br />

## See Also


#### Reference
<a href="T_Lextm_SharpSnmpPro_Mib_IValidatable">IValidatable Interface</a><br /><a href="N_Lextm_SharpSnmpPro_Mib">Lextm.SharpSnmpPro.Mib Namespace</a><br />