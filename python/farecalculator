rates = {1: 10, 2: 18, 3: 25}
def calc_amount(km, car_type, hour):
    if car_type not in rates:
        print("Not Available")
        return
    amount = km * rates[car_type]
    if 17 <= hour <= 20:
        amount = amount * 1.5
    return amount
km = float(input("Enter distance (km): "))
print("1.Economy  2.Premium 3.SUV")
car = int(input("Choose car type (1/2/3): "))
hour = int(input("Enter hour (0-23): "))
result = calc_amount(km, car, hour)
if result:
    print("Total amount:", result)