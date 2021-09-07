# ObjectIdentifier Class
 


## Inheritance Hierarchy
<a href="https://docs.microsoft.com/dotnet/api/system.object" target="_blank" rel="noopener noreferrer">System.Object</a><br />&nbsp;&nbsp;Lextm.SharpSnmpLib.ObjectIdentifier<br />
**Namespace:**&nbsp;<a href="N_Lextm_SharpSnmpLib">Lextm.SharpSnmpLib</a><br />**Assembly:**&nbsp;SharpSnmpLib (in SharpSnmpLib.dll) Version: 12.4.0+601762d0e653a71ebb69af963204dfbfb6c26b74

## Syntax

**C#**<br />
``` C#
[TypeConverterAttribute(typeof(ObjectIdentifierConverter))]
public sealed class ObjectIdentifier : ISnmpData, 
	IEquatable<ObjectIdentifier>, IComparable<ObjectIdentifier>, IComparable
```

**VB**<br />
``` VB
<TypeConverterAttribute(GetType(ObjectIdentifierConverter))>
Public NotInheritable Class ObjectIdentifier
	Implements ISnmpData, IEquatable(Of ObjectIdentifier), 
	IComparable(Of ObjectIdentifier), IComparable
```

**C++**<br />
``` C++
[TypeConverterAttribute(typeof(ObjectIdentifierConverter))]
public ref class ObjectIdentifier sealed : ISnmpData, 
	IEquatable<ObjectIdentifier^>, IComparable<ObjectIdentifier^>, IComparable
```

**F#**<br />
``` F#
[<SealedAttribute>]
[<TypeConverterAttribute(typeof(ObjectIdentifierConverter))>]
type ObjectIdentifier =  
    class
        interface ISnmpData
        interface IEquatable<ObjectIdentifier>
        interface IComparable<ObjectIdentifier>
        interface IComparable
    end
```

The ObjectIdentifier type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Lextm_SharpSnmpLib_ObjectIdentifier__ctor">ObjectIdentifier(String)</a></td><td>
Initializes a new instance of the ObjectIdentifier class</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Lextm_SharpSnmpLib_ObjectIdentifier__ctor_2">ObjectIdentifier(UInt32[])</a></td><td>
Initializes a new instance of the ObjectIdentifier class</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Lextm_SharpSnmpLib_ObjectIdentifier__ctor_1">ObjectIdentifier(Tuple(Int32, Byte[]), Stream)</a></td><td>
Initializes a new instance of the ObjectIdentifier class</td></tr></table>&nbsp;
<a href="#objectidentifier-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Lextm_SharpSnmpLib_ObjectIdentifier_TypeCode">TypeCode</a></td><td /></tr></table>&nbsp;
<a href="#objectidentifier-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Lextm_SharpSnmpLib_ObjectIdentifier_AppendBytesTo">AppendBytesTo</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_Lextm_SharpSnmpLib_ObjectIdentifier_AppendTo">AppendTo</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Lextm_SharpSnmpLib_ObjectIdentifier_Compare">Compare</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Lextm_SharpSnmpLib_ObjectIdentifier_CompareTo_1">CompareTo(Object)</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Lextm_SharpSnmpLib_ObjectIdentifier_CompareTo">CompareTo(ObjectIdentifier)</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_Lextm_SharpSnmpLib_ObjectIdentifier_Convert">Convert(String)</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_Lextm_SharpSnmpLib_ObjectIdentifier_Convert_1">Convert(UInt32[])</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_Lextm_SharpSnmpLib_ObjectIdentifier_Create">Create</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Lextm_SharpSnmpLib_ObjectIdentifier_Equals_1">Equals(Object)</a></td><td> (Overrides <a href="https://docs.microsoft.com/dotnet/api/system.object.equals#System_Object_Equals_System_Object_" target="_blank" rel="noopener noreferrer">Object.Equals(Object)</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Lextm_SharpSnmpLib_ObjectIdentifier_Equals">Equals(ObjectIdentifier)</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Lextm_SharpSnmpLib_ObjectIdentifier_GetHashCode">GetHashCode</a></td><td> (Overrides <a href="https://docs.microsoft.com/dotnet/api/system.object.gethashcode#System_Object_GetHashCode" target="_blank" rel="noopener noreferrer">Object.GetHashCode()</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="https://docs.microsoft.com/dotnet/api/system.object.gettype#System_Object_GetType" target="_blank" rel="noopener noreferrer">GetType</a></td><td>
Gets the <a href="https://docs.microsoft.com/dotnet/api/system.type" target="_blank" rel="noopener noreferrer">Type</a> of the current instance.
 (Inherited from <a href="https://docs.microsoft.com/dotnet/api/system.object" target="_blank" rel="noopener noreferrer">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Lextm_SharpSnmpLib_ObjectIdentifier_ToNumerical">ToNumerical</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Lextm_SharpSnmpLib_ObjectIdentifier_ToString">ToString</a></td><td> (Overrides <a href="https://docs.microsoft.com/dotnet/api/system.object.tostring#System_Object_ToString" target="_blank" rel="noopener noreferrer">Object.ToString()</a>.)</td></tr></table>&nbsp;
<a href="#objectidentifier-class">Back to Top</a>

## Operators
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_Lextm_SharpSnmpLib_ObjectIdentifier_op_Equality">Equality</a></td><td /></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_Lextm_SharpSnmpLib_ObjectIdentifier_op_GreaterThan">GreaterThan</a></td><td /></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_Lextm_SharpSnmpLib_ObjectIdentifier_op_Inequality">Inequality</a></td><td /></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_Lextm_SharpSnmpLib_ObjectIdentifier_op_LessThan">LessThan</a></td><td /></tr></table>&nbsp;
<a href="#objectidentifier-class">Back to Top</a>

## Extension Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_Lextm_SharpSnmpLib_Messaging_Messenger_GetErrorMessage">GetErrorMessage</a></td><td> (Defined by <a href="T_Lextm_SharpSnmpLib_Messaging_Messenger">Messenger</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_Lextm_SharpSnmpLib_SnmpDataExtension_ToBytes">ToBytes</a></td><td> (Defined by <a href="T_Lextm_SharpSnmpLib_SnmpDataExtension">SnmpDataExtension</a>.)</td></tr></table>&nbsp;
<a href="#objectidentifier-class">Back to Top</a>

## See Also


#### Reference
<a href="N_Lextm_SharpSnmpLib">Lextm.SharpSnmpLib Namespace</a><br />