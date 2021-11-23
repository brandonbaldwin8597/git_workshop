num = input("Please enter a positive number: ")
if not num.strip().isdigit():
    print("It is an invalid entry. Don't use non-numeric, float, or negative values!")
elif int(num) >= 0 :
  num2 = 0
  for i in num:
    num2 += int(i) ** len(num)
  if num2 == int(num) :
    print("{} is an Armstrong number.".format(num))
  else:
    print("{} is not an Armstrong number.".format(num))
else:
  print("It is an invalid entry. Don't use non-numeric, float, or negative values!")
