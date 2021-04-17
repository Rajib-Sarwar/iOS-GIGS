# iOS Interview School

## Table of Contents

- [What is let and var in Swift?](#what-is-let-and-var-in-swift)
- [What is optional and nil in Swift?](#what-is-optional-and-nil-in-swift)


---

## What is let and var in Swift and Objective C?
Swift: 
<br>The `let` keyword is used to declare a constant and the `var` keyword is used to declare a variable. Variables created with these either references, pointers or values. Difference between them is that when you create a variable using `let` it will become constant upon declaration and it can not be modified or reassigned later. In contrast, a varible with `var` can be assigned right away or later or noty at all. In swift, you have to be very explicit about what you are declaring. 

Objective C: 
<br>In Objective C everything is `dynamic` and can be `nil`. Also, `nil` can receive messages without breaking everything i.e. throwing an exception.


## What is optional and nil in Swift?
In swift `optional` is defined with `?` and appended at the end of variable type on declare. `Optional` variables an be assigned with a value right away or at later time or not set one at all. When you use the `optional` variables you have to either explicitly unwrap them using `!` appended at the end of variables you have used to get the value stored in it, which is not safe because the app will shutdown unexpectedly if it found `nil` while unwrapping. 

Or, you can do a `Optional Binding` to find out whether an optional variable contains a value. For example,
<br><br>
`if let unwrappingOptional = someOptional {`<br>
    `//your code here`<br>
 `}`
 
 
