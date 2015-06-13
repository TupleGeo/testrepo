# PropertyObserver(*TPropertySource*).UnregisterHandler Method 
 

Removes the callback associated with the specified property.

**Namespace:**&nbsp;<a href="N_TupleGeo_Apps_Presentation_Observers">TupleGeo.Apps.Presentation.Observers</a><br />**Assembly:**&nbsp;TupleGeo.Apps.Presentation (in TupleGeo.Apps.Presentation.dll) Version: 1.0.1.35961 (1.0.1)

## Syntax

**C#**<br />
``` C#
public PropertyObserver<TPropertySource> UnregisterHandler(
	Expression<Func<TPropertySource, Object>> expression
)
```


#### Parameters
&nbsp;<dl><dt>expression</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/bb335710" target="_blank">System.Linq.Expressions.Expression</a>(<a href="http://msdn2.microsoft.com/en-us/library/bb549151" target="_blank">Func</a>(<a href="T_TupleGeo_Apps_Presentation_Observers_PropertyObserver_1">*TPropertySource*</a>, <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>))<br />A lambda expression like 'n => n.PropertyName'.</dd></dl>

#### Return Value
Type: <a href="T_TupleGeo_Apps_Presentation_Observers_PropertyObserver_1">PropertyObserver</a>(<a href="T_TupleGeo_Apps_Presentation_Observers_PropertyObserver_1">*TPropertySource*</a>)<br />The object on which this method was invoked, to allow for multiple invocations chained together.

## See Also


#### Reference
<a href="T_TupleGeo_Apps_Presentation_Observers_PropertyObserver_1">PropertyObserver(TPropertySource) Class</a><br /><a href="N_TupleGeo_Apps_Presentation_Observers">TupleGeo.Apps.Presentation.Observers Namespace</a><br />