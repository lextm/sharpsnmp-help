# ErrorRegistry Class
 

A registry that stores all errors and warnings.


## Inheritance Hierarchy
<a href="https://docs.microsoft.com/dotnet/api/system.object" target="_blank" rel="noopener noreferrer">System.Object</a><br />&nbsp;&nbsp;Lextm.SharpSnmpPro.Mib.Validation.ErrorRegistry<br />
**Namespace:**&nbsp;<a href="N_Lextm_SharpSnmpPro_Mib_Validation">Lextm.SharpSnmpPro.Mib.Validation</a><br />**Assembly:**&nbsp;SharpSnmpPro.Mib (in SharpSnmpPro.Mib.dll) Version: 2.1.2

## Syntax

**C#**<br />
``` C#
public class ErrorRegistry
```

**VB**<br />
``` VB
Public Class ErrorRegistry
```

**C++**<br />
``` C++
public ref class ErrorRegistry
```

**F#**<br />
``` F#
type ErrorRegistry =  class end
```

The ErrorRegistry type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Lextm_SharpSnmpPro_Mib_Validation_ErrorRegistry__ctor">ErrorRegistry</a></td><td>
Initializes a new instance of the ErrorRegistry class.</td></tr></table>&nbsp;
<a href="#errorregistry-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Lextm_SharpSnmpPro_Mib_Validation_ErrorRegistry_Errors">Errors</a></td><td>
Errors.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Lextm_SharpSnmpPro_Mib_Validation_ErrorRegistry_Messages">Messages</a></td><td>
Messages.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Lextm_SharpSnmpPro_Mib_Validation_ErrorRegistry_Warnings">Warnings</a></td><td>
Warnings.</td></tr></table>&nbsp;
<a href="#errorregistry-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Lextm_SharpSnmpPro_Mib_Validation_ErrorRegistry_AddError">AddError(RecognitionException, String)</a></td><td>
Adds an error.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Lextm_SharpSnmpPro_Mib_Validation_ErrorRegistry_AddError_2">AddError(ErrorCategory, String, IConstruct[])</a></td><td>
Adds an error.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Lextm_SharpSnmpPro_Mib_Validation_ErrorRegistry_AddError_1">AddError(ErrorCategory, String, IToken, String)</a></td><td>
Adds an error.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Lextm_SharpSnmpPro_Mib_Validation_ErrorRegistry_AddMessage_1">AddMessage(MessageCategory, String, IConstruct[])</a></td><td>
Adds a message.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Lextm_SharpSnmpPro_Mib_Validation_ErrorRegistry_AddMessage">AddMessage(MessageCategory, String, IToken, String)</a></td><td>
Adds a message.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Lextm_SharpSnmpPro_Mib_Validation_ErrorRegistry_AddWarning_1">AddWarning(WarningCategory, String, IConstruct[])</a></td><td>
Adds a warning.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Lextm_SharpSnmpPro_Mib_Validation_ErrorRegistry_AddWarning">AddWarning(WarningCategory, String, IToken, String)</a></td><td>
Adds a warning.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="https://docs.microsoft.com/dotnet/api/system.object.equals#System_Object_Equals_System_Object_" target="_blank" rel="noopener noreferrer">Equals</a></td><td>
Determines whether the specified object is equal to the current object.
 (Inherited from <a href="https://docs.microsoft.com/dotnet/api/system.object" target="_blank" rel="noopener noreferrer">Object</a>.)</td></tr><tr><td>![Protected method](media/protmethod.gif "Protected method")</td><td><a href="https://docs.microsoft.com/dotnet/api/system.object.finalize#System_Object_Finalize" target="_blank" rel="noopener noreferrer">Finalize</a></td><td>
Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.
 (Inherited from <a href="https://docs.microsoft.com/dotnet/api/system.object" target="_blank" rel="noopener noreferrer">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="https://docs.microsoft.com/dotnet/api/system.object.gethashcode#System_Object_GetHashCode" target="_blank" rel="noopener noreferrer">GetHashCode</a></td><td>
Serves as the default hash function.
 (Inherited from <a href="https://docs.microsoft.com/dotnet/api/system.object" target="_blank" rel="noopener noreferrer">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="https://docs.microsoft.com/dotnet/api/system.object.gettype#System_Object_GetType" target="_blank" rel="noopener noreferrer">GetType</a></td><td>
Gets the <a href="https://docs.microsoft.com/dotnet/api/system.type" target="_blank" rel="noopener noreferrer">Type</a> of the current instance.
 (Inherited from <a href="https://docs.microsoft.com/dotnet/api/system.object" target="_blank" rel="noopener noreferrer">Object</a>.)</td></tr><tr><td>![Protected method](media/protmethod.gif "Protected method")</td><td><a href="https://docs.microsoft.com/dotnet/api/system.object.memberwiseclone#System_Object_MemberwiseClone" target="_blank" rel="noopener noreferrer">MemberwiseClone</a></td><td>
Creates a shallow copy of the current <a href="https://docs.microsoft.com/dotnet/api/system.object" target="_blank" rel="noopener noreferrer">Object</a>.
 (Inherited from <a href="https://docs.microsoft.com/dotnet/api/system.object" target="_blank" rel="noopener noreferrer">Object</a>.)</td></tr><tr><td>![Protected method](media/protmethod.gif "Protected method")</td><td><a href="M_Lextm_SharpSnmpPro_Mib_Validation_ErrorRegistry_OnErrorAdded">OnErrorAdded</a></td><td>
Called when an error is added.</td></tr><tr><td>![Protected method](media/protmethod.gif "Protected method")</td><td><a href="M_Lextm_SharpSnmpPro_Mib_Validation_ErrorRegistry_OnMessageAdded">OnMessageAdded</a></td><td>
Called when a message is added.</td></tr><tr><td>![Protected method](media/protmethod.gif "Protected method")</td><td><a href="M_Lextm_SharpSnmpPro_Mib_Validation_ErrorRegistry_OnWarningAdded">OnWarningAdded</a></td><td>
Called when a warning is added.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="https://docs.microsoft.com/dotnet/api/system.object.tostring#System_Object_ToString" target="_blank" rel="noopener noreferrer">ToString</a></td><td>
Returns a string that represents the current object.
 (Inherited from <a href="https://docs.microsoft.com/dotnet/api/system.object" target="_blank" rel="noopener noreferrer">Object</a>.)</td></tr></table>&nbsp;
<a href="#errorregistry-class">Back to Top</a>

## Events
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_Lextm_SharpSnmpPro_Mib_Validation_ErrorRegistry_ErrorAdded">ErrorAdded</a></td><td>
Occurs when an error is added.</td></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_Lextm_SharpSnmpPro_Mib_Validation_ErrorRegistry_MessageAdded">MessageAdded</a></td><td>
Occurs when a message is added.</td></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_Lextm_SharpSnmpPro_Mib_Validation_ErrorRegistry_WarningAdded">WarningAdded</a></td><td>
Occurs when a warning is added.</td></tr></table>&nbsp;
<a href="#errorregistry-class">Back to Top</a>

## See Also


#### Reference
<a href="N_Lextm_SharpSnmpPro_Mib_Validation">Lextm.SharpSnmpPro.Mib.Validation Namespace</a><br />