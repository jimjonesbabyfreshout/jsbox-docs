> Console use and related interfaces

# Foreword

Any program will have bugs. This is the reason for the existence of'bug`. As a development platform, JSBox should provide various means of error checking. This is a direction that requires long-term optimization.

A simple Console (console) is introduced in JSBox, which can be used to output logs and execute some simple code.

# console

The 'console` object provides the following methods for outputting content to the console：

```js
console.info ("General Information")// Output General Information
console.warn ("Warning Message")// Output warning message
console.error ("Error Message")// Output error message
console.assert(false, "Message")     // Assertion
console.clear()// Clear the console
console.open()// open the console
console.close()// close the console
```

At the same time, the console also supports the execution of some code through the input box, and the execution results will also be displayed to the console.

In addition, when a JavaScript exception is captured, the exception information will be displayed to the console in the form of `error`.

# How to use the console

-Click the bug button on the interface to enter
-Click on a line to view the full text
-Long press a certain line to copy the content
-Enter the content in the input box at the bottom to debug the code
