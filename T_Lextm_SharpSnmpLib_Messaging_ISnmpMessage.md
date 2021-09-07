# ISnmpMessage Interface
 

**Namespace:**&nbsp;<a href="N_Lextm_SharpSnmpLib_Messaging">Lextm.SharpSnmpLib.Messaging</a><br />**Assembly:**&nbsp;SharpSnmpLib (in SharpSnmpLib.dll) Version: 12.4.0+601762d0e653a71ebb69af963204dfbfb6c26b74

## Syntax

**C#**<br />
``` C#
public interface ISnmpMessage
```

**VB**<br />
``` VB
Public Interface ISnmpMessage
```

**C++**<br />
``` C++
public interface class ISnmpMessage
```

**F#**<br />
``` F#
type ISnmpMessage =  interface end
```

The ISnmpMessage type exposes the following members.


## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Lextm_SharpSnmpLib_Messaging_ISnmpMessage_Header">Header</a></td><td /></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Lextm_SharpSnmpLib_Messaging_ISnmpMessage_Parameters">Parameters</a></td><td /></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Lextm_SharpSnmpLib_Messaging_ISnmpMessage_Privacy">Privacy</a></td><td /></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Lextm_SharpSnmpLib_Messaging_ISnmpMessage_Scope">Scope</a></td><td /></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Lextm_SharpSnmpLib_Messaging_ISnmpMessage_Version">Version</a></td><td /></tr></table>&nbsp;
<a href="#isnmpmessage-interface">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Lextm_SharpSnmpLib_Messaging_ISnmpMessage_ToBytes">ToBytes</a></td><td /></tr></table>&nbsp;
<a href="#isnmpmessage-interface">Back to Top</a>

## Extension Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_Lextm_SharpSnmpLib_Messaging_SnmpMessageExtension_Community">Community</a></td><td> (Defined by <a href="T_Lextm_SharpSnmpLib_Messaging_SnmpMessageExtension">SnmpMessageExtension</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_Lextm_SharpSnmpLib_Messaging_SnmpMessageExtension_GetResponse">GetResponse(Int32, IPEndPoint)</a></td><td>Overloaded.   (Defined by <a href="T_Lextm_SharpSnmpLib_Messaging_SnmpMessageExtension">SnmpMessageExtension</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_Lextm_SharpSnmpLib_Messaging_SnmpMessageExtension_GetResponse_1">GetResponse(Int32, IPEndPoint, UserRegistry)</a></td><td>Overloaded.   (Defined by <a href="T_Lextm_SharpSnmpLib_Messaging_SnmpMessageExtension">SnmpMessageExtension</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_Lextm_SharpSnmpLib_Messaging_SnmpMessageExtension_GetResponse_3">GetResponse(Int32, IPEndPoint, Socket)</a></td><td>Overloaded.   (Defined by <a href="T_Lextm_SharpSnmpLib_Messaging_SnmpMessageExtension">SnmpMessageExtension</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_Lextm_SharpSnmpLib_Messaging_SnmpMessageExtension_GetResponse_2">GetResponse(Int32, IPEndPoint, UserRegistry, Socket)</a></td><td>Overloaded.   (Defined by <a href="T_Lextm_SharpSnmpLib_Messaging_SnmpMessageExtension">SnmpMessageExtension</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_Lextm_SharpSnmpLib_Messaging_SnmpMessageExtension_GetResponseAsync">GetResponseAsync(IPEndPoint)</a></td><td>Overloaded.   (Defined by <a href="T_Lextm_SharpSnmpLib_Messaging_SnmpMessageExtension">SnmpMessageExtension</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_Lextm_SharpSnmpLib_Messaging_SnmpMessageExtension_GetResponseAsync_1">GetResponseAsync(IPEndPoint, UserRegistry)</a></td><td>Overloaded.   (Defined by <a href="T_Lextm_SharpSnmpLib_Messaging_SnmpMessageExtension">SnmpMessageExtension</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_Lextm_SharpSnmpLib_Messaging_SnmpMessageExtension_GetResponseAsync_3">GetResponseAsync(IPEndPoint, Socket)</a></td><td>Overloaded.   (Defined by <a href="T_Lextm_SharpSnmpLib_Messaging_SnmpMessageExtension">SnmpMessageExtension</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_Lextm_SharpSnmpLib_Messaging_SnmpMessageExtension_GetResponseAsync_2">GetResponseAsync(IPEndPoint, UserRegistry, Socket)</a></td><td>Overloaded.   (Defined by <a href="T_Lextm_SharpSnmpLib_Messaging_SnmpMessageExtension">SnmpMessageExtension</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_Lextm_SharpSnmpLib_Messaging_SnmpMessageExtension_MessageId">MessageId</a></td><td> (Defined by <a href="T_Lextm_SharpSnmpLib_Messaging_SnmpMessageExtension">SnmpMessageExtension</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_Lextm_SharpSnmpLib_Messaging_SnmpMessageExtension_Pdu">Pdu</a></td><td> (Defined by <a href="T_Lextm_SharpSnmpLib_Messaging_SnmpMessageExtension">SnmpMessageExtension</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_Lextm_SharpSnmpLib_Messaging_SnmpMessageExtension_RequestId">RequestId</a></td><td> (Defined by <a href="T_Lextm_SharpSnmpLib_Messaging_SnmpMessageExtension">SnmpMessageExtension</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_Lextm_SharpSnmpLib_Messaging_SnmpMessageExtension_Send">Send(EndPoint)</a></td><td>Overloaded.   (Defined by <a href="T_Lextm_SharpSnmpLib_Messaging_SnmpMessageExtension">SnmpMessageExtension</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_Lextm_SharpSnmpLib_Messaging_SnmpMessageExtension_Send_1">Send(EndPoint, Socket)</a></td><td>Overloaded.   (Defined by <a href="T_Lextm_SharpSnmpLib_Messaging_SnmpMessageExtension">SnmpMessageExtension</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_Lextm_SharpSnmpLib_Messaging_SnmpMessageExtension_SendAsync">SendAsync(EndPoint)</a></td><td>Overloaded.   (Defined by <a href="T_Lextm_SharpSnmpLib_Messaging_SnmpMessageExtension">SnmpMessageExtension</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_Lextm_SharpSnmpLib_Messaging_SnmpMessageExtension_SendAsync_1">SendAsync(EndPoint, Socket)</a></td><td>Overloaded.   (Defined by <a href="T_Lextm_SharpSnmpLib_Messaging_SnmpMessageExtension">SnmpMessageExtension</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_Lextm_SharpSnmpLib_Messaging_SnmpMessageExtension_TypeCode">TypeCode</a></td><td> (Defined by <a href="T_Lextm_SharpSnmpLib_Messaging_SnmpMessageExtension">SnmpMessageExtension</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_Lextm_SharpSnmpLib_Messaging_SnmpMessageExtension_Variables">Variables</a></td><td> (Defined by <a href="T_Lextm_SharpSnmpLib_Messaging_SnmpMessageExtension">SnmpMessageExtension</a>.)</td></tr></table>&nbsp;
<a href="#isnmpmessage-interface">Back to Top</a>

## See Also


#### Reference
<a href="N_Lextm_SharpSnmpLib_Messaging">Lextm.SharpSnmpLib.Messaging Namespace</a><br />