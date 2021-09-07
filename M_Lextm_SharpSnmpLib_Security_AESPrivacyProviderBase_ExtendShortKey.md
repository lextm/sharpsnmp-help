# AESPrivacyProviderBase.ExtendShortKey Method 
 

**Namespace:**&nbsp;<a href="N_Lextm_SharpSnmpLib_Security">Lextm.SharpSnmpLib.Security</a><br />**Assembly:**&nbsp;SharpSnmpLib (in SharpSnmpLib.dll) Version: 12.4.0+601762d0e653a71ebb69af963204dfbfb6c26b74

## Syntax

**C#**<br />
``` C#
public byte[] ExtendShortKey(
	byte[] shortKey,
	byte[] password,
	byte[] engineID,
	IAuthenticationProvider authProtocol
)
```

**VB**<br />
``` VB
Public Function ExtendShortKey ( 
	shortKey As Byte(),
	password As Byte(),
	engineID As Byte(),
	authProtocol As IAuthenticationProvider
) As Byte()
```

**C++**<br />
``` C++
public:
array<unsigned char>^ ExtendShortKey(
	array<unsigned char>^ shortKey, 
	array<unsigned char>^ password, 
	array<unsigned char>^ engineID, 
	IAuthenticationProvider^ authProtocol
)
```

**F#**<br />
``` F#
member ExtendShortKey : 
        shortKey : byte[] * 
        password : byte[] * 
        engineID : byte[] * 
        authProtocol : IAuthenticationProvider -> byte[] 

```


#### Parameters
&nbsp;<dl><dt>shortKey</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.byte" target="_blank" rel="noopener noreferrer">System.Byte</a>[]<br /></dd><dt>password</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.byte" target="_blank" rel="noopener noreferrer">System.Byte</a>[]<br /></dd><dt>engineID</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.byte" target="_blank" rel="noopener noreferrer">System.Byte</a>[]<br /></dd><dt>authProtocol</dt><dd>Type: <a href="T_Lextm_SharpSnmpLib_Security_IAuthenticationProvider">Lextm.SharpSnmpLib.Security.IAuthenticationProvider</a><br /></dd></dl>

#### Return Value
Type: <a href="https://docs.microsoft.com/dotnet/api/system.byte" target="_blank" rel="noopener noreferrer">Byte</a>[]

## See Also


#### Reference
<a href="T_Lextm_SharpSnmpLib_Security_AESPrivacyProviderBase">AESPrivacyProviderBase Class</a><br /><a href="N_Lextm_SharpSnmpLib_Security">Lextm.SharpSnmpLib.Security Namespace</a><br />