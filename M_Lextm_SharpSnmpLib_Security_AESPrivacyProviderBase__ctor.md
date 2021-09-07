# AESPrivacyProviderBase Constructor 
 

Initializes a new instance of the <a href="T_Lextm_SharpSnmpLib_Security_AESPrivacyProviderBase">AESPrivacyProviderBase</a> class

**Namespace:**&nbsp;<a href="N_Lextm_SharpSnmpLib_Security">Lextm.SharpSnmpLib.Security</a><br />**Assembly:**&nbsp;SharpSnmpLib (in SharpSnmpLib.dll) Version: 12.4.0+601762d0e653a71ebb69af963204dfbfb6c26b74

## Syntax

**C#**<br />
``` C#
protected AESPrivacyProviderBase(
	int keyBytes,
	OctetString phrase,
	IAuthenticationProvider auth
)
```

**VB**<br />
``` VB
Protected Sub New ( 
	keyBytes As Integer,
	phrase As OctetString,
	auth As IAuthenticationProvider
)
```

**C++**<br />
``` C++
protected:
AESPrivacyProviderBase(
	int keyBytes, 
	OctetString^ phrase, 
	IAuthenticationProvider^ auth
)
```

**F#**<br />
``` F#
new : 
        keyBytes : int * 
        phrase : OctetString * 
        auth : IAuthenticationProvider -> AESPrivacyProviderBase
```


#### Parameters
&nbsp;<dl><dt>keyBytes</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.int32" target="_blank" rel="noopener noreferrer">System.Int32</a><br /></dd><dt>phrase</dt><dd>Type: <a href="T_Lextm_SharpSnmpLib_OctetString">Lextm.SharpSnmpLib.OctetString</a><br /></dd><dt>auth</dt><dd>Type: <a href="T_Lextm_SharpSnmpLib_Security_IAuthenticationProvider">Lextm.SharpSnmpLib.Security.IAuthenticationProvider</a><br /></dd></dl>

## See Also


#### Reference
<a href="T_Lextm_SharpSnmpLib_Security_AESPrivacyProviderBase">AESPrivacyProviderBase Class</a><br /><a href="N_Lextm_SharpSnmpLib_Security">Lextm.SharpSnmpLib.Security Namespace</a><br />