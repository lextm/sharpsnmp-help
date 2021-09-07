# MalformedMessage Class
 


## Inheritance Hierarchy
<a href="https://docs.microsoft.com/dotnet/api/system.object" target="_blank" rel="noopener noreferrer">System.Object</a><br />&nbsp;&nbsp;Lextm.SharpSnmpLib.Messaging.MalformedMessage<br />
**Namespace:**&nbsp;<a href="N_Lextm_SharpSnmpLib_Messaging">Lextm.SharpSnmpLib.Messaging</a><br />**Assembly:**&nbsp;SharpSnmpLib (in SharpSnmpLib.dll) Version: 12.4.0+601762d0e653a71ebb69af963204dfbfb6c26b74

## Syntax

**C#**<br />
``` C#
public sealed class MalformedMessage : ISnmpMessage
```

**VB**<br />
``` VB
Public NotInheritable Class MalformedMessage
	Implements ISnmpMessage
```

**C++**<br />
``` C++
public ref class MalformedMessage sealed : ISnmpMessage
```

**F#**<br />
``` F#
[<SealedAttribute>]
type MalformedMessage =  
    class
        interface ISnmpMessage
    end
```

The MalformedMessage type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Lextm_SharpSnmpLib_Messaging_MalformedMessage__ctor">MalformedMessage(Int32, OctetString)</a></td><td> **Obsolete. **
Initializes a new instance of the MalformedMessage class</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Lextm_SharpSnmpLib_Messaging_MalformedMessage__ctor_1">MalformedMessage(Int32, OctetString, ISnmpData)</a></td><td>
Initializes a new instance of the MalformedMessage class</td></tr></table>&nbsp;
<a href="#malformedmessage-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Lextm_SharpSnmpLib_Messaging_MalformedMessage_EncryptedScope">EncryptedScope</a></td><td /></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Lextm_SharpSnmpLib_Messaging_MalformedMessage_Header">Header</a></td><td /></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Lextm_SharpSnmpLib_Messaging_MalformedMessage_Parameters">Parameters</a></td><td /></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Lextm_SharpSnmpLib_Messaging_MalformedMessage_Privacy">Privacy</a></td><td /></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Lextm_SharpSnmpLib_Messaging_MalformedMessage_Scope">Scope</a></td><td /></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Lextm_SharpSnmpLib_Messaging_MalformedMessage_Version">Version</a></td><td /></tr></table>&nbsp;
<a href="#malformedmessage-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="https://docs.microsoft.com/dotnet/api/system.object.equals#System_Object_Equals_System_Object_" target="_blank" rel="noopener noreferrer">Equals</a></td><td>
Determines whether the specified object is equal to the current object.
 (Inherited from <a href="https://docs.microsoft.com/dotnet/api/system.object" target="_blank" rel="noopener noreferrer">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="https://docs.microsoft.com/dotnet/api/system.object.gethashcode#System_Object_GetHashCode" target="_blank" rel="noopener noreferrer">GetHashCode</a></td><td>
Serves as the default hash function.
 (Inherited from <a href="https://docs.microsoft.com/dotnet/api/system.object" target="_blank" rel="noopener noreferrer">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="https://docs.microsoft.com/dotnet/api/system.object.gettype#System_Object_GetType" target="_blank" rel="noopener noreferrer">GetType</a></td><td>
Gets the <a href="https://docs.microsoft.com/dotnet/api/system.type" target="_blank" rel="noopener noreferrer">Type</a> of the current instance.
 (Inherited from <a href="https://docs.microsoft.com/dotnet/api/system.object" target="_blank" rel="noopener noreferrer">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Lextm_SharpSnmpLib_Messaging_MalformedMessage_ToBytes">ToBytes</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Lextm_SharpSnmpLib_Messaging_MalformedMessage_ToString">ToString</a></td><td> (Overrides <a href="https://docs.microsoft.com/dotnet/api/system.object.tostring#System_Object_ToString" target="_blank" rel="noopener noreferrer">Object.ToString()</a>.)</td></tr></table>&nbsp;
<a href="#malformedmessage-class">Back to Top</a>

## Extension Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_Lextm_SharpSnmpLib_Messaging_SnmpMessageExtension_Community">Community</a></td><td> (Defined by <a href="T_Lextm_SharpSnmpLib_Messaging_SnmpMessageExtension">SnmpMessageExtension</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_Lextm_SharpSnmpLib_Messaging_SnmpMessageExtension_GetResponse">GetResponse(Int32, IPEndPoint)</a></td><td>Overloaded.   (Defined by <a href="T_Lextm_SharpSnmpLib_Messaging_SnmpMessageExtension">SnmpMessageExtension</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_Lextm_SharpSnmpLib_Messaging_SnmpMessageExtension_GetResponse_1">GetResponse(Int32, IPEndPoint, UserRegistry)</a></td><td>Overloaded.   (Defined by <a href="T_Lextm_SharpSnmpLib_Messaging_SnmpMessageExtension">SnmpMessageExtension</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_Lextm_SharpSnmpLib_Messaging_SnmpMessageExtension_GetResponse_3">GetResponse(Int32, IPEndPoint, Socket)</a></td><td>Overloaded.   (Defined by <a href="T_Lextm_SharpSnmpLib_Messaging_SnmpMessageExtension">SnmpMessageExtension</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_Lextm_SharpSnmpLib_Messaging_SnmpMessageExtension_GetResponse_2">GetResponse(Int32, IPEndPoint, UserRegistry, Socket)</a></td><td>Overloaded.   (Defined by <a href="T_Lextm_SharpSnmpLib_Messaging_SnmpMessageExtension">SnmpMessageExtension</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_Lextm_SharpSnmpLib_Messaging_SnmpMessageExtension_GetResponseAsync">GetResponseAsync(IPEndPoint)</a></td><td>Overloaded.   (Defined by <a href="T_Lextm_SharpSnmpLib_Messaging_SnmpMessageExtension">SnmpMessageExtension</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_Lextm_SharpSnmpLib_Messaging_SnmpMessageExtension_GetResponseAsync_1">GetResponseAsync(IPEndPoint, UserRegistry)</a></td><td>Overloaded.   (Defined by <a href="T_Lextm_SharpSnmpLib_Messaging_SnmpMessageExtension">SnmpMessageExtension</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_Lextm_SharpSnmpLib_Messaging_SnmpMessageExtension_GetResponseAsync_3">GetResponseAsync(IPEndPoint, Socket)</a></td><td>Overloaded.   (Defined by <a href="T_Lextm_SharpSnmpLib_Messaging_SnmpMessageExtension">SnmpMessageExtension</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_Lextm_SharpSnmpLib_Messaging_SnmpMessageExtension_GetResponseAsync_2">GetResponseAsync(IPEndPoint, UserRegistry, Socket)</a></td><td>Overloaded.   (Defined by <a href="T_Lextm_SharpSnmpLib_Messaging_SnmpMessageExtension">SnmpMessageExtension</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_Lextm_SharpSnmpLib_Messaging_SnmpMessageExtension_MessageId">MessageId</a></td><td> (Defined by <a href="T_Lextm_SharpSnmpLib_Messaging_SnmpMessageExtension">SnmpMessageExtension</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_Lextm_SharpSnmpLib_Messaging_SnmpMessageExtension_Pdu">Pdu</a></td><td> (Defined by <a href="T_Lextm_SharpSnmpLib_Messaging_SnmpMessageExtension">SnmpMessageExtension</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_Lextm_SharpSnmpLib_Messaging_SnmpMessageExtension_RequestId">RequestId</a></td><td> (Defined by <a href="T_Lextm_SharpSnmpLib_Messaging_SnmpMessageExtension">SnmpMessageExtension</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_Lextm_SharpSnmpLib_Messaging_SnmpMessageExtension_Send">Send(EndPoint)</a></td><td>Overloaded.   (Defined by <a href="T_Lextm_SharpSnmpLib_Messaging_SnmpMessageExtension">SnmpMessageExtension</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_Lextm_SharpSnmpLib_Messaging_SnmpMessageExtension_Send_1">Send(EndPoint, Socket)</a></td><td>Overloaded.   (Defined by <a href="T_Lextm_SharpSnmpLib_Messaging_SnmpMessageExtension">SnmpMessageExtension</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_Lextm_SharpSnmpLib_Messaging_SnmpMessageExtension_SendAsync">SendAsync(EndPoint)</a></td><td>Overloaded.   (Defined by <a href="T_Lextm_SharpSnmpLib_Messaging_SnmpMessageExtension">SnmpMessageExtension</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_Lextm_SharpSnmpLib_Messaging_SnmpMessageExtension_SendAsync_1">SendAsync(EndPoint, Socket)</a></td><td>Overloaded.   (Defined by <a href="T_Lextm_SharpSnmpLib_Messaging_SnmpMessageExtension">SnmpMessageExtension</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_Lextm_SharpSnmpLib_Messaging_SnmpMessageExtension_TypeCode">TypeCode</a></td><td> (Defined by <a href="T_Lextm_SharpSnmpLib_Messaging_SnmpMessageExtension">SnmpMessageExtension</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_Lextm_SharpSnmpLib_Messaging_SnmpMessageExtension_Variables">Variables</a></td><td> (Defined by <a href="T_Lextm_SharpSnmpLib_Messaging_SnmpMessageExtension">SnmpMessageExtension</a>.)</td></tr></table>&nbsp;
<a href="#malformedmessage-class">Back to Top</a>

## See Also


#### Reference
<a href="N_Lextm_SharpSnmpLib_Messaging">Lextm.SharpSnmpLib.Messaging Namespace</a><br />