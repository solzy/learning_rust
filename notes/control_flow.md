# Control Flow

Rust has many futures of functional languages, the control flow of the Rust is affected!

## `if` 

```
let x = 1;
// the condition must be a bool value
if x == 0 {
    println!("Can not reach there!");
} else {
    println!("OK");
}

```

## `if - else if`

```
let x = 10;
if x % 5 == 0 {
    println!("number is divisiable by 5!");
} else if x % 10 == 0 {
    println!("number is divisiable by 10!");
} else {
    println!("number is not divisiable by 5/10!");
}

```

## `if` with `let`

```
let x = 10;
//NOTE: Need semicolon at last of the code block 
let is_ok = if x % 10 {
    true
} else {
    false
};

```

## `loop` vs `while` vs `for`

```
loop {
    println!("loop infinite!");
}

let x = 10;
while x == 10 {
    println!("loop infinite!");
}

let a = [1, 2, 3];
for element in a.iter() {
    println!("list element:{}!", element);
}

//reverse the range
for i in (1..4).rev() {
    println!("reverse element:{}!", element);
}

```



