# ObjectIdentifier Constructor (Tuple(Int32, Byte[]), Stream)
 

Initializes a new instance of the <a href="T_Lextm_SharpSnmpLib_ObjectIdentifier">ObjectIdentifier</a> class

**Namespace:**&nbsp;<a href="N_Lextm_SharpSnmpLib">Lextm.SharpSnmpLib</a><br />**Assembly:**&nbsp;SharpSnmpLib (in SharpSnmpLib.dll) Version: 12.4.0+601762d0e653a71ebb69af963204dfbfb6c26b74

## Syntax

**C#**<br />
``` C#
public ObjectIdentifier(
	Tuple<int, byte[]> length,
	Stream stream
)
```

**VB**<br />
``` VB
Public Sub New ( 
	length As Tuple(Of Integer, Byte()),
	stream As Stream
)
```

**C++**<br />
``` C++
public:
ObjectIdentifier(
	Tuple<int, array<unsigned char>^>^ length, 
	Stream^ stream
)
```

**F#**<br />
``` F#
new : 
        length : Tuple<int, byte[]> * 
        stream : Stream -> ObjectIdentifier
```


#### Parameters
&nbsp;<dl><dt>length</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.tuple-2" target="_blank" rel="noopener noreferrer">System.Tuple</a>(<a href="https://docs.microsoft.com/dotnet/api/system.int32" target="_blank" rel="noopener noreferrer">Int32</a>, <a href="https://docs.microsoft.com/dotnet/api/system.byte" target="_blank" rel="noopener noreferrer">Byte</a>[])<br /></dd><dt>stream</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.io.stream" target="_blank" rel="noopener noreferrer">System.IO.Stream</a><br /></dd></dl>

## See Also


#### Reference
<a href="T_Lextm_SharpSnmpLib_ObjectIdentifier">ObjectIdentifier Class</a><br /><a href="Overload_Lextm_SharpSnmpLib_ObjectIdentifier__ctor">ObjectIdentifier Overload</a><br /><a href="N_Lextm_SharpSnmpLib">Lextm.SharpSnmpLib Namespace</a><br />