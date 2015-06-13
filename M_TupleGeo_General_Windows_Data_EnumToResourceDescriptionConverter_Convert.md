# EnumToResourceDescriptionConverter.Convert Method 
 

Converts the enumeration value to a <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">String</a> having the description of this value.

**Namespace:**&nbsp;<a href="N_TupleGeo_General_Windows_Data">TupleGeo.General.Windows.Data</a><br />**Assembly:**&nbsp;TupleGeo.General.Windows.Presentation (in TupleGeo.General.Windows.Presentation.dll) Version: 1.0.1.35963 (1.0.1)

## Syntax

**C#**<br />
``` C#
public Object Convert(
	Object value,
	Type targetType,
	Object parameter,
	CultureInfo culture
)
```


#### Parameters
&nbsp;<dl><dt>value</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">System.Object</a><br />The enumeration value that needs to be converted.</dd><dt>targetType</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/42892f65" target="_blank">System.Type</a><br />The target <a href="http://msdn2.microsoft.com/en-us/library/42892f65" target="_blank">Type</a>.</dd><dt>parameter</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">System.Object</a><br />A parameter used by the converter. Accepted values for this converter is either null or an instance of a Resource file.</dd><dt>culture</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/kx54z3k7" target="_blank">System.Globalization.CultureInfo</a><br />The <a href="http://msdn2.microsoft.com/en-us/library/kx54z3k7" target="_blank">culture</a> used by this converter during the conversion operation.</dd></dl>

#### Return Value
Type: <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a><br />A <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">String</a> containing the description.

#### Implements
<a href="http://msdn2.microsoft.com/en-us/library/ms590771" target="_blank">IValueConverter.Convert(Object, Type, Object, CultureInfo)</a><br />

## Remarks

The Convert method can be used in two ways.

If no parameter is supplied, then it is assumed that the Resource that will be used by the associated <a href="T_TupleGeo_General_Attributes_ResourceDescriptionAttribute">ResourceDescriptionAttribute</a> has a <a href="http://msdn2.microsoft.com/en-us/library/kx54z3k7" target="_blank">Culture</a> set. If this is not set then the UI culture will be used instead.

If a parameter is supplied, then it must be a Resource object and the culture must be set as well. In XAML this can be done by setting either the Language property of the element that will show the converted values, or by setting the ConverterCulture of the converter.

If no resource description will be retrieved then the name of the enumerated value will be returned instead.


## See Also


#### Reference
<a href="T_TupleGeo_General_Windows_Data_EnumToResourceDescriptionConverter">EnumToResourceDescriptionConverter Class</a><br /><a href="N_TupleGeo_General_Windows_Data">TupleGeo.General.Windows.Data Namespace</a><br />