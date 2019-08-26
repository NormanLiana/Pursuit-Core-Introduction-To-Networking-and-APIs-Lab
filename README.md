# Pursuit-Core-Introduction-To-Networking-and-APIs-Lab

# Part One

Status Code Scavenger Hunt!

Use Postman to find each of the following HTTP codes:


1. 200

https://api.nasa.gov/mars-photos/api/v1/rovers/curiosity/photos?sol=1000&api_key=DEMO_KEY
This means the request is successful and you can use the information the way it is outlined.
My understanding is that you shouldn't have issues when receiving this code.

1. 301


1. 400
1. 401
1. 403
1. 404
1. 418
1. 500


For each of the questions below, write:

1. The website which generated the HTTP status code
2. A description of what the status code means
3. If an app you were writing encountered this status code, what would you do (if anything) to resolve any issues?


For reference, see:

https://en.wikipedia.org/wiki/List_of_HTTP_status_codes (Links to an external site.)
https://http.cat


# Part Two

API Scavenger Hunt!

For each of the questions below, identify a website and search query that will give you the appropriate JSON.  Paste the url and the json below.  Googling the category + API will generally take you to where you need.  Ex. https://lmgtfy.com/?q=cat+fact+api

1. A random cat fact

https://catfact.ninja/fact

<details>
<summary>JSON</summary>
{
"fact": "A female cat is called a queen or a molly.",
"length": 42
}
</details>

1. A list of 150 random users in English.

https://randomuser.me/api/?results=150

<details>
<summary>JSON</summary>
{
"results": [
{
"gender": "male",
"name": {
"title": "monsieur",
"first": "maurizio",
"last": "roger"
},
"location": {
"street": "7359 rue dubois",
"city": "oberdorf (so)",
"state": "basel-stadt",
"postcode": 3950,
"coordinates": {
"latitude": "-53.6958",
"longitude": "-76.0373"
},
"timezone": {
"offset": "-9:00",
"description": "Alaska"
}
},
"email": "maurizio.roger@example.com",
"login": {
"uuid": "ae1bd925-8b9f-4dc3-852d-2bca528b0960",
"username": "blackswan266",
"password": "evil",
"salt": "GTK73Ynr",
"md5": "188a43a3c93ebc40e1bb76bb41e8f0dc",
"sha1": "691f16301055a88885b5251b1d5716d950ce6508",
"sha256": "b17c2e42533828e6ab45ac0001a35cb83b9f72df4afb46ad63b2e80c0439cda8"
},
"dob": {
"date": "1982-07-31T06:42:38Z",
"age": 37
},
"registered": {
"date": "2014-10-11T22:55:44Z",
"age": 4
},
"phone": "(157)-063-0027",
"cell": "(229)-872-7904",
"id": {
"name": "AVS",
"value": "756.1016.7974.99"
},
"picture": {
"large": "https://randomuser.me/api/portraits/men/63.jpg",
"medium": "https://randomuser.me/api/portraits/med/men/63.jpg",
"thumbnail": "https://randomuser.me/api/portraits/thumb/men/63.jpg"
},
"nat": "CH"
},
{
"gender": "female",
"name": {
"title": "mrs",
"first": "آنیتا",
"last": "مرادی"
},
"location": {
"street": "4372 موحد دانش",
"city": "خمینی‌شهر",
"state": "اصفهان",
"postcode": 91202,
"coordinates": {
"latitude": "-89.9666",
"longitude": "-91.7899"
},
"timezone": {
"offset": "+8:00",
"description": "Beijing, Perth, Singapore, Hong Kong"
}
},
"email": "آنیتا.مرادی@example.com",
"login": {
"uuid": "b34fdb4b-e072-403a-8eb6-efaa098d6a61",
"username": "lazybird900",
"password": "tiffany",
"salt": "O23iXpxV",
"md5": "da7e12afad31a57016c43660a524798f",
"sha1": "79f4aef8c70f0e8270d13ee9e6741e805709f66a",
"sha256": "761b9dab6811339c62c4da3c98a3e9e2dd3a2de67106c434c87a412fd4b1405d"
},
"dob": {
"date": "1975-08-25T05:53:50Z",
"age": 44
},
"registered": {
"date": "2009-05-01T05:04:29Z",
"age": 10
},
"phone": "095-79585199",
"cell": "0913-794-6513",
"id": {
"name": "",
"value": null
},
"picture": {
"large": "https://randomuser.me/api/portraits/women/57.jpg",
"medium": "https://randomuser.me/api/portraits/med/women/57.jpg",
"thumbnail": "https://randomuser.me/api/portraits/thumb/women/57.jpg"
},
"nat": "IR"
}
],
"info": {
"seed": "6c3206cec9485b8d",
"results": 2,
"page": 1,
"version": "1.2"
}
}
</details>

1. The current stock price of Microsoft. (IEX API)
1. The 5 year history of Apple stock prices (IEX API)
1. All the Swift language repos on Github with Pursuit in their name
1. A list of all Pokemon
1. A list of all items in Fortnite
1. A list of all Game of Thrones Episodes.
1. A list of all songs with "Love" in the title.
1. All information about Petyr Baelish from the Game of Thrones books
1. All the movies Leonardo Dicaprio has acted in
