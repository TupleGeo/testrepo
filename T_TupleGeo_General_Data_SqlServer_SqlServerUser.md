# SqlServerUser Class
 

Defines an SQL Server user as it appears in a connection string.


## Inheritance Hierarchy
<a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">System.Object</a><br />&nbsp;&nbsp;TupleGeo.General.Data.SqlServer.SqlServerUser<br />
**Namespace:**&nbsp;<a href="N_TupleGeo_General_Data_SqlServer">TupleGeo.General.Data.SqlServer</a><br />**Assembly:**&nbsp;TupleGeo.General (in TupleGeo.General.dll) Version: 2.1.0.35959 (2.1.0)

## Syntax

**C#**<br />
``` C#
[SerializableAttribute]
[XmlRootAttribute(Namespace = "urn:TupleGeo:General:Data:SqlServer", 
	IsNullable = false)]
[XmlTypeAttribute(AnonymousType = false)]
public sealed class SqlServerUser
```

The SqlServerUser type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_TupleGeo_General_Data_SqlServer_SqlServerUser__ctor">SqlServerUser</a></td><td>
Initializes a new instance of the SqlServerUser class</td></tr></table>&nbsp;
<a href="#sqlserveruser-class">Back to Top</a>

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
<a href="#sqlserveruser-class">Back to Top</a>

## Extension Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_TupleGeo_General_ObjectExtensions_GetPropertyValueString">GetPropertyValueString</a></td><td>
Gets a <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">String</a> representation of the value of a specified property of an object.
 (Defined by <a href="T_TupleGeo_General_ObjectExtensions">ObjectExtensions</a>.)</td></tr></table>&nbsp;
<a href="#sqlserveruser-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_TupleGeo_General_Data_SqlServer_SqlServerUser_IsPasswordEncrypted">IsPasswordEncrypted</a></td><td>
Gets / Sets whether the password of the user is encrypted or not.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_TupleGeo_General_Data_SqlServer_SqlServerUser_IsPasswordPersisted">IsPasswordPersisted</a></td><td>
Gets / Sets whether the password of the user is persisted or not.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_TupleGeo_General_Data_SqlServer_SqlServerUser_Password">Password</a></td><td>
Gets / Sets the password.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_TupleGeo_General_Data_SqlServer_SqlServerUser_UserName">UserName</a></td><td>
Gets / Sets the username.</td></tr></table>&nbsp;
<a href="#sqlserveruser-class">Back to Top</a>

## See Also


#### Reference
<a href="N_TupleGeo_General_Data_SqlServer">TupleGeo.General.Data.SqlServer Namespace</a><br />