# ByteTool.PackMessage Method 
 

**Namespace:**&nbsp;<a href="N_Lextm_SharpSnmpLib">Lextm.SharpSnmpLib</a><br />**Assembly:**&nbsp;SharpSnmpLib (in SharpSnmpLib.dll) Version: 12.4.0+601762d0e653a71ebb69af963204dfbfb6c26b74

## Syntax

**C#**<br />
``` C#
public static Sequence PackMessage(
	byte[] length,
	VersionCode version,
	ISegment header,
	ISegment parameters,
	ISnmpData data
)
```

**VB**<br />
``` VB
Public Shared Function PackMessage ( 
	length As Byte(),
	version As VersionCode,
	header As ISegment,
	parameters As ISegment,
	data As ISnmpData
) As Sequence
```

**C++**<br />
``` C++
public:
static Sequence^ PackMessage(
	array<unsigned char>^ length, 
	VersionCode version, 
	ISegment^ header, 
	ISegment^ parameters, 
	ISnmpData^ data
)
```

**F#**<br />
``` F#
static member PackMessage : 
        length : byte[] * 
        version : VersionCode * 
        header : ISegment * 
        parameters : ISegment * 
        data : ISnmpData -> Sequence 

```


#### Parameters
&nbsp;<dl><dt>length</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.byte" target="_blank" rel="noopener noreferrer">System.Byte</a>[]<br /></dd><dt>version</dt><dd>Type: <a href="T_Lextm_SharpSnmpLib_VersionCode">Lextm.SharpSnmpLib.VersionCode</a><br /></dd><dt>header</dt><dd>Type: <a href="T_Lextm_SharpSnmpLib_ISegment">Lextm.SharpSnmpLib.ISegment</a><br /></dd><dt>parameters</dt><dd>Type: <a href="T_Lextm_SharpSnmpLib_ISegment">Lextm.SharpSnmpLib.ISegment</a><br /></dd><dt>data</dt><dd>Type: <a href="T_Lextm_SharpSnmpLib_ISnmpData">Lextm.SharpSnmpLib.ISnmpData</a><br /></dd></dl>

#### Return Value
Type: <a href="T_Lextm_SharpSnmpLib_Sequence">Sequence</a>

## See Also


#### Reference
<a href="T_Lextm_SharpSnmpLib_ByteTool">ByteTool Class</a><br /><a href="N_Lextm_SharpSnmpLib">Lextm.SharpSnmpLib Namespace</a><br />