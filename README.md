def bspfunktionfuerrueckgabe(eingabewert):
	rueckgabewert = eingabewert * 2
	return rueckgabewert
    
if __name__ == "__main__":
	print("Datei wurde direkt aufgerufen und die Main wird ausgeführt")
else:
	print("Datei wurde als Modul aufgerufen")
    
print("Ich stehe in der Datei: " + __name__)



>>> prompt = 'What...is the airspeed velocity of an unladen swallow?\n'
>>>speed = input(prompt)
What...is the airspeed velocity of an unladen swallow?
What do you mean, an African or a European swallow?
>>>int(speed)
ValueError: invalid literal for int() with base 10:
