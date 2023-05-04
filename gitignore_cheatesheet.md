| Pattern  |  Explanation | Examples |
| --------------------|------------------------------------------------------------------ | ----------------------------------------------------------------------- |
| name.file           | All files with the name.file will be ignored                     | /name.file, /lib/name.file                                              |
|                     | All blank lines are ignored                                       |                                                                         |
| name                | All names files, folders                                           | /name.log, /name/file.txt, /lib/name.log                                |
| name/               | Ending with / specifies the pattern is for a folder or file       | /name/file.txt, /name/log, /name.log                                    |
| /name.file          | Starting with / specifies the pattern matches only files in the root folder | /name.file                                            |
| lib/name.file       | Patterns specifying files in specific folders                     | /lib/name.file                                                          |
| **/lib/name.file    | Starting with ** before / specifies that it matches any folder in the repository | /lib/name.file, /test/lib/name.file                                    |
