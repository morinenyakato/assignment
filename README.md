# assignment
import calendar 
from datetime import datetime
Tnow = datetime.now()
Age = int(input("Enter your age: "))
Year = int(input('Enter year:'))
Month = int(input("Enter the month: "))
Day = int(input("Enter the day of the month: "))
cal = calendar.weekday(Year,Month,Day)
day = {0:'Monday',1:'Tuesday',2:'Wednesday',3:'Thursday',4:'Friday',5:'Saturday',6:'Sunday'}
print('You were born on',day[cal])
