Part 1
Test case 1 is AND
Test case 2 is OR
Test case 3 is ADD
Test case 4 is SUB
Test case 5 is SLT
Test case 6 is NOR
Test case 7 is ADDI
Test case 8 is LW
Test case 9 is SW
Test case 10 is BEQ
Part 2
The main differences are regdst as ADD uses 1 while ADDI uses 0. This is becasuse ADDI writes to rt instead of rd
ALUSRC is different because add uses 0 while ADDI uses 1. ADDI is trying to add an immediate value instead of any ordinary register
