
###POST /user/login & POST /user/register

Dummy Payload:
```
{
	"mail": "hen@egg.de",
	"password": "egg",
}
```

###GET /user/me
requires authentication cookie
Dummy Result:
```
{
	_id: "ec26fc9e9342d7df21a87ab2477e3eb2", 
	name: "Julo"
	birthdate: "1992-06-05T22:00:00.000Z"
	name: "Michael"
	user_thumb: "/users/ec26fc9e9342d7df21a87ab2477e3eb2/profile.jpeg"
	hometown: "Konstanz, Deutschland"
}
```

###GET /user/logout
requires authentication cookie
