# AssemblyExtensions.CreateInstance Method 
 

Creates an instance of an object implementing the specified interface type.

**Namespace:**&nbsp;<a href="N_TupleGeo_General_Reflection">TupleGeo.General.Reflection</a><br />**Assembly:**&nbsp;TupleGeo.General (in TupleGeo.General.dll) Version: 2.1.0.35959 (2.1.0)

## Syntax

**C#**<br />
``` C#
public static Object CreateInstance(
	this Assembly assembly,
	Type interfaceType
)
```


#### Parameters
&nbsp;<dl><dt>assembly</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/xbe1wdx9" target="_blank">System.Reflection.Assembly</a><br />The <a href="http://msdn2.microsoft.com/en-us/library/xbe1wdx9" target="_blank">Assembly</a>.</dd><dt>interfaceType</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/42892f65" target="_blank">System.Type</a><br />The <a href="http://msdn2.microsoft.com/en-us/library/42892f65" target="_blank">Type</a> of interface implemented by the object to be instantiated.</dd></dl>

#### Return Value
Type: <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a><br />An <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a> instance implementing the specified interface.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type <a href="http://msdn2.microsoft.com/en-us/library/xbe1wdx9" target="_blank">Assembly</a>. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="http://msdn.microsoft.com/en-us/library/bb384936.aspx">Extension Methods (Visual Basic)</a> or <a href="http://msdn.microsoft.com/en-us/library/bb383977.aspx">Extension Methods (C# Programming Guide)</a>.

## Remarks
The method expects only one of the exported types to implement this interface. In case there are more exported types implementing this interface the method will return null and raise an error.

## See Also


#### Reference
<a href="T_TupleGeo_General_Reflection_AssemblyExtensions">AssemblyExtensions Class</a><br /><a href="N_TupleGeo_General_Reflection">TupleGeo.General.Reflection Namespace</a><br />