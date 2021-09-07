# ObjectTree.Import Method 
 

Imports the specified modules.

**Namespace:**&nbsp;<a href="N_Lextm_SharpSnmpPro_Mib_Registry">Lextm.SharpSnmpPro.Mib.Registry</a><br />**Assembly:**&nbsp;SharpSnmpPro.Mib (in SharpSnmpPro.Mib.dll) Version: 2.1.2

## Syntax

**C#**<br />
``` C#
public void Import(
	IEnumerable<Module> modules
)
```

**VB**<br />
``` VB
Public Sub Import ( 
	modules As IEnumerable(Of Module)
)
```

**C++**<br />
``` C++
public:
void Import(
	IEnumerable<Module^>^ modules
)
```

**F#**<br />
``` F#
member Import : 
        modules : IEnumerable<Module> -> unit 

```


#### Parameters
&nbsp;<dl><dt>modules</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.collections.generic.ienumerable-1" target="_blank" rel="noopener noreferrer">System.Collections.Generic.IEnumerable</a>(<a href="T_Lextm_SharpSnmpPro_Mib_Module">Module</a>)<br />The modules.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td><a href="https://docs.microsoft.com/dotnet/api/system.argumentnullexception" target="_blank" rel="noopener noreferrer">ArgumentNullException</a></td><td>modules</td></tr></table>

## See Also


#### Reference
<a href="T_Lextm_SharpSnmpPro_Mib_Registry_ObjectTree">ObjectTree Class</a><br /><a href="N_Lextm_SharpSnmpPro_Mib_Registry">Lextm.SharpSnmpPro.Mib.Registry Namespace</a><br />