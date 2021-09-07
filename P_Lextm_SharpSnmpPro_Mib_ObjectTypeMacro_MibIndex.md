# ObjectTypeMacro.MibIndex Property 
 

**Note: This API is now obsolete.**

Gets or sets the index of the mib.

**Namespace:**&nbsp;<a href="N_Lextm_SharpSnmpPro_Mib">Lextm.SharpSnmpPro.Mib</a><br />**Assembly:**&nbsp;SharpSnmpPro.Mib (in SharpSnmpPro.Mib.dll) Version: 2.1.2

## Syntax

**C#**<br />
``` C#
[ObsoleteAttribute("Please use IndexList property instead.")]
public IList<ISmiValue> MibIndex { get; }
```

**VB**<br />
``` VB
<ObsoleteAttribute("Please use IndexList property instead.")>
Public ReadOnly Property MibIndex As IList(Of ISmiValue)
	Get
```

**C++**<br />
``` C++
public:
[ObsoleteAttribute(L"Please use IndexList property instead.")]
property IList<ISmiValue^>^ MibIndex {
	IList<ISmiValue^>^ get ();
}
```

**F#**<br />
``` F#
[<ObsoleteAttribute("Please use IndexList property instead.")>]
member MibIndex : IList<ISmiValue> with get

```


#### Property Value
Type: <a href="https://docs.microsoft.com/dotnet/api/system.collections.generic.ilist-1" target="_blank" rel="noopener noreferrer">IList</a>(<a href="T_Lextm_SharpSnmpPro_Mib_ISmiValue">ISmiValue</a>)<br />The index of the mib.

## See Also


#### Reference
<a href="T_Lextm_SharpSnmpPro_Mib_ObjectTypeMacro">ObjectTypeMacro Class</a><br /><a href="N_Lextm_SharpSnmpPro_Mib">Lextm.SharpSnmpPro.Mib Namespace</a><br />