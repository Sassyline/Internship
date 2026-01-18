# Task-01: Test Cases for Simple Calculator Applications (Updated Values)

## Addition – Test Cases

### Test Case Id:

**TC_001**

**Test Description:**
Verify addition of two positive numbers

**Precondition:**
Calculator application is opened

**Test Steps:**

1. Enter 25
2. Click `+`
3. Enter 14
4. Click `=`

**Expected Result:**
Result should be **39**

---

### Test Case Id:

**TC_002**

**Test Description:**
Verify addition of two negative numbers

**Precondition:**
Calculator application is opened

**Test Steps:**

1. Enter -22
2. Click `+`
3. Enter -13
4. Click `=`

**Expected Result:**
Result should be **-35**

---

### Test Case Id:

**TC_003**

**Test Description:**
Verify addition of decimal numbers

**Precondition:**
Calculator application is opened

**Test Steps:**

1. Enter 4.75
2. Click `+`
3. Enter 2.25
4. Click `=`

**Expected Result:**
Result should be **7.0**

---

## Subtraction – Test Cases

### Test Case Id:

**TC_004**

**Test Description:**
Verify subtraction of two positive numbers

**Precondition:**
Calculator application is opened

**Test Steps:**

1. Enter 50
2. Click `-`
3. Enter 18
4. Click `=`

**Expected Result:**
Result should be **32**

---

### Test Case Id:

**TC_005**

**Test Description:**
Verify subtraction resulting in negative value

**Precondition:**
Calculator application is opened

**Test Steps:**

1. Enter 9
2. Click `-`
3. Enter 21
4. Click `=`

**Expected Result:**
Result should be **-12**

---

## Multiplication – Test Cases

### Test Case Id:

**TC_006**

**Test Description:**
Verify multiplication of two numbers

**Precondition:**
Calculator application is opened

**Test Steps:**

1. Enter 6
2. Click `*`
3. Enter 9
4. Click `=`

**Expected Result:**
Result should be **54**

---

### Test Case Id:

**TC_007**

**Test Description:**
Verify multiplication with zero

**Precondition:**
Calculator application is opened

**Test Steps:**

1. Enter 45
2. Click `*`
3. Enter 0
4. Click `=`

**Expected Result:**
Result should be **0**

---

### Test Case Id:

**TC_008**

**Test Description:**
Verify multiplication of decimal numbers

**Precondition:**
Calculator application is opened

**Test Steps:**

1. Enter 3.2
2. Click `*`
3. Enter 2.5
4. Click `=`

**Expected Result:**
Result should be **8.0**

---

## Division – Test Cases

### Test Case Id:

**TC_009**

**Test Description:**
Verify division of two positive numbers

**Precondition:**
Calculator application is opened

**Test Steps:**

1. Enter 64
2. Click `/`
3. Enter 8
4. Click `=`

**Expected Result:**
Result should be **8**

---

### Test Case Id:

**TC_010**

**Test Description:**
Verify division resulting in decimal value

**Precondition:**
Calculator application is opened

**Test Steps:**

1. Enter 9
2. Click `/`
3. Enter 5
4. Click `=`

**Expected Result:**
Result should be **1.8**

---

### Test Case Id:

**TC_011**

**Test Description:**
Verify division by zero

**Precondition:**
Calculator application is opened

**Test Steps:**

1. Enter 20
2. Click `/`
3. Enter 0
4. Click `=`

**Expected Result:**
Error message should be displayed (e.g., *“Cannot divide by zero”*)

---

## BODMAS – Test Case

### Test Case Id:

**TC_012**

**Test Description:**
Verify calculator follows BODMAS rule

**Precondition:**
Calculator application is opened

**Test Steps:**

1. Enter `10 + 6 * 4`
2. Click `=`

**Expected Result:**
Result should be **34**

---

## Invalid Input – Test Cases

### Test Case Id:

**TC_013**

**Test Description:**
Verify behavior for alphabetic input

**Precondition:**
Calculator application is opened

**Test Steps:**

1. Enter `x`
2. Click `+`
3. Enter 7
4. Click `=`

**Expected Result:**
Error message should be displayed

---

### Test Case Id:

**TC_014**

**Test Description:**
Verify behavior for special characters

**Precondition:**
Calculator application is opened

**Test Steps:**

1. Enter `#`
2. Click `-`
3. Enter `$`
4. Click `=`

**Expected Result:**
Error message should be displayed

---

### Test Case Id:

**TC_015**

**Test Description:**
Verify behavior when no input is provided

**Precondition:**
Calculator application is opened

**Test Steps:**

1. Click `=` without entering any value

**Expected Result:**
Validation message or no result should be displayed
