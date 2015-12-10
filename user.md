
###POST /user/login

Dummy Payload:
```
{
	"mail": "hen@egg.de",
	"password": "egg"
}
```

###POST /user/register
Dummy Payload:
```
{
	"name" : "Julo"
	"hometown" : "Konstanz"
	"mail": "julo@julohausen.de",
	"password": "ichbinjulo123"
}
```

###GET /user/me
requires authentication cookie
Dummy Result:
```
{
	_id: "ec26fc9e9342d7df21a87ab2477e3eb2", 
	name: "Julo",
	user_thumb: "/users/ec26fc9e9342d7df21a87ab2477e3eb2/profile.jpeg",
	hometown: "Konstanz, Deutschland"
}
```

###GET /user/logout
requires authentication cookie
