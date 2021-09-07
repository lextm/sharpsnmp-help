# ObjectTypeMacro.MibAugments Property 
 

**Note: This API is now obsolete.**

Gets or sets the mib augments.

**Namespace:**&nbsp;<a href="N_Lextm_SharpSnmpPro_Mib">Lextm.SharpSnmpPro.Mib</a><br />**Assembly:**&nbsp;SharpSnmpPro.Mib (in SharpSnmpPro.Mib.dll) Version: 2.1.2

## Syntax

**C#**<br />
``` C#
[ObsoleteAttribute("Please use Augments property instead.")]
public ISmiValue MibAugments { get; set; }
```

**VB**<br />
``` VB
<ObsoleteAttribute("Please use Augments property instead.")>
Public Property MibAugments As ISmiValue
	Get
	Set
```

**C++**<br />
``` C++
public:
[ObsoleteAttribute(L"Please use Augments property instead.")]
property ISmiValue^ MibAugments {
	ISmiValue^ get ();
	void set (ISmiValue^ value);
}
```

**F#**<br />
``` F#
[<ObsoleteAttribute("Please use Augments property instead.")>]
member MibAugments : ISmiValue with get, set

```


#### Property Value
Type: <a href="T_Lextm_SharpSnmpPro_Mib_ISmiValue">ISmiValue</a><br />The mib augments.

## See Also


#### Reference
<a href="T_Lextm_SharpSnmpPro_Mib_ObjectTypeMacro">ObjectTypeMacro Class</a><br /><a href="N_Lextm_SharpSnmpPro_Mib">Lextm.SharpSnmpPro.Mib Namespace</a><br />