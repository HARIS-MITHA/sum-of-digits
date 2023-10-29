def sum_of_digits(number):
    sum=0
    while number>0:
      rem=number%10
      sum+=rem
      n=number//10
      number=n
    return(sum)
number=int(input())
print(sum_of_digits(number))
