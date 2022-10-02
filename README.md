# Instrukcja po polsku

1. Zainstaluj python [Python Download exe](https://www.python.org/ftp/python/3.10.7/python-3.10.7-amd64.exe)2. 2. podczas instalacji dodaj python'a do sciezki windowsa (checkbox)
   2. podczas instalacji dodaj python'a do sciezki windowsa (checkbox)
2. Zainstaluj biblioteki potrzebne do dziaania pythona ! `pip install -r requirments.txt`
3. Zainstaluj [Instalka win.64](https://digi.bib.uni-mannheim.de/tesseract/tesseract-ocr-w64-setup-v5.2.0.20220712.exe)
4. Zmodyfikuj plik `settings` w katalogu glownym (te ponizej wystarcza!)
   ```
    login = `twoj login`
    password = `twoje haslo`
    acc = `nazwa_twojego_konta_wowa`
    server = Gehennas
    WOW_PATH = C:\\World of Warcraft\\_classic_\\WowClassic.exe
    TES_PATH = C:\\Program Files\\Tesseract-OCR\\tesseract.exe
   ```
   
6. Zaznacz w grze `remember my account / login`
7. Uruchom linie komend (cmd) i skrypt `run.cmd`
   6. skrypt uruchomi okienko wow'a i przesunie myszke powoli
   7. program wykrywa `scene` na ktorej aktualnie sie znajduje (ekran logowania, ekran kolejki, ekran 
   dissconecta) i reaguje odpowiednio na zadany ekran
   

# WoW-login-bot
Bot for automatic login and keeping account online for classic World of Warcraft<br><br>
<i>WARNING: The bot is done in academical purpose. You use the software as it is and on your own risk. No warranty, guarantee nor sharing of responsibility is supposed in case of use the software</i><br>
<br>
<b>Installation guide</b>
<br>

-Python 3<br>
-Libraries - go through script import section and install all required dependencies
<br><br>
Check settings file and update following:<br>
login - your account name<br>
password - account password<br>
acc - combination of down (d) or up (u) arrow keys needed to chose correct account (only if you have multiple accounts - just run the bot and you will see what is it). <br><br><i>REMINDER: if check box of "Remember account name" is set, this screen will never appear on startup, however it's possible to see this after disconnect</i><br><br>
server - the server name to login<br>
WOW_PATH - path to WoW.exe<br>
TES_PATH - path to tesseract.exe<br>
USER - 0 if you want bot to enter both your account name and password, or 1 if check box of "Remember account name" is set<br>
Next lines are list of servers, it's better to keep them updated to help the bot in case of incorrect reading of server names<br>

WARNING: Do not modify order of settings and don't delete or add any new.
<br>
<br>
<b>Run</b>
<br>
Run the script using python3 executable or via run.cmd launch file (it may be needed to update the executable name into the cmd file in accordance with your environmental variable name of python3)
<br><br><br>
I hope you will enjoy this bot!<br>
In case of any questions - mail me on mikhail.ivanov@rocketmail.com
