# Possible Errors in a Discovery Report

### dor_connection_error
There is a problem connecting to the Digital Object Repository. Try a second time; if still getting this error, contact the repository manager.
### dupes
The object has files with the same name; all files within an object must have unique file names. 
### empty_files
At least one file (found by walking the directory path for the object, recursively) is empty.
### empty_object
All the object's files are empty.
### filename_no_extension
At least one file (found by walking the directory path for the object, recursively) has no extension (the part after the last period in the filepath, e.g. pdf or jp2)
### item_not_registered
The object must already be registered.    
### missing_files
Each object must have at least one file, and all files for the object must be readable.
  - If using a file manifest, the files sought are from the manifest
  - If no file manifest, files are found by walking the directory path for the object, recursively.
  
## Errors That Only Occur When Using a File Manifest
### empty_manifest
There are no files in the manifest.
### files_found_mismatch
The number of files in the manifest does not match the number of files found by walking the directory path for the object, recursively.
### missing_media_container_name_or_manifest
The manifest file wasn't found.
