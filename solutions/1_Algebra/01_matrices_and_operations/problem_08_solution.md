1. After R2 <- R2 - 2R1: [[1, 2, -1], [0, 0, 3], [-1, 1, 3]]
2. After R3 <- R3 + R1: [[1, 2, -1], [0, 0, 3], [0, 3, 2]]
3. After interchange R2 <-> R3: [[1, 2, -1], [0, 3, 2], [0, 0, 3]]
4. Reversing operations:
   - For R2 <- R2 - 2R1: use R2 <- R2 + 2R1
   - For R3 <- R3 + R1: use R3 <- R3 - R1
   - For interchange R2 <-> R3: interchange them again (R2 <-> R3).