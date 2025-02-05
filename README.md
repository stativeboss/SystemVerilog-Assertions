# SystemVerilog-Assertions
My notes on SVA course by Ashok Mehta

## Contents
- [Immediate Assertions](#immediate-assertions)
- [Concurrent Assertions](#concurrent-assertions)
  - [Basics](#basics)
    - [Sequence, Property, Assert and Cover, Implication Operator](#sequence-property-assert-and-cover-implication-operator)
    - [Vacuous Pass](#vacuous-pass)
    - [Clocking Basics](#clocking-basics)
    - [Multithreading, Formal Arguments, Disable Iff, and Severity Levels](#multithreading-formal-arguments-disable-iff-and-severity-levels)
    - [Binding Properties](#binding-properties)
  - [Sampled Value Functions](#sampled-value-functions)
    - [$rose and $fell](#rose-and-fell)
    - [$stable, $past, $changed, and $sampled](#stable-past-changed-and-sampled)
  - [Operators](#operators)
    - [Clock Delay Operator](#clock-delay-operator)
    - [Consecutive Repetition](#consecutive-repetition)
    - [Non-consecutive Repetition and Non-consecutive GoTo](#non-consecutive-repetition-and-non-consecutive-goto)
    - [`throughout` and `within`](#throughout-and-within)
    - [`and`, `or`, `intersect`](#and-or-intersect)
    - [`first match`, `if else`, `iff`, `implies`](#first-match-if-else-iff-implies)
- [System Functions and Tasks](#system-functions-and-tasks)
  - [$onehot, $onehot0, $isunknown, $countones, and Assertion Execution & Control Tasks](#onehot-onehot0-isunknown-countones-and-assertion-execution-control-tasks)
- [Multiply Clocked Properties and Sequences](#multiply-clocked-properties-and-sequences)
- [Local Variables and Endpoint Sequence Methods](#local-variables-and-endpoint-sequence-methods)
- [Misc](#misc)
  - [`expect`, `assume` Blocking `action block`](#expect-assume-blocking-action-block)
  - [Asynchronous FIFO Assertions](#asynchronous-fifo-assertions)
  - [Calling Subroutines, Sensitivity List, and Cyclic Dependency](#calling-subroutines-sensitivity-list-and-cyclic-dependency)
  - [Recursive Property](#recursive-property)
  - [Concurrent Assertions Fired from a Procedural Block](#concurrent-assertions-fired-from-a-procedural-block)
  - [`let` Declarations and `checker`](#let-declarations-and-checker)
  - [Checker's Legal and Illegal Conditions](#checkers-legal-and-illegal-conditions)
  - [Strong and Weak Properties, `always`, `eventually`, and `followed_by` Operators](#strong-and-weak-properties-always-eventually-and-followed_by-operators)
------------------------------------------------------------------------------------
## Immediate Assertions

## Concurrent Assertions

### Basics
#### Sequence, Property, Assert and Cover, Implication Operator
#### Vacuous Pass
#### Clocking Basics
#### Multithreading, Formal Arguments, Disable Iff, and Severity Levels
#### Binding Properties

### Sampled Value Functions
#### $rose and $fell
#### $stable, $past, $changed, and $sampled

### Operators
#### Clock Delay Operator
#### Consecutive Repetition
#### Non-consecutive Repetition and Non-consecutive GoTo
#### `throughout` and `within`
#### `and`, `or`, `intersect`
#### `first match`, `if else`, `iff`, `implies`

## System Functions and Tasks
### $onehot, $onehot0, $isunknown, $countones, and Assertion Execution Control Tasks

## Multiply Clocked Properties and Sequences

## Local Variables and Endpoint Sequence Methods

## Misc
### `expect`, `assume` Blocking `action block`
### Asynchronous FIFO Assertions
### Calling Subroutines, Sensitivity List, and Cyclic Dependency
### Recursive Property
### Concurrent Assertions Fired from a Procedural Block
### `let` Declarations and `checker`
### Checker's Legal and Illegal Conditions
### Strong and Weak Properties, `always`, `eventually`, and `followed_by` Operators
