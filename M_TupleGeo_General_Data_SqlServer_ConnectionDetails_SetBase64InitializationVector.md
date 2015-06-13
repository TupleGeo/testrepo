# ConnectionDetails.SetBase64InitializationVector Method 
 

Sets the base64 initialization vector used to decrypt the password.

**Namespace:**&nbsp;<a href="N_TupleGeo_General_Data_SqlServer">TupleGeo.General.Data.SqlServer</a><br />**Assembly:**&nbsp;TupleGeo.General (in TupleGeo.General.dll) Version: 2.1.0.35959 (2.1.0)

## Syntax

**C#**<br />
``` C#
public void SetBase64InitializationVector(
	string base64InitializationVector
)
```


#### Parameters
&nbsp;<dl><dt>base64InitializationVector</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a><br />The base64 initialization vector.</dd></dl>

## Remarks
The initialization vector must be a base64 string used as an initialization vector feed for the <a href="T_TupleGeo_General_Security_CryptographicString">CryptographicString</a> object.

## See Also


#### Reference
<a href="T_TupleGeo_General_Data_SqlServer_ConnectionDetails">ConnectionDetails Class</a><br /><a href="N_TupleGeo_General_Data_SqlServer">TupleGeo.General.Data.SqlServer Namespace</a><br />