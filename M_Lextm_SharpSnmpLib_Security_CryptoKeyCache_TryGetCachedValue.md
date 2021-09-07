# CryptoKeyCache.TryGetCachedValue Method 
 

**Namespace:**&nbsp;<a href="N_Lextm_SharpSnmpLib_Security">Lextm.SharpSnmpLib.Security</a><br />**Assembly:**&nbsp;SharpSnmpLib (in SharpSnmpLib.dll) Version: 12.4.0+601762d0e653a71ebb69af963204dfbfb6c26b74

## Syntax

**C#**<br />
``` C#
public bool TryGetCachedValue(
	byte[] password,
	byte[] engineId,
	out byte[] cachedValue
)
```

**VB**<br />
``` VB
Public Function TryGetCachedValue ( 
	password As Byte(),
	engineId As Byte(),
	<OutAttribute> ByRef cachedValue As Byte()
) As Boolean
```

**C++**<br />
``` C++
public:
bool TryGetCachedValue(
	array<unsigned char>^ password, 
	array<unsigned char>^ engineId, 
	[OutAttribute] array<unsigned char>^% cachedValue
)
```

**F#**<br />
``` F#
member TryGetCachedValue : 
        password : byte[] * 
        engineId : byte[] * 
        cachedValue : byte[] byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>password</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.byte" target="_blank" rel="noopener noreferrer">System.Byte</a>[]<br /></dd><dt>engineId</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.byte" target="_blank" rel="noopener noreferrer">System.Byte</a>[]<br /></dd><dt>cachedValue</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.byte" target="_blank" rel="noopener noreferrer">System.Byte</a>[]<br /></dd></dl>

#### Return Value
Type: <a href="https://docs.microsoft.com/dotnet/api/system.boolean" target="_blank" rel="noopener noreferrer">Boolean</a>

## See Also


#### Reference
<a href="T_Lextm_SharpSnmpLib_Security_CryptoKeyCache">CryptoKeyCache Class</a><br /><a href="N_Lextm_SharpSnmpLib_Security">Lextm.SharpSnmpLib.Security Namespace</a><br />