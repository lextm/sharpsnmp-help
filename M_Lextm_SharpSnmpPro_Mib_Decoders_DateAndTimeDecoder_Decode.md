# DateAndTimeDecoder.Decode Method 
 

Decodes the specified data.

**Namespace:**&nbsp;<a href="N_Lextm_SharpSnmpPro_Mib_Decoders">Lextm.SharpSnmpPro.Mib.Decoders</a><br />**Assembly:**&nbsp;SharpSnmpPro.Mib (in SharpSnmpPro.Mib.dll) Version: 2.1.2

## Syntax

**C#**<br />
``` C#
public string Decode(
	ISnmpData data
)
```

**VB**<br />
``` VB
Public Function Decode ( 
	data As ISnmpData
) As String
```

**C++**<br />
``` C++
public:
virtual String^ Decode(
	ISnmpData^ data
) sealed
```

**F#**<br />
``` F#
abstract Decode : 
        data : ISnmpData -> string 
override Decode : 
        data : ISnmpData -> string 
```


#### Parameters
&nbsp;<dl><dt>data</dt><dd>Type: <a href="T_Lextm_SharpSnmpLib_ISnmpData">Lextm.SharpSnmpLib.ISnmpData</a><br />The data.</dd></dl>

#### Return Value
Type: <a href="https://docs.microsoft.com/dotnet/api/system.string" target="_blank" rel="noopener noreferrer">String</a><br />

#### Implements
<a href="M_Lextm_SharpSnmpPro_Mib_IDecoder_Decode">IDecoder.Decode(ISnmpData)</a><br />

## See Also


#### Reference
<a href="T_Lextm_SharpSnmpPro_Mib_Decoders_DateAndTimeDecoder">DateAndTimeDecoder Class</a><br /><a href="N_Lextm_SharpSnmpPro_Mib_Decoders">Lextm.SharpSnmpPro.Mib.Decoders Namespace</a><br />