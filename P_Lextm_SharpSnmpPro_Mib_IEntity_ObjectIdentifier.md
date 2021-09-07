# IEntity.ObjectIdentifier Property 
 

**Note: This API is now obsolete.**

Gets or sets the object identifier.

**Namespace:**&nbsp;<a href="N_Lextm_SharpSnmpPro_Mib">Lextm.SharpSnmpPro.Mib</a><br />**Assembly:**&nbsp;SharpSnmpPro.Mib (in SharpSnmpPro.Mib.dll) Version: 2.1.2

## Syntax

**C#**<br />
``` C#
[ObsoleteAttribute("Please use GetObjectIdentifier method.")]
uint[] ObjectIdentifier { get; set; }
```

**VB**<br />
``` VB
<ObsoleteAttribute("Please use GetObjectIdentifier method.")>
Property ObjectIdentifier As UInteger()
	Get
	Set
```

**C++**<br />
``` C++
[ObsoleteAttribute(L"Please use GetObjectIdentifier method.")]
property array<unsigned int>^ ObjectIdentifier {
	array<unsigned int>^ get ();
	void set (array<unsigned int>^ value);
}
```

**F#**<br />
``` F#
[<ObsoleteAttribute("Please use GetObjectIdentifier method.")>]
abstract ObjectIdentifier : uint32[] with get, set

```


#### Property Value
Type: <a href="https://docs.microsoft.com/dotnet/api/system.uint32" target="_blank" rel="noopener noreferrer">UInt32</a>[]<br />The object identifier.

## See Also


#### Reference
<a href="T_Lextm_SharpSnmpPro_Mib_IEntity">IEntity Interface</a><br /><a href="N_Lextm_SharpSnmpPro_Mib">Lextm.SharpSnmpPro.Mib Namespace</a><br />