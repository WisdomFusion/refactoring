# Refactoring. 重构。

## 0. 什么是重构？为什么重构？

重构。

## 1. 代码的“坏味道”

### Bloaters

- Long Method
- Large Class
- Primitive Obsession
- Long Parameter List
- Data Clumps

### Object-Orientation Abusers

- Switch Statements
- Temporary Field
- Refused Bequest
- Alternative Classes with Different Interfaces

### Change Preventers

- Divergent Change
- Shotgun Surgery
- Parallel Inheritance Hierarchies

### Dispensables

- Comments
- Duplicate Code
- Lazy Class
- Data Class
- Dead Code
- Speculative Generality

### Couplers

- Feature Envy
- Inappropriate Intimacy
- Message Chains
- Middle Man

### Other Smells

- Incomplete Library Class

## 3. 重构技术

### Composing Methods

- Extract Method
- Inline Method
- Extract Variable
- Inline Temp
- Replace Temp with Query
- Split Temporary Variable
- Remove Assignments to Parameters
- Replace Method with Method Object
- Substitute Algorithm

### Moving Features between Objects

- Move Method
- Move Field
- Extract Class
- Inline Class
- Hide Delegate
- Remove Middle Man
- Introduce Foreign Method
- Introduce Local Extension

### Organizing Data

- Self Encapsulate Field
- Replace Data Value with Object
- Change Value to Reference
- Change Reference to Value
- Replace Array with Object
- Duplicate Observed Data
- Change Unidirectional Association to Bidirectional
- Change Bidirectional Association to Unidirectional
- Replace Magic Number with Symbolic Constant

## 4. 大规模重构

- Tease Apart Inheritance
- Convert Procedure Design to Objects
- Separate Domain from Presentation
- Extract Hierarchy

## 5. 参考文档

- Refactorings http://refactoring.com/catalog/
- https://sourcemaking.com/refactoring

