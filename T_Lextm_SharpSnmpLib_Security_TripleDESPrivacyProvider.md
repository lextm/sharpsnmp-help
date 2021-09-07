# TripleDESPrivacyProvider Class
 

**Note: This API is now obsolete.**


## Inheritance Hierarchy
<a href="https://docs.microsoft.com/dotnet/api/system.object" target="_blank" rel="noopener noreferrer">System.Object</a><br />&nbsp;&nbsp;Lextm.SharpSnmpLib.Security.TripleDESPrivacyProvider<br />
**Namespace:**&nbsp;<a href="N_Lextm_SharpSnmpLib_Security">Lextm.SharpSnmpLib.Security</a><br />**Assembly:**&nbsp;SharpSnmpLib (in SharpSnmpLib.dll) Version: 12.4.0+601762d0e653a71ebb69af963204dfbfb6c26b74

## Syntax

**C#**<br />
``` C#
[ObsoleteAttribute("3DES is no longer secure. Please use a more secure provider.")]
public sealed class TripleDESPrivacyProvider : IPrivacyProvider
```

**VB**<br />
``` VB
<ObsoleteAttribute("3DES is no longer secure. Please use a more secure provider.")>
Public NotInheritable Class TripleDESPrivacyProvider
	Implements IPrivacyProvider
```

**C++**<br />
``` C++
[ObsoleteAttribute(L"3DES is no longer secure. Please use a more secure provider.")]
public ref class TripleDESPrivacyProvider sealed : IPrivacyProvider
```

**F#**<br />
``` F#
[<SealedAttribute>]
[<ObsoleteAttribute("3DES is no longer secure. Please use a more secure provider.")>]
type TripleDESPrivacyProvider =  
    class
        interface IPrivacyProvider
    end
```

The TripleDESPrivacyProvider type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Lextm_SharpSnmpLib_Security_TripleDESPrivacyProvider__ctor">TripleDESPrivacyProvider</a></td><td>
Initializes a new instance of the TripleDESPrivacyProvider class</td></tr></table>&nbsp;
<a href="#tripledesprivacyprovider-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Lextm_SharpSnmpLib_Security_TripleDESPrivacyProvider_AuthenticationProvider">AuthenticationProvider</a></td><td /></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Lextm_SharpSnmpLib_Security_TripleDESPrivacyProvider_EngineId">EngineId</a></td><td> **Obsolete. **</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Lextm_SharpSnmpLib_Security_TripleDESPrivacyProvider_EngineIds">EngineIds</a></td><td /></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_Lextm_SharpSnmpLib_Security_TripleDESPrivacyProvider_MaximumKeyLength">MaximumKeyLength</a></td><td /></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_Lextm_SharpSnmpLib_Security_TripleDESPrivacyProvider_MinimumKeyLength">MinimumKeyLength</a></td><td /></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_Lextm_SharpSnmpLib_Security_TripleDESPrivacyProvider_PrivacyParametersLength">PrivacyParametersLength</a></td><td /></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Lextm_SharpSnmpLib_Security_TripleDESPrivacyProvider_Salt">Salt</a></td><td /></tr></table>&nbsp;
<a href="#tripledesprivacyprovider-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Lextm_SharpSnmpLib_Security_TripleDESPrivacyProvider_Decrypt">Decrypt(ISnmpData, SecurityParameters)</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_Lextm_SharpSnmpLib_Security_TripleDESPrivacyProvider_Decrypt_1">Decrypt(Byte[], Byte[], Byte[])</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Lextm_SharpSnmpLib_Security_TripleDESPrivacyProvider_Encrypt">Encrypt(ISnmpData, SecurityParameters)</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_Lextm_SharpSnmpLib_Security_TripleDESPrivacyProvider_Encrypt_1">Encrypt(Byte[], Byte[], Byte[])</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="https://docs.microsoft.com/dotnet/api/system.object.equals#System_Object_Equals_System_Object_" target="_blank" rel="noopener noreferrer">Equals</a></td><td>
Determines whether the specified object is equal to the current object.
 (Inherited from <a href="https://docs.microsoft.com/dotnet/api/system.object" target="_blank" rel="noopener noreferrer">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="https://docs.microsoft.com/dotnet/api/system.object.gethashcode#System_Object_GetHashCode" target="_blank" rel="noopener noreferrer">GetHashCode</a></td><td>
Serves as the default hash function.
 (Inherited from <a href="https://docs.microsoft.com/dotnet/api/system.object" target="_blank" rel="noopener noreferrer">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="https://docs.microsoft.com/dotnet/api/system.object.gettype#System_Object_GetType" target="_blank" rel="noopener noreferrer">GetType</a></td><td>
Gets the <a href="https://docs.microsoft.com/dotnet/api/system.type" target="_blank" rel="noopener noreferrer">Type</a> of the current instance.
 (Inherited from <a href="https://docs.microsoft.com/dotnet/api/system.object" target="_blank" rel="noopener noreferrer">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Lextm_SharpSnmpLib_Security_TripleDESPrivacyProvider_PasswordToKey">PasswordToKey</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Lextm_SharpSnmpLib_Security_TripleDESPrivacyProvider_ToString">ToString</a></td><td> (Overrides <a href="https://docs.microsoft.com/dotnet/api/system.object.tostring#System_Object_ToString" target="_blank" rel="noopener noreferrer">Object.ToString()</a>.)</td></tr></table>&nbsp;
<a href="#tripledesprivacyprovider-class">Back to Top</a>

## Extension Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_Lextm_SharpSnmpLib_Security_PrivacyProviderExtension_ComputeHash">ComputeHash</a></td><td> (Defined by <a href="T_Lextm_SharpSnmpLib_Security_PrivacyProviderExtension">PrivacyProviderExtension</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_Lextm_SharpSnmpLib_Security_PrivacyProviderExtension_GetScopeData">GetScopeData</a></td><td> (Defined by <a href="T_Lextm_SharpSnmpLib_Security_PrivacyProviderExtension">PrivacyProviderExtension</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_Lextm_SharpSnmpLib_Security_PrivacyProviderExtension_ToSecurityLevel">ToSecurityLevel</a></td><td> (Defined by <a href="T_Lextm_SharpSnmpLib_Security_PrivacyProviderExtension">PrivacyProviderExtension</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_Lextm_SharpSnmpLib_Security_PrivacyProviderExtension_VerifyHash">VerifyHash</a></td><td> (Defined by <a href="T_Lextm_SharpSnmpLib_Security_PrivacyProviderExtension">PrivacyProviderExtension</a>.)</td></tr></table>&nbsp;
<a href="#tripledesprivacyprovider-class">Back to Top</a>

## See Also


#### Reference
<a href="N_Lextm_SharpSnmpLib_Security">Lextm.SharpSnmpLib.Security Namespace</a><br />