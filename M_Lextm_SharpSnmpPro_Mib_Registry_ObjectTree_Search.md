# ObjectTree.Search Method 
 

Searches the specified object via identifier.

**Namespace:**&nbsp;<a href="N_Lextm_SharpSnmpPro_Mib_Registry">Lextm.SharpSnmpPro.Mib.Registry</a><br />**Assembly:**&nbsp;SharpSnmpPro.Mib (in SharpSnmpPro.Mib.dll) Version: 2.1.2

## Syntax

**C#**<br />
``` C#
public SearchResult Search(
	uint[] id
)
```

**VB**<br />
``` VB
Public Function Search ( 
	id As UInteger()
) As SearchResult
```

**C++**<br />
``` C++
public:
SearchResult^ Search(
	array<unsigned int>^ id
)
```

**F#**<br />
``` F#
member Search : 
        id : uint32[] -> SearchResult 

```


#### Parameters
&nbsp;<dl><dt>id</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.uint32" target="_blank" rel="noopener noreferrer">System.UInt32</a>[]<br />The identifier.</dd></dl>

#### Return Value
Type: <a href="T_Lextm_SharpSnmpPro_Mib_Registry_SearchResult">SearchResult</a><br />

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td><a href="https://docs.microsoft.com/dotnet/api/system.argumentnullexception" target="_blank" rel="noopener noreferrer">ArgumentNullException</a></td><td>id</td></tr><tr><td><a href="https://docs.microsoft.com/dotnet/api/system.argumentexception" target="_blank" rel="noopener noreferrer">ArgumentException</a></td><td>numerical cannot be empty</td></tr></table>

## See Also


#### Reference
<a href="T_Lextm_SharpSnmpPro_Mib_Registry_ObjectTree">ObjectTree Class</a><br /><a href="N_Lextm_SharpSnmpPro_Mib_Registry">Lextm.SharpSnmpPro.Mib.Registry Namespace</a><br />