# EntityExtensions.GetObjectIdentifier Method 
 

Gets object identifier.

**Namespace:**&nbsp;<a href="N_Lextm_SharpSnmpPro_Mib">Lextm.SharpSnmpPro.Mib</a><br />**Assembly:**&nbsp;SharpSnmpPro.Mib (in SharpSnmpPro.Mib.dll) Version: 2.1.2

## Syntax

**C#**<br />
``` C#
public static uint[] GetObjectIdentifier(
	this IEntity entity
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
Public Shared Function GetObjectIdentifier ( 
	entity As IEntity
) As UInteger()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
static array<unsigned int>^ GetObjectIdentifier(
	IEntity^ entity
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
static member GetObjectIdentifier : 
        entity : IEntity -> uint32[] 

```


#### Parameters
&nbsp;<dl><dt>entity</dt><dd>Type: <a href="T_Lextm_SharpSnmpPro_Mib_IEntity">Lextm.SharpSnmpPro.Mib.IEntity</a><br />Entity.</dd></dl>

#### Return Value
Type: <a href="https://docs.microsoft.com/dotnet/api/system.uint32" target="_blank" rel="noopener noreferrer">UInt32</a>[]<br />

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type <a href="T_Lextm_SharpSnmpPro_Mib_IEntity">IEntity</a>. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods" target="_blank" rel="noopener noreferrer">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods" target="_blank" rel="noopener noreferrer">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_Lextm_SharpSnmpPro_Mib_EntityExtensions">EntityExtensions Class</a><br /><a href="N_Lextm_SharpSnmpPro_Mib">Lextm.SharpSnmpPro.Mib Namespace</a><br />