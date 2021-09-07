# SecurityParameters Constructor (OctetString, Integer32, Integer32, OctetString, OctetString, OctetString)
 

Initializes a new instance of the <a href="T_Lextm_SharpSnmpLib_SecurityParameters">SecurityParameters</a> class

**Namespace:**&nbsp;<a href="N_Lextm_SharpSnmpLib">Lextm.SharpSnmpLib</a><br />**Assembly:**&nbsp;SharpSnmpLib (in SharpSnmpLib.dll) Version: 12.4.0+601762d0e653a71ebb69af963204dfbfb6c26b74

## Syntax

**C#**<br />
``` C#
public SecurityParameters(
	OctetString engineId,
	Integer32 engineBoots,
	Integer32 engineTime,
	OctetString userName,
	OctetString authenticationParameters,
	OctetString privacyParameters
)
```

**VB**<br />
``` VB
Public Sub New ( 
	engineId As OctetString,
	engineBoots As Integer32,
	engineTime As Integer32,
	userName As OctetString,
	authenticationParameters As OctetString,
	privacyParameters As OctetString
)
```

**C++**<br />
``` C++
public:
SecurityParameters(
	OctetString^ engineId, 
	Integer32^ engineBoots, 
	Integer32^ engineTime, 
	OctetString^ userName, 
	OctetString^ authenticationParameters, 
	OctetString^ privacyParameters
)
```

**F#**<br />
``` F#
new : 
        engineId : OctetString * 
        engineBoots : Integer32 * 
        engineTime : Integer32 * 
        userName : OctetString * 
        authenticationParameters : OctetString * 
        privacyParameters : OctetString -> SecurityParameters
```


#### Parameters
&nbsp;<dl><dt>engineId</dt><dd>Type: <a href="T_Lextm_SharpSnmpLib_OctetString">Lextm.SharpSnmpLib.OctetString</a><br /></dd><dt>engineBoots</dt><dd>Type: <a href="T_Lextm_SharpSnmpLib_Integer32">Lextm.SharpSnmpLib.Integer32</a><br /></dd><dt>engineTime</dt><dd>Type: <a href="T_Lextm_SharpSnmpLib_Integer32">Lextm.SharpSnmpLib.Integer32</a><br /></dd><dt>userName</dt><dd>Type: <a href="T_Lextm_SharpSnmpLib_OctetString">Lextm.SharpSnmpLib.OctetString</a><br /></dd><dt>authenticationParameters</dt><dd>Type: <a href="T_Lextm_SharpSnmpLib_OctetString">Lextm.SharpSnmpLib.OctetString</a><br /></dd><dt>privacyParameters</dt><dd>Type: <a href="T_Lextm_SharpSnmpLib_OctetString">Lextm.SharpSnmpLib.OctetString</a><br /></dd></dl>

## See Also


#### Reference
<a href="T_Lextm_SharpSnmpLib_SecurityParameters">SecurityParameters Class</a><br /><a href="Overload_Lextm_SharpSnmpLib_SecurityParameters__ctor">SecurityParameters Overload</a><br /><a href="N_Lextm_SharpSnmpLib">Lextm.SharpSnmpLib Namespace</a><br />