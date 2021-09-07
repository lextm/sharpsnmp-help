# AESPrivacyProviderBase.Decrypt Method 
 

**Namespace:**&nbsp;<a href="N_Lextm_SharpSnmpLib_Security">Lextm.SharpSnmpLib.Security</a><br />**Assembly:**&nbsp;SharpSnmpLib (in SharpSnmpLib.dll) Version: 12.4.0+601762d0e653a71ebb69af963204dfbfb6c26b74

## Syntax

**C#**<br />
``` C#
public ISnmpData Decrypt(
	ISnmpData data,
	SecurityParameters parameters
)
```

**VB**<br />
``` VB
Public Function Decrypt ( 
	data As ISnmpData,
	parameters As SecurityParameters
) As ISnmpData
```

**C++**<br />
``` C++
public:
virtual ISnmpData^ Decrypt(
	ISnmpData^ data, 
	SecurityParameters^ parameters
) sealed
```

**F#**<br />
``` F#
abstract Decrypt : 
        data : ISnmpData * 
        parameters : SecurityParameters -> ISnmpData 
override Decrypt : 
        data : ISnmpData * 
        parameters : SecurityParameters -> ISnmpData 
```


#### Parameters
&nbsp;<dl><dt>data</dt><dd>Type: <a href="T_Lextm_SharpSnmpLib_ISnmpData">Lextm.SharpSnmpLib.ISnmpData</a><br /></dd><dt>parameters</dt><dd>Type: <a href="T_Lextm_SharpSnmpLib_SecurityParameters">Lextm.SharpSnmpLib.SecurityParameters</a><br /></dd></dl>

#### Return Value
Type: <a href="T_Lextm_SharpSnmpLib_ISnmpData">ISnmpData</a>

#### Implements
<a href="M_Lextm_SharpSnmpLib_Security_IPrivacyProvider_Decrypt">IPrivacyProvider.Decrypt(ISnmpData, SecurityParameters)</a><br />

## See Also


#### Reference
<a href="T_Lextm_SharpSnmpLib_Security_AESPrivacyProviderBase">AESPrivacyProviderBase Class</a><br /><a href="N_Lextm_SharpSnmpLib_Security">Lextm.SharpSnmpLib.Security Namespace</a><br />