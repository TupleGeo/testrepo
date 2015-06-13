# ConnectionDetails.SetPassword Method 
 

Sets the password.

**Namespace:**&nbsp;<a href="N_TupleGeo_General_Data_SqlServer">TupleGeo.General.Data.SqlServer</a><br />**Assembly:**&nbsp;TupleGeo.General (in TupleGeo.General.dll) Version: 2.1.0.35959 (2.1.0)

## Syntax

**C#**<br />
``` C#
private void SetPassword(
	bool encryptPassword,
	ref string password,
	string[] tokens,
	ref IEnumerable<string> dataSourceTokens
)
```


#### Parameters
&nbsp;<dl><dt>encryptPassword</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/a28wyd50" target="_blank">System.Boolean</a><br />Indicates whether to encrypt the password or not.</dd><dt>password</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a><br />The password.</dd><dt>tokens</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a>[]<br />The connection string tokens.</dd><dt>dataSourceTokens</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/9eekhta0" target="_blank">System.Collections.Generic.IEnumerable</a>(<a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">String</a>)<br />The data source tokens.</dd></dl>

## See Also


#### Reference
<a href="T_TupleGeo_General_Data_SqlServer_ConnectionDetails">ConnectionDetails Class</a><br /><a href="N_TupleGeo_General_Data_SqlServer">TupleGeo.General.Data.SqlServer Namespace</a><br />