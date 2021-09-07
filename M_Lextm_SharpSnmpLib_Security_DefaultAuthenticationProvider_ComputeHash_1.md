# DefaultAuthenticationProvider.ComputeHash Method (Byte[], OctetString)
 

**Namespace:**&nbsp;<a href="N_Lextm_SharpSnmpLib_Security">Lextm.SharpSnmpLib.Security</a><br />**Assembly:**&nbsp;SharpSnmpLib (in SharpSnmpLib.dll) Version: 12.4.0+601762d0e653a71ebb69af963204dfbfb6c26b74

## Syntax

**C#**<br />
``` C#
public OctetString ComputeHash(
	byte[] buffer,
	OctetString engineId
)
```

**VB**<br />
``` VB
Public Function ComputeHash ( 
	buffer As Byte(),
	engineId As OctetString
) As OctetString
```

**C++**<br />
``` C++
public:
OctetString^ ComputeHash(
	array<unsigned char>^ buffer, 
	OctetString^ engineId
)
```

**F#**<br />
``` F#
member ComputeHash : 
        buffer : byte[] * 
        engineId : OctetString -> OctetString 

```


#### Parameters
&nbsp;<dl><dt>buffer</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.byte" target="_blank" rel="noopener noreferrer">System.Byte</a>[]<br /></dd><dt>engineId</dt><dd>Type: <a href="T_Lextm_SharpSnmpLib_OctetString">Lextm.SharpSnmpLib.OctetString</a><br /></dd></dl>

#### Return Value
Type: <a href="T_Lextm_SharpSnmpLib_OctetString">OctetString</a>

## See Also


#### Reference
<a href="T_Lextm_SharpSnmpLib_Security_DefaultAuthenticationProvider">DefaultAuthenticationProvider Class</a><br /><a href="Overload_Lextm_SharpSnmpLib_Security_DefaultAuthenticationProvider_ComputeHash">ComputeHash Overload</a><br /><a href="N_Lextm_SharpSnmpLib_Security">Lextm.SharpSnmpLib.Security Namespace</a><br />