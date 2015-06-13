# Filter Class
 

The object used to define a filter capable to be used in a CollectionViewsource for filtering rows.


## Inheritance Hierarchy
<a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">System.Object</a><br />&nbsp;&nbsp;<a href="T_TupleGeo_General_ComponentModel_ObservableObject_1">TupleGeo.General.ComponentModel.ObservableObject</a>(Filter)<br />&nbsp;&nbsp;&nbsp;&nbsp;TupleGeo.General.Windows.Data.Filter<br />
**Namespace:**&nbsp;<a href="N_TupleGeo_General_Windows_Data">TupleGeo.General.Windows.Data</a><br />**Assembly:**&nbsp;TupleGeo.General.Windows.Presentation (in TupleGeo.General.Windows.Presentation.dll) Version: 1.0.1.35963 (1.0.1)

## Syntax

**C#**<br />
``` C#
public sealed class Filter : ObservableObject<Filter>
```

The Filter type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_TupleGeo_General_Windows_Data_Filter__ctor">Filter</a></td><td>
Initializes a new instance of the Filter class</td></tr></table>&nbsp;
<a href="#filter-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/bsc2ak47" target="_blank">Equals</a></td><td>
Determines whether the specified object is equal to the current object.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Protected method](media/protmethod.gif "Protected method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/4k87zsw7" target="_blank">Finalize</a></td><td>
Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/zdee4b3y" target="_blank">GetHashCode</a></td><td>
Serves as a hash function for a particular type.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/dfwy45w9" target="_blank">GetType</a></td><td>
Gets the <a href="http://msdn2.microsoft.com/en-us/library/42892f65" target="_blank">Type</a> of the current instance.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Protected method](media/protmethod.gif "Protected method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/57ctke0a" target="_blank">MemberwiseClone</a></td><td>
Creates a shallow copy of the current <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Protected method](media/protmethod.gif "Protected method")</td><td><a href="M_TupleGeo_General_ComponentModel_ObservableObject_1_OnPropertyChanged">OnPropertyChanged(Expression(Func(T, Object)))</a></td><td>
Executed when a property changes.
 (Inherited from <a href="T_TupleGeo_General_ComponentModel_ObservableObject_1">ObservableObject(T)</a>.)</td></tr><tr><td>![Protected method](media/protmethod.gif "Protected method")</td><td><a href="M_TupleGeo_General_ComponentModel_ObservableObject_1_OnPropertyChanged_1">OnPropertyChanged(String)</a></td><td>
Called when [property changed].
 (Inherited from <a href="T_TupleGeo_General_ComponentModel_ObservableObject_1">ObservableObject(T)</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/7bxwbwt2" target="_blank">ToString</a></td><td>
Returns a string that represents the current object.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr></table>&nbsp;
<a href="#filter-class">Back to Top</a>

## Extension Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_TupleGeo_General_ObjectExtensions_GetPropertyValueString">GetPropertyValueString</a></td><td>
Gets a <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">String</a> representation of the value of a specified property of an object.
 (Defined by <a href="T_TupleGeo_General_ObjectExtensions">ObjectExtensions</a>.)</td></tr></table>&nbsp;
<a href="#filter-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_TupleGeo_General_Windows_Data_Filter_Callback">Callback</a></td><td>
Gets / Sets the callback function used to perform the filtering action.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_TupleGeo_General_Windows_Data_Filter_Description">Description</a></td><td>
Gets / Sets the filter description.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_TupleGeo_General_Windows_Data_Filter_Id">Id</a></td><td>
Gets / Sets the id of the filter.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_TupleGeo_General_Windows_Data_Filter_Name">Name</a></td><td>
Gets / Sets the filter name.</td></tr></table>&nbsp;
<a href="#filter-class">Back to Top</a>

## Events
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_TupleGeo_General_ComponentModel_ObservableObject_1_PropertyChanged">PropertyChanged</a></td><td>
Occurs when a property value changes.
 (Inherited from <a href="T_TupleGeo_General_ComponentModel_ObservableObject_1">ObservableObject(T)</a>.)</td></tr></table>&nbsp;
<a href="#filter-class">Back to Top</a>

## See Also


#### Reference
<a href="N_TupleGeo_General_Windows_Data">TupleGeo.General.Windows.Data Namespace</a><br />