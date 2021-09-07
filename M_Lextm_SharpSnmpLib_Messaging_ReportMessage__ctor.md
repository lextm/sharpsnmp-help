# ReportMessage Constructor 
 

Initializes a new instance of the <a href="T_Lextm_SharpSnmpLib_Messaging_ReportMessage">ReportMessage</a> class

**Namespace:**&nbsp;<a href="N_Lextm_SharpSnmpLib_Messaging">Lextm.SharpSnmpLib.Messaging</a><br />**Assembly:**&nbsp;SharpSnmpLib (in SharpSnmpLib.dll) Version: 12.4.0+601762d0e653a71ebb69af963204dfbfb6c26b74

## Syntax

**C#**<br />
``` C#
public ReportMessage(
	VersionCode version,
	Header header,
	SecurityParameters parameters,
	Scope scope,
	IPrivacyProvider privacy,
	byte[] length
)
```

**VB**<br />
``` VB
Public Sub New ( 
	version As VersionCode,
	header As Header,
	parameters As SecurityParameters,
	scope As Scope,
	privacy As IPrivacyProvider,
	length As Byte()
)
```

**C++**<br />
``` C++
public:
ReportMessage(
	VersionCode version, 
	Header^ header, 
	SecurityParameters^ parameters, 
	Scope^ scope, 
	IPrivacyProvider^ privacy, 
	array<unsigned char>^ length
)
```

**F#**<br />
``` F#
new : 
        version : VersionCode * 
        header : Header * 
        parameters : SecurityParameters * 
        scope : Scope * 
        privacy : IPrivacyProvider * 
        length : byte[] -> ReportMessage
```


#### Parameters
&nbsp;<dl><dt>version</dt><dd>Type: <a href="T_Lextm_SharpSnmpLib_VersionCode">Lextm.SharpSnmpLib.VersionCode</a><br /></dd><dt>header</dt><dd>Type: <a href="T_Lextm_SharpSnmpLib_Header">Lextm.SharpSnmpLib.Header</a><br /></dd><dt>parameters</dt><dd>Type: <a href="T_Lextm_SharpSnmpLib_SecurityParameters">Lextm.SharpSnmpLib.SecurityParameters</a><br /></dd><dt>scope</dt><dd>Type: <a href="T_Lextm_SharpSnmpLib_Scope">Lextm.SharpSnmpLib.Scope</a><br /></dd><dt>privacy</dt><dd>Type: <a href="T_Lextm_SharpSnmpLib_Security_IPrivacyProvider">Lextm.SharpSnmpLib.Security.IPrivacyProvider</a><br /></dd><dt>length</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.byte" target="_blank" rel="noopener noreferrer">System.Byte</a>[]<br /></dd></dl>

## See Also


#### Reference
<a href="T_Lextm_SharpSnmpLib_Messaging_ReportMessage">ReportMessage Class</a><br /><a href="N_Lextm_SharpSnmpLib_Messaging">Lextm.SharpSnmpLib.Messaging Namespace</a><br />