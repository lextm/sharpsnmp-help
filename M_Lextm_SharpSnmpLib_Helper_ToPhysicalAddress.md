# Helper.ToPhysicalAddress Method 
 

**Namespace:**&nbsp;<a href="N_Lextm_SharpSnmpLib">Lextm.SharpSnmpLib</a><br />**Assembly:**&nbsp;SharpSnmpLib (in SharpSnmpLib.dll) Version: 12.4.0+601762d0e653a71ebb69af963204dfbfb6c26b74

## Syntax

**C#**<br />
``` C#
public static PhysicalAddress ToPhysicalAddress(
	this OctetString address
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
Public Shared Function ToPhysicalAddress ( 
	address As OctetString
) As PhysicalAddress
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
static PhysicalAddress^ ToPhysicalAddress(
	OctetString^ address
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
static member ToPhysicalAddress : 
        address : OctetString -> PhysicalAddress 

```


#### Parameters
&nbsp;<dl><dt>address</dt><dd>Type: <a href="T_Lextm_SharpSnmpLib_OctetString">Lextm.SharpSnmpLib.OctetString</a><br /></dd></dl>

#### Return Value
Type: <a href="https://docs.microsoft.com/dotnet/api/system.net.networkinformation.physicaladdress" target="_blank" rel="noopener noreferrer">PhysicalAddress</a>

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type <a href="T_Lextm_SharpSnmpLib_OctetString">OctetString</a>. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods" target="_blank" rel="noopener noreferrer">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods" target="_blank" rel="noopener noreferrer">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_Lextm_SharpSnmpLib_Helper">Helper Class</a><br /><a href="N_Lextm_SharpSnmpLib">Lextm.SharpSnmpLib Namespace</a><br />