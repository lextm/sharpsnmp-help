# ReloadableObjectRegistry Class
 

Object registry.


## Inheritance Hierarchy
<a href="https://docs.microsoft.com/dotnet/api/system.object" target="_blank" rel="noopener noreferrer">System.Object</a><br />&nbsp;&nbsp;<a href="T_Lextm_SharpSnmpPro_Mib_Registry_ObjectRegistryBase">Lextm.SharpSnmpPro.Mib.Registry.ObjectRegistryBase</a><br />&nbsp;&nbsp;&nbsp;&nbsp;Lextm.SharpSnmpPro.Mib.Registry.ReloadableObjectRegistry<br />
**Namespace:**&nbsp;<a href="N_Lextm_SharpSnmpPro_Mib_Registry">Lextm.SharpSnmpPro.Mib.Registry</a><br />**Assembly:**&nbsp;SharpSnmpPro.Mib (in SharpSnmpPro.Mib.dll) Version: 2.1.2

## Syntax

**C#**<br />
``` C#
public class ReloadableObjectRegistry : ObjectRegistryBase
```

**VB**<br />
``` VB
Public Class ReloadableObjectRegistry
	Inherits ObjectRegistryBase
```

**C++**<br />
``` C++
public ref class ReloadableObjectRegistry : public ObjectRegistryBase
```

**F#**<br />
``` F#
type ReloadableObjectRegistry =  
    class
        inherit ObjectRegistryBase
    end
```

The ReloadableObjectRegistry type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Lextm_SharpSnmpPro_Mib_Registry_ReloadableObjectRegistry__ctor">ReloadableObjectRegistry</a></td><td>
Initializes a new instance of the ReloadableObjectRegistry class.</td></tr></table>&nbsp;
<a href="#reloadableobjectregistry-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Lextm_SharpSnmpPro_Mib_Registry_ReloadableObjectRegistry_Path">Path</a></td><td>
Gets the path.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Lextm_SharpSnmpPro_Mib_Registry_ObjectRegistryBase_Tree">Tree</a></td><td>
Object tree.
 (Inherited from <a href="T_Lextm_SharpSnmpPro_Mib_Registry_ObjectRegistryBase">ObjectRegistryBase</a>.)</td></tr></table>&nbsp;
