# InformRequestPdu Class
 


## Inheritance Hierarchy
<a href="https://docs.microsoft.com/dotnet/api/system.object" target="_blank" rel="noopener noreferrer">System.Object</a><br />&nbsp;&nbsp;Lextm.SharpSnmpLib.InformRequestPdu<br />
**Namespace:**&nbsp;<a href="N_Lextm_SharpSnmpLib">Lextm.SharpSnmpLib</a><br />**Assembly:**&nbsp;SharpSnmpLib (in SharpSnmpLib.dll) Version: 12.4.0+601762d0e653a71ebb69af963204dfbfb6c26b74

## Syntax

**C#**<br />
``` C#
public sealed class InformRequestPdu : ISnmpPdu, 
	ISnmpData
```

**VB**<br />
``` VB
Public NotInheritable Class InformRequestPdu
	Implements ISnmpPdu, ISnmpData
```

**C++**<br />
``` C++
public ref class InformRequestPdu sealed : ISnmpPdu, 
	ISnmpData
```

**F#**<br />
``` F#
[<SealedAttribute>]
type InformRequestPdu =  
    class
        interface ISnmpPdu
        interface ISnmpData
    end
```

The InformRequestPdu type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Lextm_SharpSnmpLib_InformRequestPdu__ctor">InformRequestPdu(Int32)</a></td><td>
Initializes a new instance of the InformRequestPdu class</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Lextm_SharpSnmpLib_InformRequestPdu__ctor_2">InformRequestPdu(Tuple(Int32, Byte[]), Stream)</a></td><td>
Initializes a new instance of the InformRequestPdu class</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Lextm_SharpSnmpLib_InformRequestPdu__ctor_1">InformRequestPdu(Int32, ObjectIdentifier, UInt32, IList(Variable))</a></td><td>
Initializes a new instance of the InformRequestPdu class</td></tr></table>&nbsp;
<a href="#informrequestpdu-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Lextm_SharpSnmpLib_InformRequestPdu_Enterprise">Enterprise</a></td><td /></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Lextm_SharpSnmpLib_InformRequestPdu_ErrorIndex">ErrorIndex</a></td><td /></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Lextm_SharpSnmpLib_InformRequestPdu_ErrorStatus">ErrorStatus</a></td><td /></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Lextm_SharpSnmpLib_InformRequestPdu_RequestId">RequestId</a></td><td /></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Lextm_SharpSnmpLib_InformRequestPdu_TimeStamp">TimeStamp</a></td><td /></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Lextm_SharpSnmpLib_InformRequestPdu_TypeCode">TypeCode</a></td><td /></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Lextm_SharpSnmpLib_InformRequestPdu_Variables">Variables</a></td><td /></tr></table>&nbsp;
<a href="#informrequestpdu-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Lextm_SharpSnmpLib_InformRequestPdu_AppendBytesTo">AppendBytesTo</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Lextm_SharpSnmpLib_InformRequestPdu_Decorate">Decorate</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="https://docs.microsoft.com/dotnet/api/system.object.equals#System_Object_Equals_System_Object_" target="_blank" rel="noopener noreferrer">Equals</a></td><td>
Determines whether the specified object is equal to the current object.
 (Inherited from <a href="https://docs.microsoft.com/dotnet/api/system.object" target="_blank" rel="noopener noreferrer">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="https://docs.microsoft.com/dotnet/api/system.object.gethashcode#System_Object_GetHashCode" target="_blank" rel="noopener noreferrer">GetHashCode</a></td><td>
Serves as the default hash function.
 (Inherited from <a href="https://docs.microsoft.com/dotnet/api/system.object" target="_blank" rel="noopener noreferrer">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="https://docs.microsoft.com/dotnet/api/system.object.gettype#System_Object_GetType" target="_blank" rel="noopener noreferrer">GetType</a></td><td>
Gets the <a href="https://docs.microsoft.com/dotnet/api/system.type" target="_blank" rel="noopener noreferrer">Type</a> of the current instance.
 (Inherited from <a href="https://docs.microsoft.com/dotnet/api/system.object" target="_blank" rel="noopener noreferrer">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Lextm_SharpSnmpLib_InformRequestPdu_ToString">ToString</a></td><td> (Overrides <a href="https://docs.microsoft.com/dotnet/api/system.object.tostring#System_Object_ToString" target="_blank" rel="noopener noreferrer">Object.ToString()</a>.)</td></tr></table>&nbsp;
<a href="#informrequestpdu-class">Back to Top</a>

## Extension Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_Lextm_SharpSnmpLib_SnmpDataExtension_ToBytes">ToBytes</a></td><td> (Defined by <a href="T_Lextm_SharpSnmpLib_SnmpDataExtension">SnmpDataExtension</a>.)</td></tr></table>&nbsp;
<a href="#informrequestpdu-class">Back to Top</a>

## See Also


#### Reference
<a href="N_Lextm_SharpSnmpLib">Lextm.SharpSnmpLib Namespace</a><br />