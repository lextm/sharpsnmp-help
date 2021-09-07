# Cache(*TKey*, *TValue*).TryGetValue Method 
 

**Namespace:**&nbsp;<a href="N_Lextm_SharpSnmpLib_Security">Lextm.SharpSnmpLib.Security</a><br />**Assembly:**&nbsp;SharpSnmpLib (in SharpSnmpLib.dll) Version: 12.4.0+601762d0e653a71ebb69af963204dfbfb6c26b74

## Syntax

**C#**<br />
``` C#
public bool TryGetValue(
	TKey key,
	out TValue value
)
```

**VB**<br />
``` VB
Public Function TryGetValue ( 
	key As TKey,
	<OutAttribute> ByRef value As TValue
) As Boolean
```

**C++**<br />
``` C++
public:
bool TryGetValue(
	TKey key, 
	[OutAttribute] TValue% value
)
```

**F#**<br />
``` F#
member TryGetValue : 
        key : 'TKey * 
        value : 'TValue byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>key</dt><dd>Type: <a href="T_Lextm_SharpSnmpLib_Security_Cache_2">*TKey*</a><br /></dd><dt>value</dt><dd>Type: <a href="T_Lextm_SharpSnmpLib_Security_Cache_2">*TValue*</a><br /></dd></dl>

#### Return Value
Type: <a href="https://docs.microsoft.com/dotnet/api/system.boolean" target="_blank" rel="noopener noreferrer">Boolean</a>

## See Also


#### Reference
<a href="T_Lextm_SharpSnmpLib_Security_Cache_2">Cache(TKey, TValue) Class</a><br /><a href="N_Lextm_SharpSnmpLib_Security">Lextm.SharpSnmpLib.Security Namespace</a><br />