a)
```
s2 = 0
s3 = s0

while s3 != 0:
    s3 -= 1
    s2 += s1
```
b) Because it adds s1 to s2 until s3 = 0, and s3 = s0. So it will loop
s0 number of times.

c)
```
s0 = 10
s1 = 1

while s0 != 0:
    s2 = 0
    s3 = s0
    while s3 != 0:
        s2 += s1
        s3 -= 1
    s1 = s2
    s0 -= 1
```
d) The inner loop repeats one less time each iteration of the outer loop,
within the inner loop the value of s1 is multiplied by the number of times it 
loops and is stored in the s2 registery until the inner loop finishes, 
at which point the value in s1 is set to the value of s2 ready to be 
called upon when the inner loop starts next iteration. 

e)
addi $s0, $zero, 10
addi $s1, $zero, 1

loop:
mult $s0, $s1
mflo $s2
addi $s0, $s0, -1
addi $s1, $s2, 0
bne, $s0, $zero, loop
