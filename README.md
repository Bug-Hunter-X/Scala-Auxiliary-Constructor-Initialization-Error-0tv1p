# Scala Auxiliary Constructor Initialization Error

This repository demonstrates a common error in Scala related to the use of auxiliary constructors and default values. The example shows an incorrect implementation where a default value is not properly handled leading to unexpected behavior. The solution shows how to address this issue with proper initialization.

## Bug

The initial `MyClass` implementation uses an auxiliary constructor to provide a default value for `x`. However, if the primary constructor is called without explicitly providing a value for `x`, the value remains uninitialized, potentially causing issues later in the code.

## Solution

The solution showcases how to correctly initialize the value of `x` within the auxiliary constructor, ensuring it's always set to a defined value, irrespective of how the class is instantiated.
