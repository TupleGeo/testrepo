# XmlSerializer.SerializeToString Method (Object, Encoding)
 

Serializes the specified object in to a <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">String</a>.

**Namespace:**&nbsp;<a href="N_TupleGeo_General_Serialization">TupleGeo.General.Serialization</a><br />**Assembly:**&nbsp;TupleGeo.General (in TupleGeo.General.dll) Version: 2.1.0.35959 (2.1.0)

## Syntax

**C#**<br />
``` C#
public static string SerializeToString(
	Object value,
	Encoding encoding
)
```


#### Parameters
&nbsp;<dl><dt>value</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">System.Object</a><br />The object to serialize.</dd><dt>encoding</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/86hf4sb8" target="_blank">System.Text.Encoding</a><br />The <a href="http://msdn2.microsoft.com/en-us/library/86hf4sb8" target="_blank">Encoding</a> used to serialize the object.</dd></dl>

#### Return Value
Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">String</a><br />A <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">String</a> containing the serialized object.

## Remarks

The method might not return the entire object graph in to a serialized string. This is caused by the internal <a href="http://msdn2.microsoft.com/en-us/library/9a84386f" target="_blank">MemoryStream</a> byte buffer length used in the serialization process of this method.


## See Also


#### Reference
<a href="T_TupleGeo_General_Serialization_XmlSerializer">XmlSerializer Class</a><br /><a href="Overload_TupleGeo_General_Serialization_XmlSerializer_SerializeToString">SerializeToString Overload</a><br /><a href="N_TupleGeo_General_Serialization">TupleGeo.General.Serialization Namespace</a><br />