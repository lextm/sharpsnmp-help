# NotResolvedException Class
 

Exception raised when type resolution fails.


## Inheritance Hierarchy
<a href="https://docs.microsoft.com/dotnet/api/system.object" target="_blank" rel="noopener noreferrer">System.Object</a><br />&nbsp;&nbsp;<a href="https://docs.microsoft.com/dotnet/api/system.exception" target="_blank" rel="noopener noreferrer">System.Exception</a><br />&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_Lextm_SharpSnmpLib_SnmpException">Lextm.SharpSnmpLib.SnmpException</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Lextm.SharpSnmpPro.Mib.NotResolvedException<br />
**Namespace:**&nbsp;<a href="N_Lextm_SharpSnmpPro_Mib">Lextm.SharpSnmpPro.Mib</a><br />**Assembly:**&nbsp;SharpSnmpPro.Mib (in SharpSnmpPro.Mib.dll) Version: 2.1.2

## Syntax

**C#**<br />
``` C#
public class NotResolvedException : SnmpException
```

**VB**<br />
``` VB
Public Class NotResolvedException
	Inherits SnmpException
```

**C++**<br />
``` C++
public ref class NotResolvedException : public SnmpException
```

**F#**<br />
``` F#
type NotResolvedException =  
    class
        inherit SnmpException
    end
```

The NotResolvedException type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Lextm_SharpSnmpPro_Mib_NotResolvedException__ctor">NotResolvedException()</a></td><td>
Initializes a new instance of the NotResolvedException class</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Lextm_SharpSnmpPro_Mib_NotResolvedException__ctor_1">NotResolvedException(String)</a></td><td>
Initializes a new instance of the NotResolvedException class</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Lextm_SharpSnmpPro_Mib_NotResolvedException__ctor_2">NotResolvedException(String, Exception)</a></td><td>
Initializes a new instance of the NotResolvedException class</td></tr></table>&nbsp;
<a href="#notresolvedexception-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Lextm_SharpSnmpPro_Mib_NotResolvedException_BrokenType">BrokenType</a></td><td /></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="https://docs.microsoft.com/dotnet/api/system.exception.data#System_Exception_Data" target="_blank" rel="noopener noreferrer">Data</a></td><td>
Gets a collection of key/value pairs that provide additional user-defined information about the exception.
 (Inherited from <a href="https://docs.microsoft.com/dotnet/api/system.exception" target="_blank" rel="noopener noreferrer">Exception</a>.)</td></tr><tr><td>![Protected property](media/protproperty.gif "Protected property")</td><td><a href="P_Lextm_SharpSnmpLib_SnmpException_Details">Details</a></td><td> (Inherited from <a href="T_Lextm_SharpSnmpLib_SnmpException">SnmpException</a>.)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Lextm_SharpSnmpPro_Mib_NotResolvedException_FullMessage">FullMessage</a></td><td /></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="https://docs.microsoft.com/dotnet/api/system.exception.helplink#System_Exception_HelpLink" target="_blank" rel="noopener noreferrer">HelpLink</a></td><td>
Gets or sets a link to the help file associated with this exception.
 (Inherited from <a href="https://docs.microsoft.com/dotnet/api/system.exception" target="_blank" rel="noopener noreferrer">Exception</a>.)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="https://docs.microsoft.com/dotnet/api/system.exception.hresult#System_Exception_HResult" target="_blank" rel="noopener noreferrer">HResult</a></td><td>
Gets or sets HRESULT, a coded numerical value that is assigned to a specific exception.
 (Inherited from <a href="https://docs.microsoft.com/dotnet/api/system.exception" target="_blank" rel="noopener noreferrer">Exception</a>.)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="https://docs.microsoft.com/dotnet/api/system.exception.innerexception#System_Exception_InnerException" target="_blank" rel="noopener noreferrer">InnerException</a></td><td>
Gets the <a href="https://docs.microsoft.com/dotnet/api/system.exception" target="_blank" rel="noopener noreferrer">Exception</a> instance that caused the current exception.
 (Inherited from <a href="https://docs.microsoft.com/dotnet/api/system.exception" target="_blank" rel="noopener noreferrer">Exception</a>.)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="https://docs.microsoft.com/dotnet/api/system.exception.message#System_Exception_Message" target="_blank" rel="noopener noreferrer">Message</a></td><td>
Gets a message that describes the current exception.
 (Inherited from <a href="https://docs.microsoft.com/dotnet/api/system.exception" target="_blank" rel="noopener noreferrer">Exception</a>.)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="https://docs.microsoft.com/dotnet/api/system.exception.source#System_Exception_Source" target="_blank" rel="noopener noreferrer">Source</a></td><td>
Gets or sets the name of the application or the object that causes the error.
 (Inherited from <a href="https://docs.microsoft.com/dotnet/api/system.exception" target="_blank" rel="noopener noreferrer">Exception</a>.)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="https://docs.microsoft.com/dotnet/api/system.exception.stacktrace#System_Exception_StackTrace" target="_blank" rel="noopener noreferrer">StackTrace</a></td><td>
