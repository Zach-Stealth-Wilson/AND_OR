<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works|

Two logic gates take two single bit inputs and compare them, with the result sent to the led at the output.
There is an AND gate and an OR gate. Their implementations are separate from one another

## How to test|
Using the Wokwi simulator verify the inputs using the truth tables

AND GATE
`AB = S `
|  A     |  B     |  S    |
|--------|--------|-------|
| 0      | 0      | 0     |
| 0      | 1      | 0     |
| 1      | 0      | 0     |
| 1      | 1      | 1     |


OR GATE
`A + B = Cout`
|  A     |  B     |  Cout |
|--------|--------|-------|
| 0      | 0      | 0     |
| 0      | 1      | 1     |
| 1      | 0      | 1     |
| 1      | 1      | 1     |


## External hardware|
Six Led's
