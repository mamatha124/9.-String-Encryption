# 9.-String-Encryption in python
n = input()
res = ''
for i in range(0, len(n), 2):
    if i+1 < len(n):
        res += n[i+1] + n[i]
    else:
        res += n[i]
print(res)