Gets a string representation of the immediate frames on the call stack.
 (Inherited from <a href="https://docs.microsoft.com/dotnet/api/system.exception" target="_blank" rel="noopener noreferrer">Exception</a>.)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="https://docs.microsoft.com/dotnet/api/system.exception.targetsite#System_Exception_TargetSite" target="_blank" rel="noopener noreferrer">TargetSite</a></td><td>
Gets the method that throws the current exception.
 (Inherited from <a href="https://docs.microsoft.com/dotnet/api/system.exception" target="_blank" rel="noopener noreferrer">Exception</a>.)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Lextm_SharpSnmpPro_Mib_NotResolvedException_Type">Type</a></td><td /></tr></table>&nbsp;
<a href="#notresolvedexception-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="https://docs.microsoft.com/dotnet/api/system.object.equals#System_Object_Equals_System_Object_" target="_blank" rel="noopener noreferrer">Equals</a></td><td>
Determines whether the specified object is equal to the current object.
 (Inherited from <a href="https://docs.microsoft.com/dotnet/api/system.object" target="_blank" rel="noopener noreferrer">Object</a>.)</td></tr><tr><td>![Protected method](media/protmethod.gif "Protected method")</td><td><a href="https://docs.microsoft.com/dotnet/api/system.object.finalize#System_Object_Finalize" target="_blank" rel="noopener noreferrer">Finalize</a></td><td>
Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.
 (Inherited from <a href="https://docs.microsoft.com/dotnet/api/system.object" target="_blank" rel="noopener noreferrer">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="https://docs.microsoft.com/dotnet/api/system.exception.getbaseexception#System_Exception_GetBaseException" target="_blank" rel="noopener noreferrer">GetBaseException</a></td><td>
When overridden in a derived class, returns the <a href="https://docs.microsoft.com/dotnet/api/system.exception" target="_blank" rel="noopener noreferrer">Exception</a> that is the root cause of one or more subsequent exceptions.
 (Inherited from <a href="https://docs.microsoft.com/dotnet/api/system.exception" target="_blank" rel="noopener noreferrer">Exception</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="https://docs.microsoft.com/dotnet/api/system.object.gethashcode#System_Object_GetHashCode" target="_blank" rel="noopener noreferrer">GetHashCode</a></td><td>
Serves as the default hash function.
 (Inherited from <a href="https://docs.microsoft.com/dotnet/api/system.object" target="_blank" rel="noopener noreferrer">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="https://docs.microsoft.com/dotnet/api/system.exception.getobjectdata#System_Exception_GetObjectData_System_Runtime_Serialization_SerializationInfo_System_Runtime_Serialization_StreamingContext_" target="_blank" rel="noopener noreferrer">GetObjectData</a></td><td>
When overridden in a derived class, sets the <a href="https://docs.microsoft.com/dotnet/api/system.runtime.serialization.serializationinfo" target="_blank" rel="noopener noreferrer">SerializationInfo</a> with information about the exception.
 (Inherited from <a href="https://docs.microsoft.com/dotnet/api/system.exception" target="_blank" rel="noopener noreferrer">Exception</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="https://docs.microsoft.com/dotnet/api/system.exception.gettype#System_Exception_GetType" target="_blank" rel="noopener noreferrer">GetType</a></td><td>
Gets the runtime type of the current instance.
 (Inherited from <a href="https://docs.microsoft.com/dotnet/api/system.exception" target="_blank" rel="noopener noreferrer">Exception</a>.)</td></tr><tr><td>![Protected method](media/protmethod.gif "Protected method")</td><td><a href="https://docs.microsoft.com/dotnet/api/system.object.memberwiseclone#System_Object_MemberwiseClone" target="_blank" rel="noopener noreferrer">MemberwiseClone</a></td><td>
Creates a shallow copy of the current <a href="https://docs.microsoft.com/dotnet/api/system.object" target="_blank" rel="noopener noreferrer">Object</a>.
 (Inherited from <a href="https://docs.microsoft.com/dotnet/api/system.object" target="_blank" rel="noopener noreferrer">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Lextm_SharpSnmpLib_SnmpException_ToString">ToString</a></td><td> (Inherited from <a href="T_Lextm_SharpSnmpLib_SnmpException">SnmpException</a>.)</td></tr></table>&nbsp;
<a href="#notresolvedexception-class">Back to Top</a>

## Events
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Protected event](media/protevent.gif "Protected event")</td><td><a href="https://docs.microsoft.com/dotnet/api/system.exception.serializeobjectstate" target="_blank" rel="noopener noreferrer">SerializeObjectState</a></td><td>
Occurs when an exception is serialized to create an exception state object that contains serialized data about the exception.
 (Inherited from <a href="https://docs.microsoft.com/dotnet/api/system.exception" target="_blank" rel="noopener noreferrer">Exception</a>.)</td></tr></table>&nbsp;
<a href="#notresolvedexception-class">Back to Top</a>

## Remarks
This exception is used to collect detailed error message when type resolution fails.

## See Also


#### Reference
<a href="N_Lextm_SharpSnmpPro_Mib">Lextm.SharpSnmpPro.Mib Namespace</a><br />