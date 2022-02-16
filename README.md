# Apni-Dictionery
This is a simple program for creating dictionery.
dic= {"A":"First Letter", "B":"Secoend Letter", "C":"Third Letter", "D": "Fourth Letter"}
dic["a"]=["First Letter"]
dic.update({"b":"Seconed Letter", "c":"Third Letter", "d": "Fourth Letter"})
ask= input("Select Choice:\nA,a. B,b. C,c. D,d.\n")
b= dic.get(ask)
print("The mean of {} is {}.\n" .format(ask,b) )
ask_for_start= input("For Start Again, Press \"Y\".\nFor Closing The Program, Press \"Q\".\n")
while ask_for_start=="Y":
        ask= input("Select Choice:\nA,a. B,b. C,c. D,d.\n")
        b= dic.get(ask)
        print("The mean of {} is {}.\n" .format(ask,b) )
        ask_for_start= input("For Start Again, Press \"Y\".\nFor Closing The Program, Press \"Q\".\n")
if ask_for_start=="Q":
    print("Thanks for your Time.")
