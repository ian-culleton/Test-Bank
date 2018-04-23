## Prompt

(Thus named by John Michelin, after the color of marker he used on that particular day.)

Given an array of integers that represent the heights of towers in 2 dimensions, return the amount of water that would collect between the towers, assuming continuous, eternal rainfall.  In other words, at what point would this system reach equilibrium?

NOTES:  All towers can be assumed to be 1 unit in width, and all towers can be assumed to be adjacent and have no space between them. Water will *always* flow from higher towers to lower towers, and will *always* flow off the edge of the tower system.

Example to give
```

input: [1,3,2,1,3]

which represents the following towers:

height
4         _     _
3        |#|_  |#|
2       _|#|#|_|#|
1      |#|#|#|#|#|
------------------
input: [1,3,2,1,3]

output: 3

```

