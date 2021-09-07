# ModuleComplianceMacro.ObjectIdentifier Property 
 

**Note: This API is now obsolete.**

**Namespace:**&nbsp;<a href="N_Lextm_SharpSnmpPro_Mib">Lextm.SharpSnmpPro.Mib</a><br />**Assembly:**&nbsp;SharpSnmpPro.Mib (in SharpSnmpPro.Mib.dll) Version: 2.1.2

## Syntax

**C#**<br />
``` C#
[ObsoleteAttribute("Please use GetObjectIdentifier method.")]
public uint[] ObjectIdentifier { get; set; }
```

**VB**<br />
``` VB
<ObsoleteAttribute("Please use GetObjectIdentifier method.")>
Public Property ObjectIdentifier As UInteger()
	Get
	Set
```

**C++**<br />
``` C++
public:
[ObsoleteAttribute(L"Please use GetObjectIdentifier method.")]
virtual property array<unsigned int>^ ObjectIdentifier {
	array<unsigned int>^ get () sealed;
	void set (array<unsigned int>^ value) sealed;
}
```

**F#**<br />
``` F#
[<ObsoleteAttribute("Please use GetObjectIdentifier method.")>]
abstract ObjectIdentifier : uint32[] with get, set
[<ObsoleteAttribute("Please use GetObjectIdentifier method.")>]
override ObjectIdentifier : uint32[] with get, set
```


#### Property Value
Type: <a href="https://docs.microsoft.com/dotnet/api/system.uint32" target="_blank" rel="noopener noreferrer">UInt32</a>[]

#### Implements
<a href="P_Lextm_SharpSnmpPro_Mib_IEntity_ObjectIdentifier">IEntity.ObjectIdentifier</a><br />

## See Also


#### Reference
<a href="T_Lextm_SharpSnmpPro_Mib_ModuleComplianceMacro">ModuleComplianceMacro Class</a><br /><a href="N_Lextm_SharpSnmpPro_Mib">Lextm.SharpSnmpPro.Mib Namespace</a><br />