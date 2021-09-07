# SnmpException Class
 


## Inheritance Hierarchy
<a href="https://docs.microsoft.com/dotnet/api/system.object" target="_blank" rel="noopener noreferrer">System.Object</a><br />&nbsp;&nbsp;<a href="https://docs.microsoft.com/dotnet/api/system.exception" target="_blank" rel="noopener noreferrer">System.Exception</a><br />&nbsp;&nbsp;&nbsp;&nbsp;Lextm.SharpSnmpLib.SnmpException<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_Lextm_SharpSnmpLib_Messaging_MessageFactoryException">Lextm.SharpSnmpLib.Messaging.MessageFactoryException</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_Lextm_SharpSnmpLib_Messaging_PortInUseException">Lextm.SharpSnmpLib.Messaging.PortInUseException</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_Lextm_SharpSnmpLib_OperationException">Lextm.SharpSnmpLib.OperationException</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_Lextm_SharpSnmpLib_Security_DecryptionException">Lextm.SharpSnmpLib.Security.DecryptionException</a><br />
**Namespace:**&nbsp;<a href="N_Lextm_SharpSnmpLib">Lextm.SharpSnmpLib</a><br />**Assembly:**&nbsp;SharpSnmpLib (in SharpSnmpLib.dll) Version: 12.4.0+601762d0e653a71ebb69af963204dfbfb6c26b74

## Syntax

**C#**<br />
``` C#
public class SnmpException : Exception
```

**VB**<br />
``` VB
Public Class SnmpException
	Inherits Exception
```

**C++**<br />
``` C++
public ref class SnmpException : public Exception
```

**F#**<br />
``` F#
type SnmpException =  
    class
        inherit Exception
    end
```

The SnmpException type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Lextm_SharpSnmpLib_SnmpException__ctor">SnmpException()</a></td><td>
Initializes a new instance of the SnmpException class</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Lextm_SharpSnmpLib_SnmpException__ctor_2">SnmpException(String)</a></td><td>
Initializes a new instance of the SnmpException class</td></tr><tr><td>![Protected method](media/protmethod.gif "Protected method")</td><td><a href="M_Lextm_SharpSnmpLib_SnmpException__ctor_1">SnmpException(SerializationInfo, StreamingContext)</a></td><td>
Initializes a new instance of the SnmpException class</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Lextm_SharpSnmpLib_SnmpException__ctor_3">SnmpException(String, Exception)</a></td><td>
Initializes a new instance of the SnmpException class</td></tr></table>&nbsp;
<a href="#snmpexception-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="https://docs.microsoft.com/dotnet/api/system.exception.data#System_Exception_Data" target="_blank" rel="noopener noreferrer">Data</a></td><td>
Gets a collection of key/value pairs that provide additional user-defined information about the exception.
 (Inherited from <a href="https://docs.microsoft.com/dotnet/api/system.exception" target="_blank" rel="noopener noreferrer">Exception</a>.)</td></tr><tr><td>![Protected property](media/protproperty.gif "Protected property")</td><td><a href="P_Lextm_SharpSnmpLib_SnmpException_Details">Details</a></td><td /></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="https://docs.microsoft.com/dotnet/api/system.exception.helplink#System_Exception_HelpLink" target="_blank" rel="noopener noreferrer">HelpLink</a></td><td>
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
 (Inherited from <a href="https://docs.microsoft.com/dotnet/api/system.exception" target="_blank" rel="noopener noreferrer">Exception</a>.)</td></tr></table>&nbsp;
<a href="#snmpexception-class">Back to Top</a>

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
 (Inherited from <a href="https://docs.microsoft.com/dotnet/api/system.object" target="_blank" rel="noopener noreferrer">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Lextm_SharpSnmpLib_SnmpException_ToString">ToString</a></td><td> (Overrides <a href="https://docs.microsoft.com/dotnet/api/system.exception.tostring#System_Exception_ToString" target="_blank" rel="noopener noreferrer">Exception.ToString()</a>.)</td></tr></table>&nbsp;
<a href="#snmpexception-class">Back to Top</a>

## Events
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Protected event](media/protevent.gif "Protected event")</td><td><a href="https://docs.microsoft.com/dotnet/api/system.exception.serializeobjectstate" target="_blank" rel="noopener noreferrer">SerializeObjectState</a></td><td>
Occurs when an exception is serialized to create an exception state object that contains serialized data about the exception.
 (Inherited from <a href="https://docs.microsoft.com/dotnet/api/system.exception" target="_blank" rel="noopener noreferrer">Exception</a>.)</td></tr></table>&nbsp;
<a href="#snmpexception-class">Back to Top</a>

## See Also


#### Reference
<a href="N_Lextm_SharpSnmpLib">Lextm.SharpSnmpLib Namespace</a><br />