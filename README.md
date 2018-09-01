# Historia-Log

Historia-Log is a Node.JS module that handles various logging tasks

### Basics
---

#### log.print(prefixes, msg)

Required:  
*prefixes* - An array of strings that will be color coded and displayed before the message  
*msg* - A string that will be displayed.

#### error.print(msg , code=0, err, tb=false)

Required:  
*msg* - A string that will be printed as a part of an error

Optional:  
*code* - A string or integer to be displayed to the right of the error header.  
*err* - An error object generated by a catch block
*tb* - A boolean value denoting whether a traceback will be printed

#### info.print(msg)
#### info.warn(msg)
#### info.success(msg)

Required:  
*msg* - A string that will be printed.

### Change Log
---

| Version  | Date  | Notes  |
|---|---|---|
| 0.1.0 | 08-31-2018 | Stylized console logging |
| 0.2.0 | 08-31-2018 | More styled printing presets |
|   |   | Stylized errors |
|   |   | Errors have optional tracebacks |
| 0.2.1 | 08-31-2018 | Bug fix |