<a href="#reloadableobjectregistry-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Lextm_SharpSnmpPro_Mib_Registry_ObjectRegistryBase_CreateVariable">CreateVariable(String)</a></td><td>
Creates a variable.
 (Inherited from <a href="T_Lextm_SharpSnmpPro_Mib_Registry_ObjectRegistryBase">ObjectRegistryBase</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Lextm_SharpSnmpPro_Mib_Registry_ObjectRegistryBase_CreateVariable_1">CreateVariable(String, ISnmpData)</a></td><td>
Creates a variable.
 (Inherited from <a href="T_Lextm_SharpSnmpPro_Mib_Registry_ObjectRegistryBase">ObjectRegistryBase</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Lextm_SharpSnmpPro_Mib_Registry_ObjectRegistryBase_Decode_2">Decode(UInt32[], ISnmpData)</a></td><td>
Decodes the data against the object identifier.
 (Inherited from <a href="T_Lextm_SharpSnmpPro_Mib_Registry_ObjectRegistryBase">ObjectRegistryBase</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Lextm_SharpSnmpPro_Mib_Registry_ObjectRegistryBase_Decode">Decode(ObjectIdentifier, ISnmpData)</a></td><td>
Decodes the data against the object identifier.
 (Inherited from <a href="T_Lextm_SharpSnmpPro_Mib_Registry_ObjectRegistryBase">ObjectRegistryBase</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Lextm_SharpSnmpPro_Mib_Registry_ObjectRegistryBase_Decode_1">Decode(String, String, ISnmpData)</a></td><td>
Decodes the data against the object name in specified module.
 (Inherited from <a href="T_Lextm_SharpSnmpPro_Mib_Registry_ObjectRegistryBase">ObjectRegistryBase</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="https://docs.microsoft.com/dotnet/api/system.object.equals#System_Object_Equals_System_Object_" target="_blank" rel="noopener noreferrer">Equals</a></td><td>
Determines whether the specified object is equal to the current object.
 (Inherited from <a href="https://docs.microsoft.com/dotnet/api/system.object" target="_blank" rel="noopener noreferrer">Object</a>.)</td></tr><tr><td>![Protected method](media/protmethod.gif "Protected method")</td><td><a href="https://docs.microsoft.com/dotnet/api/system.object.finalize#System_Object_Finalize" target="_blank" rel="noopener noreferrer">Finalize</a></td><td>
Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.
 (Inherited from <a href="https://docs.microsoft.com/dotnet/api/system.object" target="_blank" rel="noopener noreferrer">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="https://docs.microsoft.com/dotnet/api/system.object.gethashcode#System_Object_GetHashCode" target="_blank" rel="noopener noreferrer">GetHashCode</a></td><td>
Serves as the default hash function.
 (Inherited from <a href="https://docs.microsoft.com/dotnet/api/system.object" target="_blank" rel="noopener noreferrer">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="https://docs.microsoft.com/dotnet/api/system.object.gettype#System_Object_GetType" target="_blank" rel="noopener noreferrer">GetType</a></td><td>
Gets the <a href="https://docs.microsoft.com/dotnet/api/system.type" target="_blank" rel="noopener noreferrer">Type</a> of the current instance.
 (Inherited from <a href="https://docs.microsoft.com/dotnet/api/system.object" target="_blank" rel="noopener noreferrer">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Lextm_SharpSnmpPro_Mib_Registry_ObjectRegistryBase_Import">Import</a></td><td>
Imports instances of <a href="T_Lextm_SharpSnmpPro_Mib_Module">Module</a>.
 (Inherited from <a href="T_Lextm_SharpSnmpPro_Mib_Registry_ObjectRegistryBase">ObjectRegistryBase</a>.)</td></tr><tr><td>![Protected method](media/protmethod.gif "Protected method")</td><td><a href="https://docs.microsoft.com/dotnet/api/system.object.memberwiseclone#System_Object_MemberwiseClone" target="_blank" rel="noopener noreferrer">MemberwiseClone</a></td><td>
Creates a shallow copy of the current <a href="https://docs.microsoft.com/dotnet/api/system.object" target="_blank" rel="noopener noreferrer">Object</a>.
 (Inherited from <a href="https://docs.microsoft.com/dotnet/api/system.object" target="_blank" rel="noopener noreferrer">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Lextm_SharpSnmpPro_Mib_Registry_ObjectRegistryBase_Refresh">Refresh</a></td><td>
Refreshes.
 (Inherited from <a href="T_Lextm_SharpSnmpPro_Mib_Registry_ObjectRegistryBase">ObjectRegistryBase</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Lextm_SharpSnmpPro_Mib_Registry_ReloadableObjectRegistry_Reload">Reload</a></td><td>
Reloads the registry.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="https://docs.microsoft.com/dotnet/api/system.object.tostring#System_Object_ToString" target="_blank" rel="noopener noreferrer">ToString</a></td><td>
Returns a string that represents the current object.
 (Inherited from <a href="https://docs.microsoft.com/dotnet/api/system.object" target="_blank" rel="noopener noreferrer">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Lextm_SharpSnmpPro_Mib_Registry_ObjectRegistryBase_Translate">Translate(String)</a></td><td>
Gets numerical form from textual form.
 (Inherited from <a href="T_Lextm_SharpSnmpPro_Mib_Registry_ObjectRegistryBase">ObjectRegistryBase</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Lextm_SharpSnmpPro_Mib_Registry_ObjectRegistryBase_Translate_2">Translate(UInt32[])</a></td><td>
Gets textual form from numerical form.
 (Inherited from <a href="T_Lextm_SharpSnmpPro_Mib_Registry_ObjectRegistryBase">ObjectRegistryBase</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Lextm_SharpSnmpPro_Mib_Registry_ObjectRegistryBase_Translate_1">Translate(String, String)</a></td><td>
Gets numerical form from textual form.
 (Inherited from <a href="T_Lextm_SharpSnmpPro_Mib_Registry_ObjectRegistryBase">ObjectRegistryBase</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Lextm_SharpSnmpPro_Mib_Registry_ObjectRegistryBase_ValidateTable">ValidateTable</a></td><td>
Validates if an <a href="T_Lextm_SharpSnmpLib_ObjectIdentifier">ObjectIdentifier</a> is a table.
 (Inherited from <a href="T_Lextm_SharpSnmpPro_Mib_Registry_ObjectRegistryBase">ObjectRegistryBase</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Lextm_SharpSnmpPro_Mib_Registry_ObjectRegistryBase_Verify">Verify(ObjectIdentifier, ISnmpData)</a></td><td>
Verifies the data against the object identifier.
 (Inherited from <a href="T_Lextm_SharpSnmpPro_Mib_Registry_ObjectRegistryBase">ObjectRegistryBase</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Lextm_SharpSnmpPro_Mib_Registry_ObjectRegistryBase_Verify_1">Verify(String, String, ISnmpData)</a></td><td>
Verifies the data against the object name defined in specified module.
 (Inherited from <a href="T_Lextm_SharpSnmpPro_Mib_Registry_ObjectRegistryBase">ObjectRegistryBase</a>.)</td></tr></table>&nbsp;
<a href="#reloadableobjectregistry-class">Back to Top</a>

## Events
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_Lextm_SharpSnmpPro_Mib_Registry_ObjectRegistryBase_OnChanged">OnChanged</a></td><td>
This event occurs when new documents are loaded.
 (Inherited from <a href="T_Lextm_SharpSnmpPro_Mib_Registry_ObjectRegistryBase">ObjectRegistryBase</a>.)</td></tr></table>&nbsp;
<a href="#reloadableobjectregistry-class">Back to Top</a>

## See Also


#### Reference
<a href="N_Lextm_SharpSnmpPro_Mib_Registry">Lextm.SharpSnmpPro.Mib.Registry Namespace</a><br />