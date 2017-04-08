# Function

## Code Style

Rust code uses snake case for function names and variable names.

`main` is key word as entry point of program.

## function define

```
fn function_1() {
    println!("hello, world!");
}

fn function_2(x: u32, y: bool) {
    println!("x: {}, y {}", x, y);
}

fn function_3(x: u32) -> u32 {
    //return x value.
    //The return value of function is synonymous with the value of
    //final expression in the block of the body of a function.
    // NOTE: No semicolon!
    x
}
```

## Statements and Expressions

Statements are instruction that perform some action and do not return a value

statements demo:

```
let x = 6;
```

Expressions evalute resulting value, such as calling  a function, calling a macro and a code block etc.

expressions demo

```
let x = {
 let y = 1;
 y + 1
}
```


