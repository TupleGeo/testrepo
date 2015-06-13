# ConnectionDetails.FromConnectionString Method (String, String, String)
 

Updates the connection details using a connection string.

**Namespace:**&nbsp;<a href="N_TupleGeo_General_Data_SqlServer">TupleGeo.General.Data.SqlServer</a><br />**Assembly:**&nbsp;TupleGeo.General (in TupleGeo.General.dll) Version: 2.1.0.35959 (2.1.0)

## Syntax

**C#**<br />
``` C#
public void FromConnectionString(
	string connectionString,
	string base64Key,
	string base64InitializationVector
)
```


#### Parameters
&nbsp;<dl><dt>connectionString</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a><br />The connection string used to updated the ConnectionDetails object.</dd><dt>base64Key</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a><br />The base64 key used for encrypting passwords.</dd><dt>base64InitializationVector</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a><br />The base64 initialization vector used for encrypting passwords.</dd></dl>

## Remarks
The method assumes that the password will be encrypted.

## See Also


#### Reference
<a href="T_TupleGeo_General_Data_SqlServer_ConnectionDetails">ConnectionDetails Class</a><br /><a href="Overload_TupleGeo_General_Data_SqlServer_ConnectionDetails_FromConnectionString">FromConnectionString Overload</a><br /><a href="N_TupleGeo_General_Data_SqlServer">TupleGeo.General.Data.SqlServer Namespace</a><br />