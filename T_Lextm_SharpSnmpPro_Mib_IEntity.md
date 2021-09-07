# IEntity Interface
 

Entity interface.

**Namespace:**&nbsp;<a href="N_Lextm_SharpSnmpPro_Mib">Lextm.SharpSnmpPro.Mib</a><br />**Assembly:**&nbsp;SharpSnmpPro.Mib (in SharpSnmpPro.Mib.dll) Version: 2.1.2

## Syntax

**C#**<br />
``` C#
public interface IEntity : IConstruct, 
	IValidatable
```

**VB**<br />
``` VB
Public Interface IEntity
	Inherits IConstruct, IValidatable
```

**C++**<br />
``` C++
public interface class IEntity : IConstruct, 
	IValidatable
```

**F#**<br />
``` F#
type IEntity =  
    interface
        interface IConstruct
        interface IValidatable
    end
```

The IEntity type exposes the following members.


## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Lextm_SharpSnmpPro_Mib_IConstruct_CharPositionInLine">CharPositionInLine</a></td><td>
Gets the char position in line.
 (Inherited from <a href="T_Lextm_SharpSnmpPro_Mib_IConstruct">IConstruct</a>.)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Lextm_SharpSnmpPro_Mib_IEntity_Description">Description</a></td><td>
Provides a textual description of the item being defined.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Lextm_SharpSnmpPro_Mib_IConstruct_Line">Line</a></td><td>
Gets the line number.
 (Inherited from <a href="T_Lextm_SharpSnmpPro_Mib_IConstruct">IConstruct</a>.)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Lextm_SharpSnmpPro_Mib_IConstruct_Module">Module</a></td><td>
Gets or sets the module.
 (Inherited from <a href="T_Lextm_SharpSnmpPro_Mib_IConstruct">IConstruct</a>.)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Lextm_SharpSnmpPro_Mib_IConstruct_Name">Name</a></td><td>
Name.
 (Inherited from <a href="T_Lextm_SharpSnmpPro_Mib_IConstruct">IConstruct</a>.)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Lextm_SharpSnmpPro_Mib_IEntity_ObjectIdentifier">ObjectIdentifier</a></td><td> **Obsolete. **
Gets or sets the object identifier.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Lextm_SharpSnmpPro_Mib_IEntity_Parent">Parent</a></td><td>
Gets or sets the parent.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Lextm_SharpSnmpPro_Mib_IEntity_Reference">Reference</a></td><td>
Specifies the source of the definition (such as a document from another standards organization, or an architectural document for a proprietary system).</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Lextm_SharpSnmpPro_Mib_IEntity_Status">Status</a></td><td>
Status.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Lextm_SharpSnmpPro_Mib_IEntity_Value">Value</a></td><td>
Gets or sets the value.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Lextm_SharpSnmpPro_Mib_IEntity_Values">Values</a></td><td /></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Lextm_SharpSnmpPro_Mib_IEntity_Verified">Verified</a></td><td /></tr></table>&nbsp;
<a href="#ientity-interface">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Lextm_SharpSnmpPro_Mib_IValidatable_Validate">Validate</a></td><td>
Validates this entity.
 (Inherited from <a href="T_Lextm_SharpSnmpPro_Mib_IValidatable">IValidatable</a>.)</td></tr></table>&nbsp;
<a href="#ientity-interface">Back to Top</a>

## Extension Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_Lextm_SharpSnmpPro_Mib_EntityExtensions_DescriptionFormatted">DescriptionFormatted</a></td><td>
Formatted description.
 (Defined by <a href="T_Lextm_SharpSnmpPro_Mib_EntityExtensions">EntityExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_Lextm_SharpSnmpPro_Mib_EntityExtensions_GetObjectIdentifier">GetObjectIdentifier</a></td><td>
Gets object identifier.
 (Defined by <a href="T_Lextm_SharpSnmpPro_Mib_EntityExtensions">EntityExtensions</a>.)</td></tr></table>&nbsp;
<a href="#ientity-interface">Back to Top</a>

## See Also


#### Reference
<a href="N_Lextm_SharpSnmpPro_Mib">Lextm.SharpSnmpPro.Mib Namespace</a><br />