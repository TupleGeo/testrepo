# ObservableObject(*T*) Class
 

An object that is observed by other objects for value changes in its properties.


## Inheritance Hierarchy
<a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">System.Object</a><br />&nbsp;&nbsp;TupleGeo.General.ComponentModel.ObservableObject(T)<br />&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_TupleGeo_Apps_Presentation_BaseViewModel_1">TupleGeo.Apps.Presentation.BaseViewModel(T)</a><br />&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_TupleGeo_General_Windows_Data_Filter">TupleGeo.General.Windows.Data.Filter</a><br />
**Namespace:**&nbsp;<a href="N_TupleGeo_General_ComponentModel">TupleGeo.General.ComponentModel</a><br />**Assembly:**&nbsp;TupleGeo.General (in TupleGeo.General.dll) Version: 2.1.0.35959 (2.1.0)

## Syntax

**C#**<br />
``` C#
public abstract class ObservableObject<T> : INotifyPropertyChanged

```


#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>Any object need to be observed.</dd></dl>&nbsp;
The ObservableObject(T) type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Protected method](media/protmethod.gif "Protected method")</td><td><a href="M_TupleGeo_General_ComponentModel_ObservableObject_1__ctor">ObservableObject(T)</a></td><td>
Initializes a new instance of the ObservableObject(T) class</td></tr></table>&nbsp;
<a href="#observableobject(*t*)-class">Back to Top</a>

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
Executed when a property changes.</td></tr><tr><td>![Protected method](media/protmethod.gif "Protected method")</td><td><a href="M_TupleGeo_General_ComponentModel_ObservableObject_1_OnPropertyChanged_1">OnPropertyChanged(String)</a></td><td>
Called when [property changed].</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/7bxwbwt2" target="_blank">ToString</a></td><td>
Returns a string that represents the current object.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr></table>&nbsp;
<a href="#observableobject(*t*)-class">Back to Top</a>

## Extension Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_TupleGeo_General_ObjectExtensions_GetPropertyValueString">GetPropertyValueString</a></td><td>
Gets a <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">String</a> representation of the value of a specified property of an object.
 (Defined by <a href="T_TupleGeo_General_ObjectExtensions">ObjectExtensions</a>.)</td></tr></table>&nbsp;
<a href="#observableobject(*t*)-class">Back to Top</a>

## Events
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_TupleGeo_General_ComponentModel_ObservableObject_1_PropertyChanged">PropertyChanged</a></td><td>
Occurs when a property value changes.</td></tr></table>&nbsp;
<a href="#observableobject(*t*)-class">Back to Top</a>

## See Also


#### Reference
<a href="N_TupleGeo_General_ComponentModel">TupleGeo.General.ComponentModel Namespace</a><br />