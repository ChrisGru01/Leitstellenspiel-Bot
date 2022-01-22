Installation auf einem Linux-Server


1. registriere dich auf: https://missionchiefbot.com/

2. erwerbe die Menge and Bots die du benötigst

3. gehe auf https://missionchiefbot.com/dashboard , und klicke auf "Edit users". Hier trägst du den ingame Namen deines Leitstellenspiel Accounts ein, für den du den Bot erstellen möchtest.

4. um die passende Linux-Python Version zu installieren, folge bitte diesem Tutorial: https://stackoverflow.com/a/64353748

5. öffne ein Terminal und navigiere mittels "cd" Befehl in deinen Wunschordner und gib folgende Befehle nacheinander ein:

		apt-get install unzip -y

		wget https://github.com/jackbayliss/Mission-Chief-Bot/releases/download/0.2/Mission-Chief-Bot-linux-mac.zip

		unzip Mission-Chief-Bot-linux-mac.zip

		cd Mission-Chief-Bot-linux-mac/
		
		python3.9 -m pip install discord-webhook

		python3.9 -m pip install googletrans

		python3.9 -m pip install -r requirements.txt

		nano config.ini
    

die config.ini sollte sich in einem Editor öffnen. Zuerst trägst du deine Region ein. (deutsch = de) Darunter gibtst du deine Leitstellenspiel Logindaten an, für den Account den du im Dashboard eingetragen hast.

6. sobald alle Schritte fehlerfrei erledigt sind, kannst du den Bot mittels: 
7. 
python3.9 MissionChiefBot.py 

8. starten. Er sollte daraufhin anfangen die Missionen nacheinander runterzuladen. 

bei Fragen oder Problemen, wende dich gerne in Discord an mich! 
Chris-#2001
