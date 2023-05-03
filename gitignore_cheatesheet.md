

| Pattern  | Explanation/Matches | Examples |
| -------- | ------------------- | -------- |
| name.file| All files with the name.file will be ignored | /name.file /lib/name.file
|name | All name files, name folders, and files and folders in any name folder | /name.log /name/file.txt /lib/name.
|*.file | All files withe .file extention |	/name.file /lib/name.file
|**/name | 	All name folders, and files and folders in any name folder |  /name/log.file /lib/name/log.file /name/lib/log.file
|name?.file |	? matches a single non-specific character |	/names.file /name1.file /names1.file