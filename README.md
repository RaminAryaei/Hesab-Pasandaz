# Exercise 4 - Hesab Pasandaz Boland Modat
# @author: Ramin Aryaei
from colorama import Fore    # ketabkhane Rang ha
#----------------------------------------------------
    #Movjoodi Hesab
Mojoodi = int(input(Fore.RESET+'Movjoodi Hesabet ra benevis: '))
#----------------------------------------------------
    #List 12 mah
months = ['Aval','Dovom','Sevom','Chaharom','Panjoom',
          'Sheshom','Haftom','Hashtom','Nohom','Dahom',
          'Yazdahoom','Davazdahom']
#----------------------------------------------------
for i in months:
    sood = (Mojoodi*4)/100
    Mojoodi += sood
    print(Fore.RESET+'-----------------------------------------\n\n'
      f'Soode Mah {i} = '+Fore.RED+f'{sood:.2f}\n'+Fore.RESET+
      f'Mojodi Hesab mah {i} '+Fore.CYAN+f'{Mojoodi:.2f} '+Fore.RESET+'Toman.\n')
