# 1st_repo building a compound interest calculator using Python
def compound_interest(p,r,t):   
    amt = p * (pow((1 + (r/100)),t))
    print("Compound Amount: ",amt)
    CI = amt - p
    return CI

p=float(input("Enter Principal Amount: "))
r=float(input("Enter Rate of Interest: "))
t=float(input("Enter Time Period in years: "))
print("Compound interest is",compound_interest(p,r,t))
