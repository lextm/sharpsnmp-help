# SmiTypeExtensions.Verify Method 
 

Verifies the input data against the syntax.

**Namespace:**&nbsp;<a href="N_Lextm_SharpSnmpPro_Mib">Lextm.SharpSnmpPro.Mib</a><br />**Assembly:**&nbsp;SharpSnmpPro.Mib (in SharpSnmpPro.Mib.dll) Version: 2.1.2

## Syntax

**C#**<br />
``` C#
public static bool Verify(
	this ISmiType type,
	ISnmpData data
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
Public Shared Function Verify ( 
	type As ISmiType,
	data As ISnmpData
) As Boolean
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
static bool Verify(
	ISmiType^ type, 
	ISnmpData^ data
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
static member Verify : 
        type : ISmiType * 
        data : ISnmpData -> bool 

```


#### Parameters
&nbsp;<dl><dt>type</dt><dd>Type: <a href="T_Lextm_SharpSnmpPro_Mib_ISmiType">Lextm.SharpSnmpPro.Mib.ISmiType</a><br />Syntax type.</dd><dt>data</dt><dd>Type: <a href="T_Lextm_SharpSnmpLib_ISnmpData">Lextm.SharpSnmpLib.ISnmpData</a><br />Input data.</dd></dl>

#### Return Value
Type: <a href="https://docs.microsoft.com/dotnet/api/system.boolean" target="_blank" rel="noopener noreferrer">Boolean</a><br />
```
true
```
 if the data matches the syntax. Otherwise, 
```
false
```
.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type <a href="T_Lextm_SharpSnmpPro_Mib_ISmiType">ISmiType</a>. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods" target="_blank" rel="noopener noreferrer">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods" target="_blank" rel="noopener noreferrer">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_Lextm_SharpSnmpPro_Mib_SmiTypeExtensions">SmiTypeExtensions Class</a><br /><a href="N_Lextm_SharpSnmpPro_Mib">Lextm.SharpSnmpPro.Mib Namespace</a><br />