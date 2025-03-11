def check_number(num):
    if num % 2 == 0:
        print(f"{num} EVEN NOMBIR.")
    else:
        print(f"{num} ODD NOMBIR")


print("OKE ICHICK NA NATIN")

try:
    TEDDY = int(input("ANONG NUMBER BA?: "))
    check_number(TEDDY)  
except ValueError:
    print("DATI KA BANG TIGANG NA NABAGOK ANG ULO SA SOBRANG KABOBOHAN?")
