## Main Functionality

---

This extension make debugging much easier by automating the operation of writing meaningful log message.

Inspired from : https://github.com/Chakroun-Anas/turbo-console-log

## Features

---

I) Insert meaningful log message automatically

Two steps:

- Selecting the variable which is the subject of the debugging

- Pressing ctrl + alt + L

The log message will be inserted in the next line relative to the selected variable like this:

fmt.Println("SelectedVariableEnclosingClassName -> SelectedVariableEnclosingFunctionName -> SelectedVariable", SelectedVariable)

![alt text](https://image.ibb.co/dysw7p/insert_log_message.gif "Inserting meaningful log message after selecting a variable")

Multiple cursor supported.


Properties:

- turboConsoleLog.wrapLogMessage (boolean): Whether to wrap the log message or not.

- turboConsoleLog.logMessagePrefix (string): The prefix of the log message (default one is 🚀 ).

- turboConsoleLog.addSemicolonInTheEnd (boolean): Whether to put a semicolon in the end of the log message or not.

- turboConsoleLog.insertEnclosingClass (boolean): Whether to insert or not the enclosing class of the selected variable in the log message.

- turboConsoleLog.insertEnclosingFunction (boolean): Whether to insert or not the enclosing function of the selected variable in the log message.

- turboConsoleLog.delemiterInsideMessage (string): The delimiter that will separate the different log message elements (file name, line number, class, function and variable)

- turboConsoleLog.includeFileNameAndLineNum (boolean): Whether to include the file name and the line number of the log message.

- turboConsoleLog.quote (enum): Double quotes (""), single quotes ('') or backtick(``).

A wrapped log message :

![alt text](https://i.ibb.co/0cj4GnX/turbofmtprintln.gif "Wrapping The log message")

## Participate

---

You're more than welcome to participate in the development of the extension by creating pull requests and submitting issues, link of the project in github: https://github.com/sachinsmc/turbo-fmt-println


## License

---
Credit : https://github.com/Chakroun-Anas
---



**Enjoy!**
