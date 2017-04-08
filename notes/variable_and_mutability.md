## immutable variable vs mutable
```
let a = 1;
let mut b = 1
```

## immutable variable vs contants 

- const
`const MAX_POINT: u32 = 100_00`
- let 
`let immutable_value = 100`

## immutable variable vs shadowing
```
//execute ok
let a = "shadowing"
b = 2
```

```
//execute Error
a = 2
a = "re-assignment value"
b = "mutable variable can not assign value of different type"
```


