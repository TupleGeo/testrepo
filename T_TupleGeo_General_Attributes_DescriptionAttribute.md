# DescriptionAttribute Class
 

A custom attribute used to add descriptive information.


## Inheritance Hierarchy
<a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">System.Object</a><br />&nbsp;&nbsp;<a href="http://msdn2.microsoft.com/en-us/library/e8kc3626" target="_blank">System.Attribute</a><br />&nbsp;&nbsp;&nbsp;&nbsp;TupleGeo.General.Attributes.DescriptionAttribute<br />
**Namespace:**&nbsp;<a href="N_TupleGeo_General_Attributes">TupleGeo.General.Attributes</a><br />**Assembly:**&nbsp;TupleGeo.General (in TupleGeo.General.dll) Version: 2.1.0.35959 (2.1.0)

## Syntax

**C#**<br />
``` C#
[AttributeUsageAttribute(AttributeTargets.All, AllowMultiple = true)]
public sealed class DescriptionAttribute : Attribute
```

The DescriptionAttribute type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_TupleGeo_General_Attributes_DescriptionAttribute__ctor">DescriptionAttribute(String)</a></td><td>
Initializes a DescriptionAttribute by setting its description irrelevant to a culture.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_TupleGeo_General_Attributes_DescriptionAttribute__ctor_1">DescriptionAttribute(String, String)</a></td><td>
Initializes a DescriptionAttribute by setting its description for a specified culture.</td></tr></table>&nbsp;
<a href="#descriptionattribute-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/09ds241w" target="_blank">Equals</a></td><td>
Returns a value that indicates whether this instance is equal to a specified object.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e8kc3626" target="_blank">Attribute</a>.)</td></tr><tr><td>![Protected method](media/protmethod.gif "Protected method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/4k87zsw7" target="_blank">Finalize</a></td><td>
Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_TupleGeo_General_Attributes_DescriptionAttribute_GetEnumeratedValueDescriptionAttribute">GetEnumeratedValueDescriptionAttribute(Object)</a></td><td>
Gets the neutral culture DescriptionAttribute description.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_TupleGeo_General_Attributes_DescriptionAttribute_GetEnumeratedValueDescriptionAttribute_1">GetEnumeratedValueDescriptionAttribute(Object, String)</a></td><td>
Gets the DescriptionAttribute description. associated with the specified culture.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/365e1bxs" target="_blank">GetHashCode</a></td><td>
Returns the hash code for this instance.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e8kc3626" target="_blank">Attribute</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/dfwy45w9" target="_blank">GetType</a></td><td>
Gets the <a href="http://msdn2.microsoft.com/en-us/library/42892f65" target="_blank">Type</a> of the current instance.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/tbkb5x6t" target="_blank">IsDefaultAttribute</a></td><td>
When overridden in a derived class, indicates whether the value of this instance is the default value for the derived class.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e8kc3626" target="_blank">Attribute</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/wy7chz44" target="_blank">Match</a></td><td>
When overridden in a derived class, returns a value that indicates whether this instance equals a specified object.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e8kc3626" target="_blank">Attribute</a>.)</td></tr><tr><td>![Protected method](media/protmethod.gif "Protected method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/57ctke0a" target="_blank">MemberwiseClone</a></td><td>
Creates a shallow copy of the current <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/7bxwbwt2" target="_blank">ToString</a></td><td>
Returns a string that represents the current object.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr></table>&nbsp;
<a href="#descriptionattribute-class">Back to Top</a>

## Extension Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_TupleGeo_General_ObjectExtensions_GetPropertyValueString">GetPropertyValueString</a></td><td>
Gets a <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">String</a> representation of the value of a specified property of an object.
 (Defined by <a href="T_TupleGeo_General_ObjectExtensions">ObjectExtensions</a>.)</td></tr></table>&nbsp;
<a href="#descriptionattribute-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_TupleGeo_General_Attributes_DescriptionAttribute_Culture">Culture</a></td><td>
Gets the Culture.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_TupleGeo_General_Attributes_DescriptionAttribute_Description">Description</a></td><td>
Gets / Sets the Description.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="http://msdn2.microsoft.com/en-us/library/sa1bf03e" target="_blank">TypeId</a></td><td>
When implemented in a derived class, gets a unique identifier for this <a href="http://msdn2.microsoft.com/en-us/library/e8kc3626" target="_blank">Attribute</a>.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e8kc3626" target="_blank">Attribute</a>.)</td></tr></table>&nbsp;
<a href="#descriptionattribute-class">Back to Top</a>

## Explicit Interface Implementations
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Explicit interface implementation](media/pubinterface.gif "Explicit interface implementation")![Private method](media/privmethod.gif "Private method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/bb336374" target="_blank">_Attribute.GetIDsOfNames</a></td><td>
Maps a set of names to a corresponding set of dispatch identifiers.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e8kc3626" target="_blank">Attribute</a>.)</td></tr><tr><td>![Explicit interface implementation](media/pubinterface.gif "Explicit interface implementation")![Private method](media/privmethod.gif "Private method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/bb339743" target="_blank">_Attribute.GetTypeInfo</a></td><td>
Retrieves the type information for an object, which can be used to get the type information for an interface.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e8kc3626" target="_blank">Attribute</a>.)</td></tr><tr><td>![Explicit interface implementation](media/pubinterface.gif "Explicit interface implementation")![Private method](media/privmethod.gif "Private method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/bb340142" target="_blank">_Attribute.GetTypeInfoCount</a></td><td>
Retrieves the number of type information interfaces that an object provides (either 0 or 1).
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e8kc3626" target="_blank">Attribute</a>.)</td></tr><tr><td>![Explicit interface implementation](media/pubinterface.gif "Explicit interface implementation")![Private method](media/privmethod.gif "Private method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/bb337648" target="_blank">_Attribute.Invoke</a></td><td>
Provides access to properties and methods exposed by an object.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e8kc3626" target="_blank">Attribute</a>.)</td></tr></table>&nbsp;
<a href="#descriptionattribute-class">Back to Top</a>

## See Also


#### Reference
<a href="N_TupleGeo_General_Attributes">TupleGeo.General.Attributes Namespace</a><br />