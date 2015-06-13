# PathsUtility.GetParentPath Method 
 

Gets the parent path from a given path.

**Namespace:**&nbsp;<a href="N_TupleGeo_General_FileSystem">TupleGeo.General.FileSystem</a><br />**Assembly:**&nbsp;TupleGeo.General (in TupleGeo.General.dll) Version: 2.1.0.35959 (2.1.0)

## Syntax

**C#**<br />
``` C#
public static string GetParentPath(
	string path
)
```


#### Parameters
&nbsp;<dl><dt>path</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a><br />The path to get its parent.</dd></dl>

#### Return Value
Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">String</a><br />A <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">String</a> storing the parent path.

## Remarks
In case the path is the full path to a file, the path returned is that storing the file.

## See Also


#### Reference
<a href="T_TupleGeo_General_FileSystem_PathsUtility">PathsUtility Class</a><br /><a href="N_TupleGeo_General_FileSystem">TupleGeo.General.FileSystem Namespace</a><br />