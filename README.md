# MathAdv.js
MathAdv library for advanced math operations

## Usage
**Create matrix**: let sampleMatrice = new Matrix([25, 11], [23, 11, 45], [13]);
[] means array of matrix items as rows

**Transparent matrix**: sampleMatrice = sampleMatrice.transparent(); - will return a new instance of Matrix object, so rememeber about asserting to variable!

**Calculate any diagonals with**: sampleMatrice.getDiagonalToLeft(rowIndexStart, columnIndexStart), sampleMatrice.getDiagonalToRight(rowIndexStart, columnIndexStart) and reversed.

**Calculate main determinant**: sampleMatrice.calculateMainDeterminant();
