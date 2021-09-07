# IP Class
 


## Inheritance Hierarchy
<a href="https://docs.microsoft.com/dotnet/api/system.object" target="_blank" rel="noopener noreferrer">System.Object</a><br />&nbsp;&nbsp;Lextm.SharpSnmpLib.IP<br />
**Namespace:**&nbsp;<a href="N_Lextm_SharpSnmpLib">Lextm.SharpSnmpLib</a><br />**Assembly:**&nbsp;SharpSnmpLib (in SharpSnmpLib.dll) Version: 12.4.0+601762d0e653a71ebb69af963204dfbfb6c26b74

## Syntax

**C#**<br />
``` C#
public sealed class IP : ISnmpData, IEquatable<IP>
```

**VB**<br />
``` VB
Public NotInheritable Class IP
	Implements ISnmpData, IEquatable(Of IP)
```

**C++**<br />
``` C++
public ref class IP sealed : ISnmpData, 
	IEquatable<IP^>
```

**F#**<br />
``` F#
[<SealedAttribute>]
type IP =  
    class
        interface ISnmpData
        interface IEquatable<IP>
    end
```

The IP type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Lextm_SharpSnmpLib_IP__ctor">IP(Byte[])</a></td><td>
Initializes a new instance of the IP class</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Lextm_SharpSnmpLib_IP__ctor_1">IP(String)</a></td><td>
Initializes a new instance of the IP class</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Lextm_SharpSnmpLib_IP__ctor_2">IP(Tuple(Int32, Byte[]), Stream)</a></td><td>
Initializes a new instance of the IP class</td></tr></table>&nbsp;
<a href="#ip-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Lextm_SharpSnmpLib_IP_TypeCode">TypeCode</a></td><td /></tr></table>&nbsp;
<a href="#ip-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Lextm_SharpSnmpLib_IP_AppendBytesTo">AppendBytesTo</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Lextm_SharpSnmpLib_IP_Equals_1">Equals(Object)</a></td><td> (Overrides <a href="https://docs.microsoft.com/dotnet/api/system.object.equals#System_Object_Equals_System_Object_" target="_blank" rel="noopener noreferrer">Object.Equals(Object)</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Lextm_SharpSnmpLib_IP_Equals">Equals(IP)</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Lextm_SharpSnmpLib_IP_GetHashCode">GetHashCode</a></td><td> (Overrides <a href="https://docs.microsoft.com/dotnet/api/system.object.gethashcode#System_Object_GetHashCode" target="_blank" rel="noopener noreferrer">Object.GetHashCode()</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Lextm_SharpSnmpLib_IP_GetRaw">GetRaw</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="https://docs.microsoft.com/dotnet/api/system.object.gettype#System_Object_GetType" target="_blank" rel="noopener noreferrer">GetType</a></td><td>
Gets the <a href="https://docs.microsoft.com/dotnet/api/system.type" target="_blank" rel="noopener noreferrer">Type</a> of the current instance.
 (Inherited from <a href="https://docs.microsoft.com/dotnet/api/system.object" target="_blank" rel="noopener noreferrer">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Lextm_SharpSnmpLib_IP_ToString">ToString</a></td><td> (Overrides <a href="https://docs.microsoft.com/dotnet/api/system.object.tostring#System_Object_ToString" target="_blank" rel="noopener noreferrer">Object.ToString()</a>.)</td></tr></table>&nbsp;
<a href="#ip-class">Back to Top</a>

## Operators
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_Lextm_SharpSnmpLib_IP_op_Equality">Equality</a></td><td /></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_Lextm_SharpSnmpLib_IP_op_Inequality">Inequality</a></td><td /></tr></table>&nbsp;
<a href="#ip-class">Back to Top</a>

## Extension Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_Lextm_SharpSnmpLib_SnmpDataExtension_ToBytes">ToBytes</a></td><td> (Defined by <a href="T_Lextm_SharpSnmpLib_SnmpDataExtension">SnmpDataExtension</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_Lextm_SharpSnmpLib_Helper_ToIPAddress">ToIPAddress</a></td><td> (Defined by <a href="T_Lextm_SharpSnmpLib_Helper">Helper</a>.)</td></tr></table>&nbsp;
<a href="#ip-class">Back to Top</a>

## See Also


#### Reference
<a href="N_Lextm_SharpSnmpLib">Lextm.SharpSnmpLib Namespace</a><br />