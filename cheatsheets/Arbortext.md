 # Arbortext #

### Keyboard Shortcuts ###

| Command  | Purpose |
| :---------------- | :----------------|
| `Alt + E + V + E` | Open R.D.E. |
| `Alt + I + E`     | Edit Selection as XML Source |
| `Alt + N + T`     | Find Tag/Attribute |
| `Alt + N + B`     | Find/Replace Attribute |
| `Ctrl + Alt + M`  | Insert Comment |

### ACL Commands ###
| Command  | Purpose |
| :-------------------------- | :----------- | 
| `edit -current -untag` | (-untag) Disables/Enables displaying the entire doc as raw XML |
| `set protection=none` | Enable/Disable element protection, as defined by DCF |

### Troubleshooting ACL Commands ###
| Command  | Purpose |
| :-------------------------- | :----------- |
| `eval doc_type_file()`      | displays path to DTD/Schema of current document |
| `eval doc_type_dcf_file()`  | displays the path of the document type configuration file for the current doctype |
|                     |                                         |
| `eval option(loadpath)`     | displays paths of the current Applications loaded in Editor|
| `eval option(libpath)`      | displays the the currently loaded library paths |
| `eval option(catalogpath)`  | displays the paths of the currenly loaded catalog files |
|                             |                                                 |
| `eval $ENV[APTAPPLICATION]` | displays the current value of the **APTAPPLICATION** Environment Variable| 
| `eval $ENV[APTCUSTOM]`	  | displays the current value of the **APTAPPLICATION** Environment Variable |

### Doctype Declarations ###

| Doctype | Declaration |
|  ------   | ------    | 
| Ditabase |`<!DOCTYPE topic PUBLIC "-//OASIS//DTD DITA Composite//EN" "ditabase.dtd">`|
| Concept |`<!DOCTYPE topic PUBLIC "-//OASIS//DTD DITA Concept//EN" "concept.dtd">`|
| Bookmap |`<!DOCTYPE topic PUBLIC "-//OASIS//DTD DITA BookMap//EN" "bookmap.dtd">`|
| Task |`<!DOCTYPE topic PUBLIC "-//OASIS//DTD DITA Task//EN" "task.dtd">`|
| TechInfoMap | `<techinfomap ... xsi:noNamespaceSchemaLocation="urn:ptc:names:arbortext:dita:xsd:techinfomap.xsd` |
| TechInfo Concept | `<concept ... xsi:noNamespaceSchemaLocation="urn:ptc:names:arbortext:dita:xsd:techinfo.xsd>` |
| TechInfo Task | `<task ... xsi:noNamespaceSchemaLocation="urn:ptc:names:arbortext:dita:xsd:techinfo.xsd>`|
 


----

Compiled by [Jesse Lambert](https://github.com/indepic).