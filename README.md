# nikolaphyton

def c2f(tempC):
    return (1.8 * tempC + 32)

def f2c(tempF):
    return(tempF -32) / 1.8


while True:
    print ("Izaberite 1 da konvertujete *C u *F")
    print ("Izaberite 2 da konvertujete *F u *C")
    print ("Izaberite 0 da ugasite program")
    izbor = int(input("Izaberite sta zelite: "))

    if izbor == 1:
       tempC = float(input("Unesite temperaturu *C: "))
       tempF = c2f(tempC)
       print("Ta temperautra u * F je" + str(tempF))
    elif izbor == 2:
       tempF = float(input("Unesite temperaturu u *F: "))
       tempC = f2c((tempF))
       print("Ta temperatura u C je "+ str(tempC))
    elif izbor==0:
       print("Kraj programa")
       break
