# about
about share-fi, a social network based around wi-fi networks

## notes

- you need to submit a password to sign up
	- passwords go by honour system (unless someone has a better idea? double verification but that'd be a bit much)
	- comments section where people can rate the network
	- we could also have the network speed or information regarding the network (even brand of modem or ISP? possible WHOIS lookup)
	
- [geolocation via HTML5](http://www.w3schools.com/html/html5_geolocation.asp) provides networks in close proximity along with their passwords and information

- [API](https://github.com/share-fi/api) available so you can input location or lon/lat through parameters (+ an API key maybe, i'm not sure) which returns an object with arrays of close networks available

- [site](https://github.com/share-fi/site) when not logged in shows a big login and sign up modal kind of thing
	- on login
		- displays a fuckin *huge* [google maps](https://developers.google.com/maps/?hl=en) (or an alternative API for mapping if we can find something better?) box below displaying networks in the area
		- search input in top left corner
		- sign out in top right
	- on sign out
		- "goodbye wifi!" or something cheesy that makes the user want to desperately log back in