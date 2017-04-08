# Data Types
Rust is a staticlly type language!

Every value has a certain type in Rust!

Data type have two subsets: `scalar`, `compound`!

## Scalar type

### integer type
- 8bit: `i8/u8`
- 16bit: `i16/u16`
- 32bit: `i32/u32`
- 64bit: `i64/u64`
- arch: `isize/usize`(depend on computer architecture is 64 bit or 32 bit)

### integer literals demo
- decimal 98_222
- hex  0xff
- octal 0o77
- binary 0b1111_0000
- Byte b'a'

### float-point type

Have two types: `f64` -> 64 bits(default) and `f32` 32 bits

### boolean type
type `bool`:
- true
- false

```
let t = true;
let t: bool = false;
```
### characters type
type `char`

Char type represents a Unicode Scala Value.


## Compound Type

### Tuples
```
let tup: (i32, i8, f64, bool) = (1, 2, 1.1, false);
// tup.0 is 1
```

### Array
Rust will access index of array whether less than array length in runtime, In many low-level language, this kind of check is not done!

```
let arr = [1, 2, 3, 4];
let first = arr[0];
let second = arr[1];

```
