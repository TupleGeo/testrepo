# EnumDescriptionConverter.GetEnumDescriptions Method (Enum)
 

Gets the neutral culture descriptions of all enumerated values found in an enumeration.

**Namespace:**&nbsp;<a href="N_TupleGeo_General_ComponentModel">TupleGeo.General.ComponentModel</a><br />**Assembly:**&nbsp;TupleGeo.General (in TupleGeo.General.dll) Version: 2.1.0.35959 (2.1.0)

## Syntax

**C#**<br />
``` C#
public static string[] GetEnumDescriptions(
	Enum enumValue
)
```


#### Parameters
&nbsp;<dl><dt>enumValue</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/1zt1ybx4" target="_blank">System.Enum</a><br />An enumerated value used to find out the enumeration it belongs.</dd></dl>

#### Return Value
Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">String</a>[]<br />An array of <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">strings</a> containing the descriptions of the enumerated values.

## Remarks

If no enumerated values found in the enumeration a null is returned instead.

If no <a href="http://msdn2.microsoft.com/en-us/library/xwb66ftt" target="_blank">DescriptionAttribute</a> has been set for the enumerated values, a string representation of the name of the enumerated values is returned instead.


## See Also


#### Reference
<a href="T_TupleGeo_General_ComponentModel_EnumDescriptionConverter">EnumDescriptionConverter Class</a><br /><a href="Overload_TupleGeo_General_ComponentModel_EnumDescriptionConverter_GetEnumDescriptions">GetEnumDescriptions Overload</a><br /><a href="N_TupleGeo_General_ComponentModel">TupleGeo.General.ComponentModel Namespace</a><br />