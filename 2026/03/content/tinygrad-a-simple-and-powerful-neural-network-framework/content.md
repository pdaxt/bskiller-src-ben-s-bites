# tinygrad: A simple and powerful neural network framework

Source: [Ben's Bites](https://tinygrad.org/)

---

tinygradWe write and maintain tinygrad, the fastest growing neural network frameworkIt's extremely simple, and breaks down the most complexnetworks into 3 OpTypesElementwiseOps are UnaryOps, BinaryOps, and TernaryOps. They operate on 1-3 tensors and run elementwise. example: SQRT, LOG2, ADD, MUL, WHERE, etc...ReduceOps operate on one tensor and return a smaller tensor. example: SUM, MAXMovementOps are virtual ops that operate on one tensor and move the data around Copy-free with ShapeTracker. example: RESHAPE, PERMUTE, EXPAND, etc...But how...where are your CONVs and...