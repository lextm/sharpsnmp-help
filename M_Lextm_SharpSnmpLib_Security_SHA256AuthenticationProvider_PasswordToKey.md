# SHA256AuthenticationProvider.PasswordToKey Method 
 

**Namespace:**&nbsp;<a href="N_Lextm_SharpSnmpLib_Security">Lextm.SharpSnmpLib.Security</a><br />**Assembly:**&nbsp;SharpSnmpLib (in SharpSnmpLib.dll) Version: 12.4.0+601762d0e653a71ebb69af963204dfbfb6c26b74

## Syntax

**C#**<br />
``` C#
public byte[] PasswordToKey(
	byte[] password,
	byte[] engineId
)
```

**VB**<br />
``` VB
Public Function PasswordToKey ( 
	password As Byte(),
	engineId As Byte()
) As Byte()
```

**C++**<br />
``` C++
public:
virtual array<unsigned char>^ PasswordToKey(
	array<unsigned char>^ password, 
	array<unsigned char>^ engineId
) sealed
```

**F#**<br />
``` F#
abstract PasswordToKey : 
        password : byte[] * 
        engineId : byte[] -> byte[] 
override PasswordToKey : 
        password : byte[] * 
        engineId : byte[] -> byte[] 
```


#### Parameters
&nbsp;<dl><dt>password</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.byte" target="_blank" rel="noopener noreferrer">System.Byte</a>[]<br /></dd><dt>engineId</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.byte" target="_blank" rel="noopener noreferrer">System.Byte</a>[]<br /></dd></dl>

#### Return Value
Type: <a href="https://docs.microsoft.com/dotnet/api/system.byte" target="_blank" rel="noopener noreferrer">Byte</a>[]

#### Implements
<a href="M_Lextm_SharpSnmpLib_Security_IAuthenticationProvider_PasswordToKey">IAuthenticationProvider.PasswordToKey(Byte[], Byte[])</a><br />

## See Also


#### Reference
<a href="T_Lextm_SharpSnmpLib_Security_SHA256AuthenticationProvider">SHA256AuthenticationProvider Class</a><br /><a href="N_Lextm_SharpSnmpLib_Security">Lextm.SharpSnmpLib.Security Namespace</a><br />