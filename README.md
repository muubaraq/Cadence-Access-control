# SomeContract Readme
This readme provides a comprehensive overview of the "SomeContract" smart contract, written in the Move programming language. The contract includes a struct, a resource, and various functions, showcasing the use of different access modifiers to control visibility and accessibility.

### Contract Overview
The "SomeContract" smart contract comprises the following key elements:

### SomeStruct
- Definition: SomeStruct is a struct within the contract, encompassing four variables and three functions.

#### Variables:
a, b, c, and d are defined within SomeStruct, each with distinct access modifiers and scopes.

#### Functions:
SomeStruct includes publicFunc, contractFunc, and privateFunc, each callable from different areas and having specific access modifiers.

#### SomeResource
Definition: SomeResource is a resource type within the contract, consisting of a variable e and a function resourceFunc.

#### Variable:
e has a specific access scope within the contract.

#### Function:
resourceFunc can be called from a specific area, demonstrating controlled accessibility.
Functions
The contract defines three top-level functions:

#### createSomeResource:
Creates a new SomeResource resource and returns it.

#### questsAreFun:
A simple function with a specific area designated for execution.

#### init:
The constructor function initializes the contract and creates an instance of SomeStruct as testStruct.

#### Variable and Function Scopes
The comments at the end of the contract provide a detailed breakdown of variable and function scopes:

#### Variables
- a: Read and written from areas 1, 2, 3, and 4.
- b: Read from areas 1, 2, 3, and 4; written only from area 1.
- c: Read from areas 1, 2, and 3; written from area 1.
- d: Read and written from area 1.
- e: Read from areas 1, 2, 3, and 4; written only from area 2.

#### Functions
- publicFunc: Callable from areas 1, 2, 3, and 4.
- contractFunc: Callable from areas 1, 2, and 3.
- privateFunc: Callable from area 1.

#### Areas
Different areas within the contract:

- Area 1: Main contract scope.
- Area 2: Scope of SomeResource functions and variables.
- Area 3: Specific section or scope within functions.
- Area 4: Main contract scope (same as Area 1).
These areas help understand where variables and functions can be accessed and utilized within the contract, ensuring controlled and secure interactions.