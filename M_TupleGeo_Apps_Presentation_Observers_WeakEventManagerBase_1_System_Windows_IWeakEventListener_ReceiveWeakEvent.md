# WeakEventManagerBase(*TEventArgs*).IWeakEventListener.ReceiveWeakEvent Method 
 

Receives events from the centralized event manager.

**Namespace:**&nbsp;<a href="N_TupleGeo_Apps_Presentation_Observers">TupleGeo.Apps.Presentation.Observers</a><br />**Assembly:**&nbsp;TupleGeo.Apps.Presentation (in TupleGeo.Apps.Presentation.dll) Version: 1.0.1.35961 (1.0.1)

## Syntax

**C#**<br />
``` C#
bool IWeakEventListener.ReceiveWeakEvent(
	Type managerType,
	Object sender,
	EventArgs e
)
```


#### Parameters
&nbsp;<dl><dt>managerType</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/42892f65" target="_blank">System.Type</a><br />The type of the WeakEventManager calling this method.</dd><dt>sender</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">System.Object</a><br />Object that originated the event.</dd><dt>e</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/118wxtk3" target="_blank">System.EventArgs</a><br />Event data.</dd></dl>

#### Return Value
Type: <a href="http://msdn2.microsoft.com/en-us/library/a28wyd50" target="_blank">Boolean</a><br />

#### Field Value
Type: <a href="http://msdn2.microsoft.com/en-us/library/a28wyd50" target="_blank">Boolean</a><br />true if the listener handled the event. It is considered an error by the WeakEventManager handling in WPF to register a listener for an event that the listener does not handle. Regardless, the method should return 

#### Field Value
Type: <a href="http://msdn2.microsoft.com/en-us/library/a28wyd50" target="_blank">Boolean</a><br />false if it receives an event that it does not recognize or handle.

#### Implements
<a href="http://msdn2.microsoft.com/en-us/library/ms557822" target="_blank">IWeakEventListener.ReceiveWeakEvent(Type, Object, EventArgs)</a><br />

## See Also


#### Reference
<a href="T_TupleGeo_Apps_Presentation_Observers_WeakEventManagerBase_1">WeakEventManagerBase(TEventArgs) Class</a><br /><a href="N_TupleGeo_Apps_Presentation_Observers">TupleGeo.Apps.Presentation.Observers Namespace</a><br />