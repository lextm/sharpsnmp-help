# DESPrivacyProvider.Decrypt Method (Byte[], Byte[], Byte[])
 

**Namespace:**&nbsp;<a href="N_Lextm_SharpSnmpLib_Security">Lextm.SharpSnmpLib.Security</a><br />**Assembly:**&nbsp;SharpSnmpLib (in SharpSnmpLib.dll) Version: 12.4.0+601762d0e653a71ebb69af963204dfbfb6c26b74

## Syntax

**C#**<br />
``` C#
public static byte[] Decrypt(
	byte[] encryptedData,
	byte[] key,
	byte[] privacyParameters
)
```

**VB**<br />
``` VB
Public Shared Function Decrypt ( 
	encryptedData As Byte(),
	key As Byte(),
	privacyParameters As Byte()
) As Byte()
```

**C++**<br />
``` C++
public:
static array<unsigned char>^ Decrypt(
	array<unsigned char>^ encryptedData, 
	array<unsigned char>^ key, 
	array<unsigned char>^ privacyParameters
)
```

**F#**<br />
``` F#
static member Decrypt : 
        encryptedData : byte[] * 
        key : byte[] * 
        privacyParameters : byte[] -> byte[] 

```


#### Parameters
&nbsp;<dl><dt>encryptedData</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.byte" target="_blank" rel="noopener noreferrer">System.Byte</a>[]<br /></dd><dt>key</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.byte" target="_blank" rel="noopener noreferrer">System.Byte</a>[]<br /></dd><dt>privacyParameters</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.byte" target="_blank" rel="noopener noreferrer">System.Byte</a>[]<br /></dd></dl>

#### Return Value
Type: <a href="https://docs.microsoft.com/dotnet/api/system.byte" target="_blank" rel="noopener noreferrer">Byte</a>[]

## See Also


#### Reference
<a href="T_Lextm_SharpSnmpLib_Security_DESPrivacyProvider">DESPrivacyProvider Class</a><br /><a href="Overload_Lextm_SharpSnmpLib_Security_DESPrivacyProvider_Decrypt">Decrypt Overload</a><br /><a href="N_Lextm_SharpSnmpLib_Security">Lextm.SharpSnmpLib.Security Namespace</a><br />