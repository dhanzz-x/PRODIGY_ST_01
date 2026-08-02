# Task 01 - Manual Test Cases for Calculator

## Application

Simple Calculator

## Objective

To verify that all calculator functionalities work correctly under normal, boundary, and invalid conditions.

---

## Test Cases

## Module: Addition

---

### TC_001

**Test Case ID:** TC_001

**Test Description:**
Verify addition of two positive numbers.

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
30 should be displayed.

**Priority:** High

---

### TC_002

**Test Case ID:** TC_002

**Test Description:**
Verify addition of a positive and a negative number.

**Preconditions:**
Calculator application is open.

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

---

### TC_003

**Test Case ID:** TC_003

**Test Description:**
Verify addition of two negative numbers.

**Preconditions:**
Calculator application is open.

**Test Steps:**
1. Enter -10
2. Click +
3. Enter -15
4. Click =

**Test Data:**
-10 + (-15)

**Expected Result:**
-25 should be displayed.

**Priority:** High

---

### TC_004

**Test Case ID:** TC_004

**Test Description:**
Verify addition of decimal numbers.

**Preconditions:**
Calculator application is open.

**Test Steps:**
1. Enter 10.5
2. Click +
3. Enter 2.3
4. Click =

**Test Data:**
10.5 + 2.3

**Expected Result:**
12.8 should be displayed.

**Priority:** High

---

### TC_005

**Test Case ID:** TC_005

**Test Description:**
Verify addition with zero.

**Preconditions:**
Calculator application is open.

**Test Steps:**
1. Enter 25
2. Click +
3. Enter 0
4. Click =

**Test Data:**
25 + 0

**Expected Result:**
25 should be displayed.

**Priority:** Medium

---

### TC_006

**Test Case ID:** TC_006

**Test Description:**
Verify addition of very large numbers.

**Preconditions:**
Calculator application is open.

**Test Steps:**
1. Enter a very large number.
2. Click +
3. Enter another very large number.
4. Click =

**Test Data:**
999999999999 + 999999999999

**Expected Result:**
The calculator should correctly display the result or display it in scientific notation if supported.

**Priority:** Medium
