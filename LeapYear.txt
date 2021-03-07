def leap(year):
  if (year%4 == 0):
    if (year%400 == 0):
      return True
    elif (year%100 == 0):
      return False
    else: return True
    
  else: return False

year = int(input("Enter the year: "))
print(year, " is a leap year") if (leap(year)) else print(year, " is not a leap year")