# Simple Calculator Application – Test Cases

---

## TC_01
**Test Case ID:** TC_01  
**Test Description:** Verify addition of two positive integers  
**Preconditions:** Calculator is open  
**Test Steps:**  
1. Enter 5  
2. Click +  
3. Enter 3  
4. Click =  
**Expected Result:** 8 should be displayed  

---

## TC_02
**Test Case ID:** TC_02  
**Test Description:** Verify subtraction of two positive integers  
**Preconditions:** Calculator is open  
**Test Steps:**  
1. Enter 10  
2. Click -  
3. Enter 4  
4. Click =  
**Expected Result:** 6 should be displayed  

---

## TC_03
**Test Case ID:** TC_03  
**Test Description:** Verify multiplication of two numbers  
**Test Steps:**  
1. Enter 6  
2. Click *  
3. Enter 7  
4. Click =  
**Expected Result:** 42  

---

## TC_04
**Test Case ID:** TC_04  
**Test Description:** Verify division of two numbers  
**Test Steps:**  
1. Enter 20  
2. Click /  
3. Enter 5  
4. Click =  
**Expected Result:** 4  

---

## TC_05
**Test Case ID:** TC_05  
**Test Description:** Verify addition of negative numbers  
**Test Steps:**  
1. Enter -5  
2. Click +  
3. Enter -3  
4. Click =  
**Expected Result:** -8  

---

## TC_06
**Test Case ID:** TC_06  
**Test Description:** Verify decimal addition  
**Test Steps:**  
1. Enter 5.5  
2. Click +  
3. Enter 2.3  
4. Click =  
**Expected Result:** 7.8  

---

## TC_07
**Test Case ID:** TC_07  
**Test Description:** Verify division by zero  
**Test Steps:**  
1. Enter 10  
2. Click /  
3. Enter 0  
4. Click =  
**Expected Result:** Error message should be displayed  

---

## TC_08
**Test Case ID:** TC_08  
**Test Description:** Verify handling of non-numeric input  
**Test Steps:**  
1. Enter abc  
2. Click +  
3. Enter 5  
4. Click =  
**Expected Result:** Validation error message  

---

## TC_09
**Test Case ID:** TC_09  
**Test Description:** Verify BODMAS rule  
**Test Steps:**  
1. Enter 5 + 3 * 2  
2. Click =  
**Expected Result:** 11  

---

## TC_10
**Test Case ID:** TC_10  
**Test Description:** Verify large number calculation  
**Test Steps:**  
1. Enter 999999  
2. Click +  
3. Enter 1  
4. Click =  
**Expected Result:** 1000000  

---

## TC_11
Verify subtraction resulting negative number  
Expected: -5  

## TC_12
Verify multiple decimal operations  
Expected: Correct decimal result  

## TC_13
Verify pressing equals multiple times  
Expected: Result remains same  

## TC_14
Verify clear button functionality  
Expected: Screen resets to zero  

## TC_15
Verify consecutive operations  
Expected: Correct final output  

## TC_16
Verify input with special characters (@#$)  
Expected: Validation error  

## TC_17
Verify empty input and press equals  
Expected: Validation message  

## TC_18
Verify leading zeros (0005 + 2)  
Expected: 7  

## TC_19
Verify negative and positive combination (-5 + 10)  
Expected: 5  

## TC_20
Verify floating division (7 / 2)  
Expected: 3.5  
