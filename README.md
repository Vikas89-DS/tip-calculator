# tip-calculator
calculating tip on given amount

bill = int(input("please enter the amount.\n"))

people = int(input("please enter the no. of people.\n"))

tip = int(input("please enter the tip in percenetage 10 , 12, 15.\n"))

total_bill = (bill + bill * (tip/100))

bill_per_person = (total_bill/people)

round_bill = round(bill_per_person, 2)

print(f'Your bill per person is {round_bill}')

