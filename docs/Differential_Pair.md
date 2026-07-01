# Differential Pair

## 1. What is a Differential Amplifier?

A differential amplifier amplifies the difference between two input voltages while rejecting signals that are common to both inputs (common-mode signals). This makes the circuit less sensitive to noise and interference that appears equally on both inputs.

---

## 2. Why use a Differential Pair instead of a Common-Source Amplifier?

A common-source amplifier amplifies only a single-ended input and cannot reject common-mode noise. In contrast, a differential pair amplifies only the voltage difference between two inputs, providing better noise immunity and making it suitable as the input stage of operational amplifiers.

---

## 3. What is the Function of the Tail Current Source (ISS)?

The tail current source provides a constant bias current to the differential pair. This current is shared between transistors M1 and M2, such that

ID1 + ID2 = ISS

When the gate voltage of M1 increases relative to M2, M1 conducts more current while M2 conducts less. The total current remains constant because it is fixed by the tail current source.

---

## 4. Current Steering

Consider a differential pair with

ISS = 20 µA

If both inputs are equal,

ID1 = 10 µA
ID2 = 10 µA

When Vin+ increases,

ID1 = 12 µA
ID2 = 8 µA

The current source still supplies only 20 µA. The differential input does not create more current; instead, it redistributes the fixed tail current between the two branches. This process is known as current steering.
