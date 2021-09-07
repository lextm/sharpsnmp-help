# TripleDESPrivacyProvider.Encrypt Method (Byte[], Byte[], Byte[])
 

**Namespace:**&nbsp;<a href="N_Lextm_SharpSnmpLib_Security">Lextm.SharpSnmpLib.Security</a><br />**Assembly:**&nbsp;SharpSnmpLib (in SharpSnmpLib.dll) Version: 12.4.0+601762d0e653a71ebb69af963204dfbfb6c26b74

## Syntax

**C#**<br />
``` C#
public static byte[] Encrypt(
	byte[] unencryptedData,
	byte[] key,
	byte[] privacyParameters
)
```

**VB**<br />
``` VB
Public Shared Function Encrypt ( 
	unencryptedData As Byte(),
	key As Byte(),
	privacyParameters As Byte()
) As Byte()
```

**C++**<br />
``` C++
public:
static array<unsigned char>^ Encrypt(
	array<unsigned char>^ unencryptedData, 
	array<unsigned char>^ key, 
	array<unsigned char>^ privacyParameters
)
```

**F#**<br />
``` F#
static member Encrypt : 
        unencryptedData : byte[] * 
        key : byte[] * 
        privacyParameters : byte[] -> byte[] 

```


#### Parameters
&nbsp;<dl><dt>unencryptedData</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.byte" target="_blank" rel="noopener noreferrer">System.Byte</a>[]<br /></dd><dt>key</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.byte" target="_blank" rel="noopener noreferrer">System.Byte</a>[]<br /></dd><dt>privacyParameters</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.byte" target="_blank" rel="noopener noreferrer">System.Byte</a>[]<br /></dd></dl>

#### Return Value
Type: <a href="https://docs.microsoft.com/dotnet/api/system.byte" target="_blank" rel="noopener noreferrer">Byte</a>[]

## See Also


#### Reference
<a href="T_Lextm_SharpSnmpLib_Security_TripleDESPrivacyProvider">TripleDESPrivacyProvider Class</a><br /><a href="Overload_Lextm_SharpSnmpLib_Security_TripleDESPrivacyProvider_Encrypt">Encrypt Overload</a><br /><a href="N_Lextm_SharpSnmpLib_Security">Lextm.SharpSnmpLib.Security Namespace</a><br />