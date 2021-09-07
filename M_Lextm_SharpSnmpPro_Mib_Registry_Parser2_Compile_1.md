# Parser2.Compile Method (String, ErrorRegistry)
 

Loads a MIB file.

**Namespace:**&nbsp;<a href="N_Lextm_SharpSnmpPro_Mib_Registry">Lextm.SharpSnmpPro.Mib.Registry</a><br />**Assembly:**&nbsp;SharpSnmpPro.Mib (in SharpSnmpPro.Mib.dll) Version: 2.1.2

## Syntax

**C#**<br />
``` C#
public static IEnumerable<Module> Compile(
	string fileName,
	ErrorRegistry registry
)
```

**VB**<br />
``` VB
Public Shared Function Compile ( 
	fileName As String,
	registry As ErrorRegistry
) As IEnumerable(Of Module)
```

**C++**<br />
``` C++
public:
static IEnumerable<Module^>^ Compile(
	String^ fileName, 
	ErrorRegistry^ registry
)
```

**F#**<br />
``` F#
static member Compile : 
        fileName : string * 
        registry : ErrorRegistry -> IEnumerable<Module> 

```


#### Parameters
&nbsp;<dl><dt>fileName</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.string" target="_blank" rel="noopener noreferrer">System.String</a><br />File name.</dd><dt>registry</dt><dd>Type: <a href="T_Lextm_SharpSnmpPro_Mib_Validation_ErrorRegistry">Lextm.SharpSnmpPro.Mib.Validation.ErrorRegistry</a><br />The registry.</dd></dl>

#### Return Value
Type: <a href="https://docs.microsoft.com/dotnet/api/system.collections.generic.ienumerable-1" target="_blank" rel="noopener noreferrer">IEnumerable</a>(<a href="T_Lextm_SharpSnmpPro_Mib_Module">Module</a>)<br />

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td><a href="https://docs.microsoft.com/dotnet/api/system.argumentnullexception" target="_blank" rel="noopener noreferrer">ArgumentNullException</a></td><td>fileName</td></tr><tr><td><a href="https://docs.microsoft.com/dotnet/api/system.argumentexception" target="_blank" rel="noopener noreferrer">ArgumentException</a></td><td>fileName cannot be empty or file does not exist: + fileName</td></tr></table>

## See Also


#### Reference
<a href="T_Lextm_SharpSnmpPro_Mib_Registry_Parser2">Parser2 Class</a><br /><a href="Overload_Lextm_SharpSnmpPro_Mib_Registry_Parser2_Compile">Compile Overload</a><br /><a href="N_Lextm_SharpSnmpPro_Mib_Registry">Lextm.SharpSnmpPro.Mib.Registry Namespace</a><br />