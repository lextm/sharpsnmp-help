# Manager Class
 

**Note: This API is now obsolete.**


## Inheritance Hierarchy
<a href="https://docs.microsoft.com/dotnet/api/system.object" target="_blank" rel="noopener noreferrer">System.Object</a><br />&nbsp;&nbsp;Lextm.SharpSnmpLib.Messaging.Manager<br />
**Namespace:**&nbsp;<a href="N_Lextm_SharpSnmpLib_Messaging">Lextm.SharpSnmpLib.Messaging</a><br />**Assembly:**&nbsp;SharpSnmpLib (in SharpSnmpLib.dll) Version: 12.4.0+601762d0e653a71ebb69af963204dfbfb6c26b74

## Syntax

**C#**<br />
``` C#
[ObsoleteAttribute("Please use Messenger class instead.")]
public sealed class Manager
```

**VB**<br />
``` VB
<ObsoleteAttribute("Please use Messenger class instead.")>
Public NotInheritable Class Manager
```

**C++**<br />
``` C++
[ObsoleteAttribute(L"Please use Messenger class instead.")]
public ref class Manager sealed
```

**F#**<br />
``` F#
[<SealedAttribute>]
[<ObsoleteAttribute("Please use Messenger class instead.")>]
type Manager =  class end
```

The Manager type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Lextm_SharpSnmpLib_Messaging_Manager__ctor">Manager</a></td><td>
Initializes a new instance of the Manager class</td></tr></table>&nbsp;
<a href="#manager-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Lextm_SharpSnmpLib_Messaging_Manager_DefaultVersion">DefaultVersion</a></td><td /></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Lextm_SharpSnmpLib_Messaging_Manager_MaxRepetitions">MaxRepetitions</a></td><td /></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Lextm_SharpSnmpLib_Messaging_Manager_Timeout">Timeout</a></td><td /></tr></table>&nbsp;
<a href="#manager-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="https://docs.microsoft.com/dotnet/api/system.object.equals#System_Object_Equals_System_Object_" target="_blank" rel="noopener noreferrer">Equals</a></td><td>
Determines whether the specified object is equal to the current object.
 (Inherited from <a href="https://docs.microsoft.com/dotnet/api/system.object" target="_blank" rel="noopener noreferrer">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Lextm_SharpSnmpLib_Messaging_Manager_Get">Get(IPAddress, String, IList(Variable))</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Lextm_SharpSnmpLib_Messaging_Manager_Get_1">Get(IPEndPoint, String, IList(Variable))</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Lextm_SharpSnmpLib_Messaging_Manager_Get_2">Get(String, String, IList(Variable))</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="https://docs.microsoft.com/dotnet/api/system.object.gethashcode#System_Object_GetHashCode" target="_blank" rel="noopener noreferrer">GetHashCode</a></td><td>
Serves as the default hash function.
 (Inherited from <a href="https://docs.microsoft.com/dotnet/api/system.object" target="_blank" rel="noopener noreferrer">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Lextm_SharpSnmpLib_Messaging_Manager_GetSingle">GetSingle(IPAddress, String, Variable)</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Lextm_SharpSnmpLib_Messaging_Manager_GetSingle_1">GetSingle(IPEndPoint, String, Variable)</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Lextm_SharpSnmpLib_Messaging_Manager_GetSingle_2">GetSingle(String, String, Variable)</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Lextm_SharpSnmpLib_Messaging_Manager_GetTable">GetTable(IPAddress, String, ObjectIdentifier)</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Lextm_SharpSnmpLib_Messaging_Manager_GetTable_1">GetTable(IPEndPoint, String, ObjectIdentifier)</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Lextm_SharpSnmpLib_Messaging_Manager_GetTable_2">GetTable(String, String, ObjectIdentifier)</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="https://docs.microsoft.com/dotnet/api/system.object.gettype#System_Object_GetType" target="_blank" rel="noopener noreferrer">GetType</a></td><td>
Gets the <a href="https://docs.microsoft.com/dotnet/api/system.type" target="_blank" rel="noopener noreferrer">Type</a> of the current instance.
 (Inherited from <a href="https://docs.microsoft.com/dotnet/api/system.object" target="_blank" rel="noopener noreferrer">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Lextm_SharpSnmpLib_Messaging_Manager_Set">Set(IPAddress, String, IList(Variable))</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Lextm_SharpSnmpLib_Messaging_Manager_Set_1">Set(IPEndPoint, String, IList(Variable))</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Lextm_SharpSnmpLib_Messaging_Manager_Set_2">Set(String, String, IList(Variable))</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Lextm_SharpSnmpLib_Messaging_Manager_SetSingle">SetSingle(IPAddress, String, Variable)</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Lextm_SharpSnmpLib_Messaging_Manager_SetSingle_1">SetSingle(IPEndPoint, String, Variable)</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Lextm_SharpSnmpLib_Messaging_Manager_SetSingle_2">SetSingle(String, String, Variable)</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Lextm_SharpSnmpLib_Messaging_Manager_ToString">ToString</a></td><td> (Overrides <a href="https://docs.microsoft.com/dotnet/api/system.object.tostring#System_Object_ToString" target="_blank" rel="noopener noreferrer">Object.ToString()</a>.)</td></tr></table>&nbsp;
<a href="#manager-class">Back to Top</a>

## See Also


#### Reference
<a href="N_Lextm_SharpSnmpLib_Messaging">Lextm.SharpSnmpLib.Messaging Namespace</a><br />