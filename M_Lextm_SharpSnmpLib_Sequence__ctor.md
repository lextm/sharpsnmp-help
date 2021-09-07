# Sequence Constructor (Byte[], ISnmpData[])
 

Initializes a new instance of the <a href="T_Lextm_SharpSnmpLib_Sequence">Sequence</a> class

**Namespace:**&nbsp;<a href="N_Lextm_SharpSnmpLib">Lextm.SharpSnmpLib</a><br />**Assembly:**&nbsp;SharpSnmpLib (in SharpSnmpLib.dll) Version: 12.4.0+601762d0e653a71ebb69af963204dfbfb6c26b74

## Syntax

**C#**<br />
``` C#
public Sequence(
	byte[] length,
	params ISnmpData[] items
)
```

**VB**<br />
``` VB
Public Sub New ( 
	length As Byte(),
	ParamArray items As ISnmpData()
)
```

**C++**<br />
``` C++
public:
Sequence(
	array<unsigned char>^ length, 
	... array<ISnmpData^>^ items
)
```

**F#**<br />
``` F#
new : 
        length : byte[] * 
        items : ISnmpData[] -> Sequence
```


#### Parameters
&nbsp;<dl><dt>length</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.byte" target="_blank" rel="noopener noreferrer">System.Byte</a>[]<br /></dd><dt>items</dt><dd>Type: <a href="T_Lextm_SharpSnmpLib_ISnmpData">Lextm.SharpSnmpLib.ISnmpData</a>[]<br /></dd></dl>

## See Also


#### Reference
<a href="T_Lextm_SharpSnmpLib_Sequence">Sequence Class</a><br /><a href="Overload_Lextm_SharpSnmpLib_Sequence__ctor">Sequence Overload</a><br /><a href="N_Lextm_SharpSnmpLib">Lextm.SharpSnmpLib Namespace</a><br />