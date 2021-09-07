# DataFactory.CreateSnmpData Method (Byte[], Int32, Int32)
 

**Namespace:**&nbsp;<a href="N_Lextm_SharpSnmpLib">Lextm.SharpSnmpLib</a><br />**Assembly:**&nbsp;SharpSnmpLib (in SharpSnmpLib.dll) Version: 12.4.0+601762d0e653a71ebb69af963204dfbfb6c26b74

## Syntax

**C#**<br />
``` C#
public static ISnmpData CreateSnmpData(
	byte[] buffer,
	int index,
	int count
)
```

**VB**<br />
``` VB
Public Shared Function CreateSnmpData ( 
	buffer As Byte(),
	index As Integer,
	count As Integer
) As ISnmpData
```

**C++**<br />
``` C++
public:
static ISnmpData^ CreateSnmpData(
	array<unsigned char>^ buffer, 
	int index, 
	int count
)
```

**F#**<br />
``` F#
static member CreateSnmpData : 
        buffer : byte[] * 
        index : int * 
        count : int -> ISnmpData 

```


#### Parameters
&nbsp;<dl><dt>buffer</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.byte" target="_blank" rel="noopener noreferrer">System.Byte</a>[]<br /></dd><dt>index</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.int32" target="_blank" rel="noopener noreferrer">System.Int32</a><br /></dd><dt>count</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.int32" target="_blank" rel="noopener noreferrer">System.Int32</a><br /></dd></dl>

#### Return Value
Type: <a href="T_Lextm_SharpSnmpLib_ISnmpData">ISnmpData</a>

## See Also


#### Reference
<a href="T_Lextm_SharpSnmpLib_DataFactory">DataFactory Class</a><br /><a href="Overload_Lextm_SharpSnmpLib_DataFactory_CreateSnmpData">CreateSnmpData Overload</a><br /><a href="N_Lextm_SharpSnmpLib">Lextm.SharpSnmpLib Namespace</a><br />