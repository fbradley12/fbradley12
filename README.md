def pinPicker(number):
  import random
  while True:
    pin = ""
    for i in range(number):
      pin += str(random.randint(0, 6))
    return pin
pinPicker(4)
myPin = pinPicker(4)
print(pinPicker)
