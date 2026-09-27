# Voltage Divider - Series Resistors Experiment

## Objective
To understand how voltage is divided across resistors connected in series and verify the voltage division using Tinkercad simulation.

## Circuit

A 9V power supply was connected to:
- R1 = 1kΩ
- R2 = 2kΩ

The resistors were connected in series.

## Concept

For resistors connected in series, the same current flows through each resistor.

The total resistance is:

R_total = R1 + R2

Using Ohm's Law:

I = V / R_total

The voltage across each resistor is:

V = IR

## Design Calculation

### Total Resistance

R_total = 1kΩ + 2kΩ

R_total = 3kΩ

### Circuit Current

I = 9V / 3kΩ

I = 3mA

### Voltage Across 1kΩ

V1 = (3mA)(1kΩ)

V1 = 3V

### Voltage Across 2kΩ

V2 = (3mA)(2kΩ)

V2 = 6V

### Voltage Check

V1 + V2 = 3V + 6V

V1 + V2 = 9V

Therefore, the two voltage drops add up to the supply voltage.

## Simulation Results

| Quantity | Calculated | Measured |
|---|---:|---:|
| Circuit Current | 3.00mA | 3.00mA |
| Voltage across 1kΩ | 3.00V | 3.00V |
| Voltage across 2kΩ | 6.00V | 6.00V |
| Supply Voltage | 9.00V | 9.00V |

## Observation

The larger 2kΩ resistor receives a larger share of the supply voltage.

The 1kΩ resistor has a 3V drop, while the 2kΩ resistor has a 6V drop.

## What I Learned

- The same current flows through series resistors.
- Voltage divides across series resistors.
- A larger resistance gets a larger voltage drop when the same current flows through it.
- The individual voltage drops add up to the supply voltage.
- Calculated and simulated results matched.

## Engineering Lesson

Voltage dividers are useful for obtaining a desired voltage from a higher supply voltage and are commonly used in voltage sensing and signal conditioning circuits.

## Tools Used

- Tinkercad Circuits
- Multimeter
- 9V Power Supply
- 1kΩ Resistor
- 2kΩ Resistor
