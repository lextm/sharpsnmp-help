# DefaultPrivacyProvider.EngineId Property 
 

**Note: This API is now obsolete.**

**Namespace:**&nbsp;<a href="N_Lextm_SharpSnmpLib_Security">Lextm.SharpSnmpLib.Security</a><br />**Assembly:**&nbsp;SharpSnmpLib (in SharpSnmpLib.dll) Version: 12.4.0+601762d0e653a71ebb69af963204dfbfb6c26b74

## Syntax

**C#**<br />
``` C#
[ObsoleteAttribute("Use EngineIds instead.")]
public OctetString EngineId { get; set; }
```

**VB**<br />
``` VB
<ObsoleteAttribute("Use EngineIds instead.")>
Public Property EngineId As OctetString
	Get
	Set
```

**C++**<br />
``` C++
public:
[ObsoleteAttribute(L"Use EngineIds instead.")]
virtual property OctetString^ EngineId {
	OctetString^ get () sealed;
	void set (OctetString^ value) sealed;
}
```

**F#**<br />
``` F#
[<ObsoleteAttribute("Use EngineIds instead.")>]
abstract EngineId : OctetString with get, set
[<ObsoleteAttribute("Use EngineIds instead.")>]
override EngineId : OctetString with get, set
```


#### Property Value
Type: <a href="T_Lextm_SharpSnmpLib_OctetString">OctetString</a>

#### Implements
<a href="P_Lextm_SharpSnmpLib_Security_IPrivacyProvider_EngineId">IPrivacyProvider.EngineId</a><br />

## See Also


#### Reference
<a href="T_Lextm_SharpSnmpLib_Security_DefaultPrivacyProvider">DefaultPrivacyProvider Class</a><br /><a href="N_Lextm_SharpSnmpLib_Security">Lextm.SharpSnmpLib.Security Namespace</a><br />