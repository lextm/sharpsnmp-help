# MD5AuthenticationProvider.ComputeHash Method 
 

**Namespace:**&nbsp;<a href="N_Lextm_SharpSnmpLib_Security">Lextm.SharpSnmpLib.Security</a><br />**Assembly:**&nbsp;SharpSnmpLib (in SharpSnmpLib.dll) Version: 12.4.0+601762d0e653a71ebb69af963204dfbfb6c26b74

## Syntax

**C#**<br />
``` C#
public OctetString ComputeHash(
	VersionCode version,
	ISegment header,
	SecurityParameters parameters,
	ISnmpData data,
	IPrivacyProvider privacy,
	byte[] length
)
```

**VB**<br />
``` VB
Public Function ComputeHash ( 
	version As VersionCode,
	header As ISegment,
	parameters As SecurityParameters,
	data As ISnmpData,
	privacy As IPrivacyProvider,
	length As Byte()
) As OctetString
```

**C++**<br />
``` C++
public:
virtual OctetString^ ComputeHash(
	VersionCode version, 
	ISegment^ header, 
	SecurityParameters^ parameters, 
	ISnmpData^ data, 
	IPrivacyProvider^ privacy, 
	array<unsigned char>^ length
) sealed
```

**F#**<br />
``` F#
abstract ComputeHash : 
        version : VersionCode * 
        header : ISegment * 
        parameters : SecurityParameters * 
        data : ISnmpData * 
        privacy : IPrivacyProvider * 
        length : byte[] -> OctetString 
override ComputeHash : 
        version : VersionCode * 
        header : ISegment * 
        parameters : SecurityParameters * 
        data : ISnmpData * 
        privacy : IPrivacyProvider * 
        length : byte[] -> OctetString 
```


#### Parameters
&nbsp;<dl><dt>version</dt><dd>Type: <a href="T_Lextm_SharpSnmpLib_VersionCode">Lextm.SharpSnmpLib.VersionCode</a><br /></dd><dt>header</dt><dd>Type: <a href="T_Lextm_SharpSnmpLib_ISegment">Lextm.SharpSnmpLib.ISegment</a><br /></dd><dt>parameters</dt><dd>Type: <a href="T_Lextm_SharpSnmpLib_SecurityParameters">Lextm.SharpSnmpLib.SecurityParameters</a><br /></dd><dt>data</dt><dd>Type: <a href="T_Lextm_SharpSnmpLib_ISnmpData">Lextm.SharpSnmpLib.ISnmpData</a><br /></dd><dt>privacy</dt><dd>Type: <a href="T_Lextm_SharpSnmpLib_Security_IPrivacyProvider">Lextm.SharpSnmpLib.Security.IPrivacyProvider</a><br /></dd><dt>length</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.byte" target="_blank" rel="noopener noreferrer">System.Byte</a>[]<br /></dd></dl>

#### Return Value
Type: <a href="T_Lextm_SharpSnmpLib_OctetString">OctetString</a>

#### Implements
<a href="M_Lextm_SharpSnmpLib_Security_IAuthenticationProvider_ComputeHash">IAuthenticationProvider.ComputeHash(VersionCode, ISegment, SecurityParameters, ISnmpData, IPrivacyProvider, Byte[])</a><br />

## See Also


#### Reference
<a href="T_Lextm_SharpSnmpLib_Security_MD5AuthenticationProvider">MD5AuthenticationProvider Class</a><br /><a href="N_Lextm_SharpSnmpLib_Security">Lextm.SharpSnmpLib.Security Namespace</a><br />