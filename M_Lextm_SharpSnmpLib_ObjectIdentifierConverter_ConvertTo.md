# ObjectIdentifierConverter.ConvertTo Method (ITypeDescriptorContext, CultureInfo, Object, Type)
 

**Namespace:**&nbsp;<a href="N_Lextm_SharpSnmpLib">Lextm.SharpSnmpLib</a><br />**Assembly:**&nbsp;SharpSnmpLib (in SharpSnmpLib.dll) Version: 12.4.0+601762d0e653a71ebb69af963204dfbfb6c26b74

## Syntax

**C#**<br />
``` C#
public override Object ConvertTo(
	ITypeDescriptorContext context,
	CultureInfo culture,
	Object value,
	Type destinationType
)
```

**VB**<br />
``` VB
Public Overrides Function ConvertTo ( 
	context As ITypeDescriptorContext,
	culture As CultureInfo,
	value As Object,
	destinationType As Type
) As Object
```

**C++**<br />
``` C++
public:
virtual Object^ ConvertTo(
	ITypeDescriptorContext^ context, 
	CultureInfo^ culture, 
	Object^ value, 
	Type^ destinationType
) override
```

**F#**<br />
``` F#
abstract ConvertTo : 
        context : ITypeDescriptorContext * 
        culture : CultureInfo * 
        value : Object * 
        destinationType : Type -> Object 
override ConvertTo : 
        context : ITypeDescriptorContext * 
        culture : CultureInfo * 
        value : Object * 
        destinationType : Type -> Object 
```


#### Parameters
&nbsp;<dl><dt>context</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.componentmodel.itypedescriptorcontext" target="_blank" rel="noopener noreferrer">System.ComponentModel.ITypeDescriptorContext</a><br /></dd><dt>culture</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.globalization.cultureinfo" target="_blank" rel="noopener noreferrer">System.Globalization.CultureInfo</a><br /></dd><dt>value</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.object" target="_blank" rel="noopener noreferrer">System.Object</a><br /></dd><dt>destinationType</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.type" target="_blank" rel="noopener noreferrer">System.Type</a><br /></dd></dl>

#### Return Value
Type: <a href="https://docs.microsoft.com/dotnet/api/system.object" target="_blank" rel="noopener noreferrer">Object</a>

## See Also


#### Reference
<a href="T_Lextm_SharpSnmpLib_ObjectIdentifierConverter">ObjectIdentifierConverter Class</a><br /><a href="Overload_Lextm_SharpSnmpLib_ObjectIdentifierConverter_ConvertTo">ConvertTo Overload</a><br /><a href="N_Lextm_SharpSnmpLib">Lextm.SharpSnmpLib Namespace</a><br />