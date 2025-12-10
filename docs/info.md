<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

The function outputs 1 when one of the following is true:

A and B are both 1 (the term AB)

C is 0 (the term C')

So even if A and B are not both 1, the function will still output 1 anytime C = 0. The only time the output is 0 is when C = 1 and A and B are not both 1.

## How to test
Truth Table of F=AB+C'

| A | B | C | AB | C' | F |
| - | - | - | -- | -- | - |
| 0 | 0 | 0 | 0  | 1  | 1 |
| 0 | 0 | 1 | 0  | 0  | 0 |
| 0 | 1 | 0 | 0  | 1  | 1 |
| 0 | 1 | 1 | 0  | 0  | 0 |
| 1 | 0 | 0 | 1  | 1  | 1 |
| 1 | 0 | 1 | 1  | 0  | 0 |
| 1 | 1 | 0 | 0  | 1  | 1 |
| 1 | 1 | 1 | 0  | 0  | 1 |
