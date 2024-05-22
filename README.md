#
n = int(input())
#
flag = "YES"
#
while n // 10 > 0:
#
    cur_digit = n % 10 
#
    if (n // 10) % 10 < cur_digit:
#
        flag = "NO"
#
    n //= 10
#
print(flag)
