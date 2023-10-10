# Python Notes For Professionals
### Section 10.3: Bitwise AND

The `&` operator will perform a binary `AND`, where a bit is copied if it exists in both operands. That means:
```
# 0 & 0 = 0
# 0 & 1 = 0
# 1 & 0 = 0
# 1 & 1 = 1
# 60 = 0b111100
# 30 = 0b011110
60 & 30
# Out: 28
# 28 = 0b11100
bin(60 & 30)
# Out: 0b11100
```
