# Task 01 - Manual Test Cases for Calculator

## Application

Simple Calculator

## Objective

To verify that all calculator functionalities work correctly under normal, boundary, and invalid conditions.

---

## Test Cases
### TC_001

**Test Scenario:** Verify addition of two positive numbers

**Preconditions:**
Calculator application is open.

**Test Steps:**
1. Enter 10
2. Click +
3. Enter 20
4. Click =

**Test Data:**
10 + 20

**Expected Result:**

### TC_002

**Test Scenario:** Verify addition of a positive and a negative number

**Preconditions:**
Calculator is open.

**Test Steps:**
1. Enter 15
2. Click +
3. Enter -5
4. Click =

**Test Data:**
15 + (-5)

**Expected Result:**
10 should be displayed.

**Priority:** High

### TC_003

**Test Scenario:** Verify addition of two negative numbers

**Test Data:**
-10 + -15

**Expected Result:**
-25

### TC_004

**Test Scenario:** Verify decimal addition

**Test Data:**
10.5 + 2.3

**Expected Result:**
12.8

### TC_005

**Test Scenario:** Verify addition with zero

**Test Data:**
25 + 0

**Expected Result:**
25

### TC_006

**Test Scenario:** Verify addition of very large numbers

**Test Data:**
999999999999 + 999999999999

**Expected Result:**
Calculator should correctly display the result or use scientific notation if supported.
30 should be displayed.

**Priority:** High
