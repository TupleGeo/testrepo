# WeakEventManagerBase(*TEventArgs*) Class
 

The base class for a WeakEventManager.


## Inheritance Hierarchy
<a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">System.Object</a><br />&nbsp;&nbsp;TupleGeo.Apps.Presentation.Observers.WeakEventManagerBase(TEventArgs)<br />
**Namespace:**&nbsp;<a href="N_TupleGeo_Apps_Presentation_Observers">TupleGeo.Apps.Presentation.Observers</a><br />**Assembly:**&nbsp;TupleGeo.Apps.Presentation (in TupleGeo.Apps.Presentation.dll) Version: 1.0.1.35961 (1.0.1)

## Syntax

**C#**<br />
``` C#
public sealed class WeakEventManagerBase<TEventArgs> : IWeakEventListener
where TEventArgs : EventArgs

```


#### Type Parameters
&nbsp;<dl><dt>TEventArgs</dt><dd>The event arguments.</dd></dl>&nbsp;
The WeakEventManagerBase(TEventArgs) type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_TupleGeo_Apps_Presentation_Observers_WeakEventManagerBase_1__ctor">WeakEventManagerBase(TEventArgs)</a></td><td>
Initializes a new instance of the WeakEventManagerBase(TEventArgs).</td></tr></table>&nbsp;
<a href="#weakeventmanagerbase(*teventargs*)-class">Back to Top</a>

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
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/7bxwbwt2" target="_blank">ToString</a></td><td>
Returns a string that represents the current object.
 (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr></table>&nbsp;
<a href="#weakeventmanagerbase(*teventargs*)-class">Back to Top</a>

## Extension Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_TupleGeo_General_ObjectExtensions_GetPropertyValueString">GetPropertyValueString</a></td><td>
Gets a <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">String</a> representation of the value of a specified property of an object.
 (Defined by <a href="T_TupleGeo_General_ObjectExtensions">ObjectExtensions</a>.)</td></tr></table>&nbsp;
<a href="#weakeventmanagerbase(*teventargs*)-class">Back to Top</a>

## Explicit Interface Implementations
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Explicit interface implementation](media/pubinterface.gif "Explicit interface implementation")![Private method](media/privmethod.gif "Private method")</td><td><a href="M_TupleGeo_Apps_Presentation_Observers_WeakEventManagerBase_1_System_Windows_IWeakEventListener_ReceiveWeakEvent">IWeakEventListener.ReceiveWeakEvent</a></td><td>
Receives events from the centralized event manager.</td></tr></table>&nbsp;
<a href="#weakeventmanagerbase(*teventargs*)-class">Back to Top</a>

## See Also


#### Reference
<a href="N_TupleGeo_Apps_Presentation_Observers">TupleGeo.Apps.Presentation.Observers Namespace</a><br />