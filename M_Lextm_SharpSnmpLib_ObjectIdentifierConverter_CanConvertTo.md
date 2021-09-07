# ObjectIdentifierConverter.CanConvertTo Method (ITypeDescriptorContext, Type)
 

**Namespace:**&nbsp;<a href="N_Lextm_SharpSnmpLib">Lextm.SharpSnmpLib</a><br />**Assembly:**&nbsp;SharpSnmpLib (in SharpSnmpLib.dll) Version: 12.4.0+601762d0e653a71ebb69af963204dfbfb6c26b74

## Syntax

**C#**<br />
``` C#
public override bool CanConvertTo(
	ITypeDescriptorContext context,
	Type destinationType
)
```

**VB**<br />
``` VB
Public Overrides Function CanConvertTo ( 
	context As ITypeDescriptorContext,
	destinationType As Type
) As Boolean
```

**C++**<br />
``` C++
public:
virtual bool CanConvertTo(
	ITypeDescriptorContext^ context, 
	Type^ destinationType
) override
```

**F#**<br />
``` F#
abstract CanConvertTo : 
        context : ITypeDescriptorContext * 
        destinationType : Type -> bool 
override CanConvertTo : 
        context : ITypeDescriptorContext * 
        destinationType : Type -> bool 
```


#### Parameters
&nbsp;<dl><dt>context</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.componentmodel.itypedescriptorcontext" target="_blank" rel="noopener noreferrer">System.ComponentModel.ITypeDescriptorContext</a><br /></dd><dt>destinationType</dt><dd>Type: <a href="https://docs.microsoft.com/dotnet/api/system.type" target="_blank" rel="noopener noreferrer">System.Type</a><br /></dd></dl>

#### Return Value
Type: <a href="https://docs.microsoft.com/dotnet/api/system.boolean" target="_blank" rel="noopener noreferrer">Boolean</a>

## See Also


#### Reference
<a href="T_Lextm_SharpSnmpLib_ObjectIdentifierConverter">ObjectIdentifierConverter Class</a><br /><a href="Overload_Lextm_SharpSnmpLib_ObjectIdentifierConverter_CanConvertTo">CanConvertTo Overload</a><br /><a href="N_Lextm_SharpSnmpLib">Lextm.SharpSnmpLib Namespace</a><br />