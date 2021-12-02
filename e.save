#!/home/a/pitonov/pitonov/bin/python3
london_co = { 
"r1": { 
"location": "21 New Globe Walk", 
"vendor": "Cisco", 
"model": "4451", 
"ios": "15.4", 
"ip": "10.255.0.1" },
"r2": { 
"location": "21 New Globe Walk", 
"vendor": "Cisco", 
"model": "4451", 
"ios": "15.4",
"ip": "10.255.0.2" }, 
"sw1": { "location": "21 New Globe Walk", 
"vendor": "Cisco", 
"model": "3850", 
"ios": "3.6.XE", 
"ip": "10.255.0.101", 
"vlans": "10,20,30", 
"routing": True }}
a=input('Name tech: ')
if a=='r1' or a=='r2':
	b=input('Name podtech(location, vendor, model, ios, ip): ')
	b=b.lower()
else:
	b=input('Name podtech(location, vendor, model, ios, ip, vlans, routing): ')
	b=b.lower()
if b not in london_co[a]:
	print('Wrong parametr')
else:
	print(london_co[a][b])

