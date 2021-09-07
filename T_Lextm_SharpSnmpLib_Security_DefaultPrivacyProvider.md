# DefaultPrivacyProvider Class
 


## Inheritance Hierarchy
<a href="https://docs.microsoft.com/dotnet/api/system.object" target="_blank" rel="noopener noreferrer">System.Object</a><br />&nbsp;&nbsp;Lextm.SharpSnmpLib.Security.DefaultPrivacyProvider<br />
**Namespace:**&nbsp;<a href="N_Lextm_SharpSnmpLib_Security">Lextm.SharpSnmpLib.Security</a><br />**Assembly:**&nbsp;SharpSnmpLib (in SharpSnmpLib.dll) Version: 12.4.0+601762d0e653a71ebb69af963204dfbfb6c26b74

## Syntax

**C#**<br />
``` C#
public sealed class DefaultPrivacyProvider : IPrivacyProvider
```

**VB**<br />
``` VB
Public NotInheritable Class DefaultPrivacyProvider
	Implements IPrivacyProvider
```

**C++**<br />
``` C++
public ref class DefaultPrivacyProvider sealed : IPrivacyProvider
```

**F#**<br />
``` F#
[<SealedAttribute>]
type DefaultPrivacyProvider =  
    class
        interface IPrivacyProvider
    end
```

The DefaultPrivacyProvider type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Lextm_SharpSnmpLib_Security_DefaultPrivacyProvider__ctor">DefaultPrivacyProvider</a></td><td>
Initializes a new instance of the DefaultPrivacyProvider class</td></tr></table>&nbsp;
<a href="#defaultprivacyprovider-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Lextm_SharpSnmpLib_Security_DefaultPrivacyProvider_AuthenticationProvider">AuthenticationProvider</a></td><td /></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_Lextm_SharpSnmpLib_Security_DefaultPrivacyProvider_DefaultPair">DefaultPair</a></td><td /></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Lextm_SharpSnmpLib_Security_DefaultPrivacyProvider_EngineId">EngineId</a></td><td> **Obsolete. **</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Lextm_SharpSnmpLib_Security_DefaultPrivacyProvider_EngineIds">EngineIds</a></td><td /></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Lextm_SharpSnmpLib_Security_DefaultPrivacyProvider_Salt">Salt</a></td><td /></tr></table>&nbsp;
<a href="#defaultprivacyprovider-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Lextm_SharpSnmpLib_Security_DefaultPrivacyProvider_Decrypt">Decrypt</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Lextm_SharpSnmpLib_Security_DefaultPrivacyProvider_Encrypt">Encrypt</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="https://docs.microsoft.com/dotnet/api/system.object.equals#System_Object_Equals_System_Object_" target="_blank" rel="noopener noreferrer">Equals</a></td><td>
Determines whether the specified object is equal to the current object.
 (Inherited from <a href="https://docs.microsoft.com/dotnet/api/system.object" target="_blank" rel="noopener noreferrer">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="https://docs.microsoft.com/dotnet/api/system.object.gethashcode#System_Object_GetHashCode" target="_blank" rel="noopener noreferrer">GetHashCode</a></td><td>
Serves as the default hash function.
 (Inherited from <a href="https://docs.microsoft.com/dotnet/api/system.object" target="_blank" rel="noopener noreferrer">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="https://docs.microsoft.com/dotnet/api/system.object.gettype#System_Object_GetType" target="_blank" rel="noopener noreferrer">GetType</a></td><td>
Gets the <a href="https://docs.microsoft.com/dotnet/api/system.type" target="_blank" rel="noopener noreferrer">Type</a> of the current instance.
 (Inherited from <a href="https://docs.microsoft.com/dotnet/api/system.object" target="_blank" rel="noopener noreferrer">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Lextm_SharpSnmpLib_Security_DefaultPrivacyProvider_PasswordToKey">PasswordToKey</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Lextm_SharpSnmpLib_Security_DefaultPrivacyProvider_ToString">ToString</a></td><td> (Overrides <a href="https://docs.microsoft.com/dotnet/api/system.object.tostring#System_Object_ToString" target="_blank" rel="noopener noreferrer">Object.ToString()</a>.)</td></tr></table>&nbsp;
<a href="#defaultprivacyprovider-class">Back to Top</a>

## Extension Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_Lextm_SharpSnmpLib_Security_PrivacyProviderExtension_ComputeHash">ComputeHash</a></td><td> (Defined by <a href="T_Lextm_SharpSnmpLib_Security_PrivacyProviderExtension">PrivacyProviderExtension</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_Lextm_SharpSnmpLib_Security_PrivacyProviderExtension_GetScopeData">GetScopeData</a></td><td> (Defined by <a href="T_Lextm_SharpSnmpLib_Security_PrivacyProviderExtension">PrivacyProviderExtension</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_Lextm_SharpSnmpLib_Security_PrivacyProviderExtension_ToSecurityLevel">ToSecurityLevel</a></td><td> (Defined by <a href="T_Lextm_SharpSnmpLib_Security_PrivacyProviderExtension">PrivacyProviderExtension</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_Lextm_SharpSnmpLib_Security_PrivacyProviderExtension_VerifyHash">VerifyHash</a></td><td> (Defined by <a href="T_Lextm_SharpSnmpLib_Security_PrivacyProviderExtension">PrivacyProviderExtension</a>.)</td></tr></table>&nbsp;
<a href="#defaultprivacyprovider-class">Back to Top</a>

## See Also


#### Reference
<a href="N_Lextm_SharpSnmpLib_Security">Lextm.SharpSnmpLib.Security Namespace</a><br />