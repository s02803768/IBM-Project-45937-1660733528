# IBM-Project-45937-1660733528
Gas Leakage monitoring &amp; Alerting system for Industries


import random
def temp():
    temp=random.randint(20,40)
    return temp
def humidity():
    humidity=random.randint(30,70)
    return humidity
temp=temp()
humidity=humidity()
print("Temperature is=",temp)
print("Humidity is=",humidity)
if(temp>30):
    if(humidity>60):
        print("Alert detected")
    else:
        print("High temperature detected")
elif(temp==30):
    print("Threshold reached")
else:
    print("All good")
