import pyautogui , time 
print("Рад приветствовать тебя)") 
def Spambot(): 
text = input("Введите сообщение, которые вы хотите заспамить:") 
count = int(input("Введите количество сообщенией:")) 
print("5 секундо до...") 
time.sleep(5)

while count > 0:
    count -= 1

    pyautogui.typewrite(text.strip())
    pyautogui.press('enter')
Spambot()
