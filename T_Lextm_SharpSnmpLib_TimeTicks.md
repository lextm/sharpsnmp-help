# TimeTicks Class
 


## Inheritance Hierarchy
<a href="https://docs.microsoft.com/dotnet/api/system.object" target="_blank" rel="noopener noreferrer">System.Object</a><br />&nbsp;&nbsp;Lextm.SharpSnmpLib.TimeTicks<br />
**Namespace:**&nbsp;<a href="N_Lextm_SharpSnmpLib">Lextm.SharpSnmpLib</a><br />**Assembly:**&nbsp;SharpSnmpLib (in SharpSnmpLib.dll) Version: 12.4.0+601762d0e653a71ebb69af963204dfbfb6c26b74

## Syntax

**C#**<br />
``` C#
public sealed class TimeTicks : ISnmpData, 
	IEquatable<TimeTicks>
```

**VB**<br />
``` VB
Public NotInheritable Class TimeTicks
	Implements ISnmpData, IEquatable(Of TimeTicks)
```

**C++**<br />
``` C++
public ref class TimeTicks sealed : ISnmpData, 
	IEquatable<TimeTicks^>
```

**F#**<br />
``` F#
[<SealedAttribute>]
type TimeTicks =  
    class
        interface ISnmpData
        interface IEquatable<TimeTicks>
    end
```

The TimeTicks type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Lextm_SharpSnmpLib_TimeTicks__ctor">TimeTicks(TimeSpan)</a></td><td>
Initializes a new instance of the TimeTicks class</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Lextm_SharpSnmpLib_TimeTicks__ctor_2">TimeTicks(UInt32)</a></td><td>
Initializes a new instance of the TimeTicks class</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Lextm_SharpSnmpLib_TimeTicks__ctor_1">TimeTicks(Tuple(Int32, Byte[]), Stream)</a></td><td>
Initializes a new instance of the TimeTicks class</td></tr></table>&nbsp;
<a href="#timeticks-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Lextm_SharpSnmpLib_TimeTicks_TypeCode">TypeCode</a></td><td /></tr></table>&nbsp;
<a href="#timeticks-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Lextm_SharpSnmpLib_TimeTicks_AppendBytesTo">AppendBytesTo</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Lextm_SharpSnmpLib_TimeTicks_Equals_1">Equals(Object)</a></td><td> (Overrides <a href="https://docs.microsoft.com/dotnet/api/system.object.equals#System_Object_Equals_System_Object_" target="_blank" rel="noopener noreferrer">Object.Equals(Object)</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Lextm_SharpSnmpLib_TimeTicks_Equals">Equals(TimeTicks)</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Lextm_SharpSnmpLib_TimeTicks_GetHashCode">GetHashCode</a></td><td> (Overrides <a href="https://docs.microsoft.com/dotnet/api/system.object.gethashcode#System_Object_GetHashCode" target="_blank" rel="noopener noreferrer">Object.GetHashCode()</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="https://docs.microsoft.com/dotnet/api/system.object.gettype#System_Object_GetType" target="_blank" rel="noopener noreferrer">GetType</a></td><td>
Gets the <a href="https://docs.microsoft.com/dotnet/api/system.type" target="_blank" rel="noopener noreferrer">Type</a> of the current instance.
 (Inherited from <a href="https://docs.microsoft.com/dotnet/api/system.object" target="_blank" rel="noopener noreferrer">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Lextm_SharpSnmpLib_TimeTicks_ToString">ToString</a></td><td> (Overrides <a href="https://docs.microsoft.com/dotnet/api/system.object.tostring#System_Object_ToString" target="_blank" rel="noopener noreferrer">Object.ToString()</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Lextm_SharpSnmpLib_TimeTicks_ToTimeSpan">ToTimeSpan</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Lextm_SharpSnmpLib_TimeTicks_ToUInt32">ToUInt32</a></td><td /></tr></table>&nbsp;
<a href="#timeticks-class">Back to Top</a>

## Operators
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_Lextm_SharpSnmpLib_TimeTicks_op_Equality">Equality</a></td><td /></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_Lextm_SharpSnmpLib_TimeTicks_op_Inequality">Inequality</a></td><td /></tr></table>&nbsp;
<a href="#timeticks-class">Back to Top</a>

## Extension Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_Lextm_SharpSnmpLib_SnmpDataExtension_ToBytes">ToBytes</a></td><td> (Defined by <a href="T_Lextm_SharpSnmpLib_SnmpDataExtension">SnmpDataExtension</a>.)</td></tr></table>&nbsp;
<a href="#timeticks-class">Back to Top</a>

## See Also


#### Reference
<a href="N_Lextm_SharpSnmpLib">Lextm.SharpSnmpLib Namespace</a><br />