# Parser2.Compile Method (Stream, ErrorRegistry, String)
 

Loads a MIB file.

**Namespace:**&nbsp;<a href="N_Lextm_SharpSnmpPro_Mib_Registry">Lextm.SharpSnmpPro.Mib.Registry</a><br />**Assembly:**&nbsp;SharpSnmpPro.Mib (in SharpSnmpPro.Mib.dll) Version: 2.1.2

## Syntax

**C#**<br />
``` C#
public static IEnumerable<Module> Compile(
	Stream stream,
	ErrorRegistry registry,
	string fileName = ""
)
```

**VB**<br />
``` VB
Public Shared Function Compile ( 
	stream As Stream,
	registry As ErrorRegistry,
	Optional fileName As String = ""
) As IEnumerable(Of Module)
```

**C++**<br />
``` C++
public:
static IEnumerable<Module^>^ Compile(
	Stream^ stream, 
	ErrorRegistry^ registry, 
	String^ fileName = L""
)
```

**F#**<br />
``` F#
static member Compile : 
        stream : Stream * 
        registry : ErrorRegistry * 
        ?fileName : string 
(* Defaults:
        let _fileName = defaultArg fileName ""
*)
-> IEnumerable<Module> 

```


#### Parameters
&nbsp;<dl><dt>stream</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.io.stream" target="_blank" rel="noopener noreferrer">System.IO.Stream</a><br />The stream.</dd><dt>registry</dt><dd>Type: <a href="T_Lextm_SharpSnmpPro_Mib_Validation_ErrorRegistry">Lextm.SharpSnmpPro.Mib.Validation.ErrorRegistry</a><br />The registry.</dd><dt>fileName (Optional)</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.string" target="_blank" rel="noopener noreferrer">System.String</a><br />The file name (default value is empty).</dd></dl>

#### Return Value
Type: <a href="https://docs.microsoft.com/dotnet/api/system.collections.generic.ienumerable-1" target="_blank" rel="noopener noreferrer">IEnumerable</a>(<a href="T_Lextm_SharpSnmpPro_Mib_Module">Module</a>)<br />

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td><a href="https://docs.microsoft.com/dotnet/api/system.argumentnullexception" target="_blank" rel="noopener noreferrer">ArgumentNullException</a></td><td>stream</td></tr></table>

## See Also


#### Reference
<a href="T_Lextm_SharpSnmpPro_Mib_Registry_Parser2">Parser2 Class</a><br /><a href="Overload_Lextm_SharpSnmpPro_Mib_Registry_Parser2_Compile">Compile Overload</a><br /><a href="N_Lextm_SharpSnmpPro_Mib_Registry">Lextm.SharpSnmpPro.Mib.Registry Namespace</a><br />