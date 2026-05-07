# Test Cases for Simple Calculator Application
---
## TC_01 – Addition of Two Positive Numbers

### Test Description
Verify calculator performs addition correctly.

### Preconditions
Calculator application is opened.

### Test Steps
1. Enter `10`
2. Click `+`
3. Enter `5`
4. Click `=`

### Expected Result
Calculator should display `15`.

---

## TC_02 – Subtraction of Two Numbers

### Test Description
Verify subtraction operation works correctly.

### Preconditions
Calculator application is opened.

### Test Steps
1. Enter `20`
2. Click `-`
3. Enter `8`
4. Click `=`

### Expected Result
Calculator should display `12`.

---

## TC_03 – Multiplication of Numbers

### Test Description
Verify multiplication works correctly.

### Preconditions
Calculator application is opened.

### Test Steps
1. Enter `7`
2. Click `*`
3. Enter `6`
4. Click `=`

### Expected Result
Calculator should display `42`.

---

## TC_04 – Division of Numbers

### Test Description
Verify division operation works correctly.

### Preconditions
Calculator application is opened.

### Test Steps
1. Enter `20`
2. Click `/`
3. Enter `4`
4. Click `=`

### Expected Result
Calculator should display `5`.

---

## TC_05 – Division by Zero

### Test Description
Verify calculator handles division by zero.

### Preconditions
Calculator application is opened.

### Test Steps
1. Enter `10`
2. Click `/`
3. Enter `0`
4. Click `=`

### Expected Result
Calculator should display an error message:
`Cannot divide by zero`.

---

## TC_06 – Decimal Number Addition

### Test Description
Verify calculator supports decimal values.

### Preconditions
Calculator application is opened.

### Test Steps
1. Enter `10.5`
2. Click `+`
3. Enter `2.5`
4. Click `=`

### Expected Result
Calculator should display `13.0`.

---

## TC_07 – Negative Number Calculation

### Test Description
Verify calculator handles negative numbers.

### Preconditions
Calculator application is opened.

### Test Steps
1. Enter `-8`
2. Click `+`
3. Enter `3`
4. Click `=`

### Expected Result
Calculator should display `-5`.

---

## TC_08 – Invalid Character Input

### Test Description
Verify calculator rejects non-numeric input.

### Preconditions
Calculator application is opened.

### Test Steps
1. Enter `ABC`
2. Click `=`

### Expected Result
Calculator should display:
`Invalid Input`.

---

## TC_09 – Empty Input Validation

### Test Description
Verify calculator handles empty input.

### Preconditions
Calculator application is opened.

### Test Steps
1. Leave input field empty
2. Click `=`

### Expected Result
Calculator should display:
`Please enter a value`.

---

## TC_10 – BODMAS Rule Validation

### Test Description
Verify calculator follows BODMAS rule.

### Preconditions
Calculator application is opened.

### Test Steps
1. Enter expression `2 + 3 * 4`
2. Click `=`

### Expected Result
Calculator should display `14`.

---