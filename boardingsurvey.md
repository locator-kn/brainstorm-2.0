###GET /user/boardingsurvey
Dummy Result:
```
{
	"weekend": {
		"question": "Wie sieht dein Wochenende aus?",
		"hen": "Was? Schon Montag? Lass mal lieber aftherhourn!",
		"egg": "Hauptsache Couch!"
	},
	"gourmet": {
		"question": "Was schmeichelt deinem Gaumen?",
		"hen": "Egal, hauptsache schnell und billig!",
		"egg": "Nur das Beste in den Hals!"
	},
	"nature": {
		"question": "Was hälst du von Natur?",
		"hen": "Iiiiii, Käfer!",
		"egg": "Bear Grylls, my Man!"
	},
	"funtime": {
		"question": "Und wenn du mal nichts zu tun hast?",
		"hen": "Bah! Spaß! Bloß nicht bewegen!",
		"egg": "Yeah Hui! Sofort raus, was erleben!"
	},
	"painting": {
		"question": "Wenn du ein Gemälde siehst",
		"hen": "...würde sich das gut über meinem Kamin machen.",
		"egg": "...würde sich das gut in meinem Kamin machen."
	}
}
```

###POST /user/boardingsurvey 
requires authentication cookie

Dummy Payload:
```
{
	"weekend": "hen",
	"gourmet": "egg",
	"nature": "hen",
	"funtime": "egg",
	"painting": "hen"
}
```