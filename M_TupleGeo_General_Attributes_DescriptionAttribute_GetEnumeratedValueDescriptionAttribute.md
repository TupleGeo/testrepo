# DescriptionAttribute.GetEnumeratedValueDescriptionAttribute Method (Object)
 

Gets the neutral culture <a href="T_TupleGeo_General_Attributes_DescriptionAttribute">DescriptionAttribute</a> description.

**Namespace:**&nbsp;<a href="N_TupleGeo_General_Attributes">TupleGeo.General.Attributes</a><br />**Assembly:**&nbsp;TupleGeo.General (in TupleGeo.General.dll) Version: 2.1.0.35959 (2.1.0)

## Syntax

**C#**<br />
``` C#
public static string GetEnumeratedValueDescriptionAttribute(
	Object enumValue
)
```


#### Parameters
&nbsp;<dl><dt>enumValue</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">System.Object</a><br />The Enumerated value used to retrieve its <a href="T_TupleGeo_General_Attributes_DescriptionAttribute">DescriptionAttribute</a> description.</dd></dl>

#### Return Value
Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">String</a><br />A string with the neutral culture description.

## Remarks
The neutral culture description is not associated with a specific culture. Thus the <a href="P_TupleGeo_General_Attributes_DescriptionAttribute_Culture">DescriptionAttribute.Culture</a> property must be null. In such a case a neutral culture description is specified. If no neutral culture description has been found, a zero length string will be returned instead.

## See Also


#### Reference
<a href="T_TupleGeo_General_Attributes_DescriptionAttribute">DescriptionAttribute Class</a><br /><a href="Overload_TupleGeo_General_Attributes_DescriptionAttribute_GetEnumeratedValueDescriptionAttribute">GetEnumeratedValueDescriptionAttribute Overload</a><br /><a href="N_TupleGeo_General_Attributes">TupleGeo.General.Attributes Namespace</a><br />