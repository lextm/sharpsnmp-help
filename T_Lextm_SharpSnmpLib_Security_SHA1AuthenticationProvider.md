# SHA1AuthenticationProvider Class
 

**Note: This API is now obsolete.**


## Inheritance Hierarchy
<a href="https://docs.microsoft.com/dotnet/api/system.object" target="_blank" rel="noopener noreferrer">System.Object</a><br />&nbsp;&nbsp;Lextm.SharpSnmpLib.Security.SHA1AuthenticationProvider<br />
**Namespace:**&nbsp;<a href="N_Lextm_SharpSnmpLib_Security">Lextm.SharpSnmpLib.Security</a><br />**Assembly:**&nbsp;SharpSnmpLib (in SharpSnmpLib.dll) Version: 12.4.0+601762d0e653a71ebb69af963204dfbfb6c26b74

## Syntax

**C#**<br />
``` C#
[ObsoleteAttribute("SHA-1 is no longer secure. Please use a more secure provider.")]
public sealed class SHA1AuthenticationProvider : IAuthenticationProvider
```

**VB**<br />
``` VB
<ObsoleteAttribute("SHA-1 is no longer secure. Please use a more secure provider.")>
Public NotInheritable Class SHA1AuthenticationProvider
	Implements IAuthenticationProvider
```

**C++**<br />
``` C++
[ObsoleteAttribute(L"SHA-1 is no longer secure. Please use a more secure provider.")]
public ref class SHA1AuthenticationProvider sealed : IAuthenticationProvider
```

**F#**<br />
``` F#
[<SealedAttribute>]
[<ObsoleteAttribute("SHA-1 is no longer secure. Please use a more secure provider.")>]
type SHA1AuthenticationProvider =  
    class
        interface IAuthenticationProvider
    end
```

The SHA1AuthenticationProvider type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Lextm_SharpSnmpLib_Security_SHA1AuthenticationProvider__ctor">SHA1AuthenticationProvider</a></td><td>
Initializes a new instance of the SHA1AuthenticationProvider class</td></tr></table>&nbsp;
<a href="#sha1authenticationprovider-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Lextm_SharpSnmpLib_Security_SHA1AuthenticationProvider_CleanDigest">CleanDigest</a></td><td /></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Lextm_SharpSnmpLib_Security_SHA1AuthenticationProvider_DigestLength">DigestLength</a></td><td /></tr></table>&nbsp;
<a href="#sha1authenticationprovider-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Lextm_SharpSnmpLib_Security_SHA1AuthenticationProvider_ComputeHash">ComputeHash</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="https://docs.microsoft.com/dotnet/api/system.object.equals#System_Object_Equals_System_Object_" target="_blank" rel="noopener noreferrer">Equals</a></td><td>
Determines whether the specified object is equal to the current object.
 (Inherited from <a href="https://docs.microsoft.com/dotnet/api/system.object" target="_blank" rel="noopener noreferrer">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="https://docs.microsoft.com/dotnet/api/system.object.gethashcode#System_Object_GetHashCode" target="_blank" rel="noopener noreferrer">GetHashCode</a></td><td>
Serves as the default hash function.
 (Inherited from <a href="https://docs.microsoft.com/dotnet/api/system.object" target="_blank" rel="noopener noreferrer">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="https://docs.microsoft.com/dotnet/api/system.object.gettype#System_Object_GetType" target="_blank" rel="noopener noreferrer">GetType</a></td><td>
Gets the <a href="https://docs.microsoft.com/dotnet/api/system.type" target="_blank" rel="noopener noreferrer">Type</a> of the current instance.
 (Inherited from <a href="https://docs.microsoft.com/dotnet/api/system.object" target="_blank" rel="noopener noreferrer">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Lextm_SharpSnmpLib_Security_SHA1AuthenticationProvider_PasswordToKey">PasswordToKey</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Lextm_SharpSnmpLib_Security_SHA1AuthenticationProvider_ToString">ToString</a></td><td> (Overrides <a href="https://docs.microsoft.com/dotnet/api/system.object.tostring#System_Object_ToString" target="_blank" rel="noopener noreferrer">Object.ToString()</a>.)</td></tr></table>&nbsp;
<a href="#sha1authenticationprovider-class">Back to Top</a>

## See Also


#### Reference
<a href="N_Lextm_SharpSnmpLib_Security">Lextm.SharpSnmpLib.Security Namespace</a><br />