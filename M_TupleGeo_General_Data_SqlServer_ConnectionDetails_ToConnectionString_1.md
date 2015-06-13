# ConnectionDetails.ToConnectionString Method (String, String, String)
 

Converts the connection Details in to an SQL Server connection string.

**Namespace:**&nbsp;<a href="N_TupleGeo_General_Data_SqlServer">TupleGeo.General.Data.SqlServer</a><br />**Assembly:**&nbsp;TupleGeo.General (in TupleGeo.General.dll) Version: 2.1.0.35959 (2.1.0)

## Syntax

**C#**<br />
``` C#
public string ToConnectionString(
	string user,
	string base64Key,
	string base64InitializationVector
)
```


#### Parameters
&nbsp;<dl><dt>user</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a><br />The username that will be used to form the connection string.</dd><dt>base64Key</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a><br />The base64 key used for encrypting passwords.</dd><dt>base64InitializationVector</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a><br />The base64 initialization vector used for encrypting passwords.</dd></dl>

#### Return Value
Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">String</a><br />A <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">String</a>containing the SQL Server connection string.

## Remarks
In case the <a href="P_TupleGeo_General_Data_SqlServer_ConnectionDetails_SqlServerUserCollection">SqlServerUserCollection</a> property is populated with users having encrypted passwords a call to methods <a href="M_TupleGeo_General_Data_SqlServer_ConnectionDetails_SetBase64Key">SetBase64Key(String)</a> and <a href="M_TupleGeo_General_Data_SqlServer_ConnectionDetails_SetBase64InitializationVector">SetBase64InitializationVector(String)</a> must be made first in order for this method to succeed returning a connection string.

## See Also


#### Reference
<a href="T_TupleGeo_General_Data_SqlServer_ConnectionDetails">ConnectionDetails Class</a><br /><a href="Overload_TupleGeo_General_Data_SqlServer_ConnectionDetails_ToConnectionString">ToConnectionString Overload</a><br /><a href="N_TupleGeo_General_Data_SqlServer">TupleGeo.General.Data.SqlServer Namespace</a><br />