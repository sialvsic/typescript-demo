### 1.Basic Types
- Boolean
- Number
- String
- Array: two ways to declare
    1. `string[]`
    2. `Array<string>`
- Tuple:demo1
- Enum:two types of enum value: number(auto-incremented) and string
- Any
- Void
- Null,Undefined
- Never
- Object

### 2.Variable Declarations
- pay attention to set type or give default value:demo2

### 3.Interfaces
- demo3:to have any number of properties

### 4.Classes
- demo4:Abstract Classes
- public,private,protected modifiers
- demo5:constructor param modifiers

### 5.Generics
- Generic Type Variables
    - Generic functions:demo6,
    - Generic Constraints:demo7
 
### 6.Advanced Types
- Intersection Types:an object of this type will have all members of all types.- demo8
- Union Types:only access common members to all types in the union - demo9
- String Literal Types:demo10
- Index types:index type query(keyof T) and indexed access operators(T[K])--demo11

- Type Aliases:
    - differences between Aliases and interface:demo12
    - if you can’t express some shape with an interface and you need to use a union or tuple type, type aliases are usually the way to go.
    