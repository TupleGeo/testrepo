# EnumToResourceDescriptionConverter Class
 

Converts the value of an enumeration to a <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">String</a> having the description of this value.


## Inheritance Hierarchy
<a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">System.Object</a><br />&nbsp;&nbsp;TupleGeo.General.Windows.Data.EnumToResourceDescriptionConverter<br />
**Namespace:**&nbsp;<a href="N_TupleGeo_General_Windows_Data">TupleGeo.General.Windows.Data</a><br />**Assembly:**&nbsp;TupleGeo.General.Windows.Presentation (in TupleGeo.General.Windows.Presentation.dll) Version: 1.0.1.35963 (1.0.1)

## Syntax

**C#**<br />
``` C#
[ValueConversionAttribute(typeof(Object), typeof(string))]
public class EnumToResourceDescriptionConverter : IValueConverter
```

The EnumToResourceDescriptionConverter type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_TupleGeo_General_Windows_Data_EnumToResourceDescriptionConverter__ctor">EnumToResourceDescriptionConverter</a></td><td>
Initializes a new instance of the EnumToResourceDescriptionConverter class</td></tr></table>&nbsp;
<a href="#enumtoresourcedescriptionconverter-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_TupleGeo_General_Windows_Data_EnumToResourceDescriptionConverter_Convert">Convert</a></td><td>
Converts the enumeration value to a <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">String</a> having the description of this value.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_TupleGeo_General_Windows_Data_EnumToResourceDescriptionConverter_ConvertBack">ConvertBack</a></td><td>
Converts back from the enumeration description to the enumeration value.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/bsc2ak47" target="_blank">Equals</a></td><td>
Determines whether the specified object is equal to the current object.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Protected method](media/protmethod.gif "Protected method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/4k87zsw7" target="_blank">Finalize</a></td><td>
Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/zdee4b3y" target="_blank">GetHashCode</a></td><td>
Serves as a hash function for a particular type.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/dfwy45w9" target="_blank">GetType</a></td><td>
Gets the <a href="http://msdn2.microsoft.com/en-us/library/42892f65" target="_blank">Type</a> of the current instance.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Protected method](media/protmethod.gif "Protected method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/57ctke0a" target="_blank">MemberwiseClone</a></td><td>
Creates a shallow copy of the current <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/7bxwbwt2" target="_blank">ToString</a></td><td>
Returns a string that represents the current object.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr></table>&nbsp;
<a href="#enumtoresourcedescriptionconverter-class">Back to Top</a>

## Extension Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_TupleGeo_General_ObjectExtensions_GetPropertyValueString">GetPropertyValueString</a></td><td>
Gets a <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">String</a> representation of the value of a specified property of an object.
 (Defined by <a href="T_TupleGeo_General_ObjectExtensions">ObjectExtensions</a>.)</td></tr></table>&nbsp;
<a href="#enumtoresourcedescriptionconverter-class">Back to Top</a>

## Remarks
The description is retrieved by using the attached <a href="T_TupleGeo_General_Attributes_ResourceDescriptionAttribute">ResourceDescriptionAttribute</a> for each enumerated value. The description then is used to retrieve a localized version of it from an associated localized resource.

## See Also


#### Reference
<a href="N_TupleGeo_General_Windows_Data">TupleGeo.General.Windows.Data Namespace</a><br />