# Python for everybody (Course 1)
# Coursera-Assignment-5.2
largest = None
smallest = None
while True:
    num = input("Enter a number:")
    if num == "done" : 
        break
    try: 
        fnum = int(num) 
       
    except:
        print("Invalid Input")
    
    if largest is None or largest < fnum:
        largest = fnum
    elif smallest is None or smallest > fnum:
        smallest = fnum
    
    
           
print("Maximum", largest)
print("Minimum", smallest)
