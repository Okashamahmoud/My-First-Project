import os
import time
def The_Best_Player_In_The_world() :
    print("The Lsit is coutinue on : ")
    print("1 => Mohammed Salah\n" "2 => Ashraf Hakimi \n" "3 => Lamine Yamal \n" "4 => kylian mbappe\n" "5 => Ousmane Dembele")
    Your_Opinon = input("Enter a Num Player : ")
    print(f"Your Opinon Is {Your_Opinon}")
    if Your_Opinon == "1" :
        print("You Chose the Egyption Pharaoh ---> Mohammed Salah")
        time.sleep(1)
        os.startfile(r"C:\Users\user\Desktop\players\Salah.jpg")
    elif Your_Opinon == "2" :
        print("You Chose The Moroccan Lion ---> Ashraf Hakimi")
        time.sleep(1)
        os.startfile(r"C:\Users\user\Desktop\players\Hakimi.jpg")
    elif Your_Opinon == "3" :
        print("You Chose The Guy Who Amazes Everyone ---> Lamine Yamal")
        time.sleep(1)
        os.startfile(r"C:\Users\user\Desktop\players\Lamine.jpg")
    elif Your_Opinon == "4" :
        print("You Chose The Star Of Madrid And France ---> kylian Mbappe ")
        time.sleep(1)
        os.startfile(r"C:\Users\user\Desktop\players\Mbappe.jpg")
    elif Your_Opinon == "5" :
        print("You Chose The Dark-skinned Lion ---> Osmane Dembele ")
        time.sleep(1)
        os.startfile(r"C:\Users\user\Desktop\players\Ousmane.jpg")
    else :
        print("You Are Num is Not List : ")

The_Best_Player_In_The_world()
