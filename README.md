# Unexpected Memory Address in Uninitialized Variable

This Go program demonstrates a potential source of confusion for developers unfamiliar with Go's memory model: using an uninitialized variable.

## The Problem

Go does not automatically initialize variables. The output shows the memory address of the uninitialized `x` variable, which can lead to unexpected values being displayed and potentially incorrect program behavior.

## Solution

Always initialize variables before use to avoid undefined behavior and potential errors.
