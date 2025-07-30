# pattern
RIGHT ANGLE TRIANGLE WITH "*"
rows=int(input("enter rows: "))
pattern=["".join(["*" for j in range(i)])for i in range(1,rows+1)]
for p in pattern:
    print(p)
