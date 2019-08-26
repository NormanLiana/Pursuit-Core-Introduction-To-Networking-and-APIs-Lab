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

https://api-v2.intrinio.com/companies/AAPL
This code means that you are not authorized for the request.
I would need to authenticate my request.

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

https://www.alphavantage.co/query?apikey=demo&function=TIME_SERIES_DAILY_ADJUSTED&symbol=MSFT

<details>
<summary>JSON</summary>
{
"Meta Data": {
"1. Information": "Daily Time Series with Splits and Dividend Events",
"2. Symbol": "MSFT",
"3. Last Refreshed": "2019-08-26 15:27:34",
"4. Output Size": "Compact",
"5. Time Zone": "US/Eastern"
},
"Time Series (Daily)": {
"2019-08-26": {
"1. open": "134.9900",
"2. high": "135.4500",
"3. low": "133.9000",
"4. close": "135.0400",
"5. adjusted close": "135.0400",
"6. volume": "13375355",
"7. dividend amount": "0.0000",
"8. split coefficient": "1.0000"
},
"2019-08-23": {
"1. open": "137.1897",
"2. high": "138.3500",
"3. low": "132.8000",
"4. close": "133.3900",
"5. adjusted close": "133.3900",
"6. volume": "32523998",
"7. dividend amount": "0.0000",
"8. split coefficient": "1.0000"
},
"2019-08-22": {
"1. open": "138.6600",
"2. high": "139.2000",
"3. low": "136.2900",
"4. close": "137.7800",
"5. adjusted close": "137.7800",
"6. volume": "18697000",
"7. dividend amount": "0.0000",
"8. split coefficient": "1.0000"
},
"2019-08-21": {
"1. open": "138.5500",
"2. high": "139.4900",
"3. low": "138.0000",
"4. close": "138.7900",
"5. adjusted close": "138.7900",
"6. volume": "14970300",
"7. dividend amount": "0.0000",
"8. split coefficient": "1.0000"
},
"2019-08-20": {
"1. open": "138.2100",
"2. high": "138.7100",
"3. low": "137.2400",
"4. close": "137.2600",
"5. adjusted close": "137.2600",
"6. volume": "21170800",
"7. dividend amount": "0.0000",
"8. split coefficient": "1.0000"
},
"2019-08-19": {
"1. open": "137.8500",
"2. high": "138.5500",
"3. low": "136.8900",
"4. close": "138.4100",
"5. adjusted close": "138.4100",
"6. volume": "24355700",
"7. dividend amount": "0.0000",
"8. split coefficient": "1.0000"
},
"2019-08-16": {
"1. open": "134.8800",
"2. high": "136.4600",
"3. low": "134.7200",
"4. close": "136.1300",
"5. adjusted close": "136.1300",
"6. volume": "24449100",
"7. dividend amount": "0.0000",
"8. split coefficient": "1.0000"
},
"2019-08-15": {
"1. open": "134.3900",
"2. high": "134.5800",
"3. low": "132.2500",
"4. close": "133.6800",
"5. adjusted close": "133.6800",
"6. volume": "28074400",
"7. dividend amount": "0.0000",
"8. split coefficient": "1.0000"
},
"2019-08-14": {
"1. open": "136.3600",
"2. high": "136.9200",
"3. low": "133.6700",
"4. close": "133.9800",
"5. adjusted close": "133.9800",
"6. volume": "32527300",
"7. dividend amount": "0.4600",
"8. split coefficient": "1.0000"
},
"2019-08-13": {
"1. open": "136.0500",
"2. high": "138.8000",
"3. low": "135.0000",
"4. close": "138.6000",
"5. adjusted close": "138.1400",
"6. volume": "25154600",
"7. dividend amount": "0.0000",
"8. split coefficient": "1.0000"
},
"2019-08-12": {
"1. open": "137.0700",
"2. high": "137.8600",
"3. low": "135.2400",
"4. close": "135.7900",
"5. adjusted close": "135.3393",
"6. volume": "20476600",
"7. dividend amount": "0.0000",
"8. split coefficient": "1.0000"
},
"2019-08-09": {
"1. open": "138.6100",
"2. high": "139.3800",
"3. low": "136.4600",
"4. close": "137.7100",
"5. adjusted close": "137.2530",
"6. volume": "23466700",
"7. dividend amount": "0.0000",
"8. split coefficient": "1.0000"
},
"2019-08-08": {
"1. open": "136.6000",
"2. high": "138.9900",
"3. low": "135.9300",
"4. close": "138.8900",
"5. adjusted close": "138.4290",
"6. volume": "27496500",
"7. dividend amount": "0.0000",
"8. split coefficient": "1.0000"
},
"2019-08-07": {
"1. open": "133.7900",
"2. high": "135.6500",
"3. low": "131.8280",
"4. close": "135.2800",
"5. adjusted close": "134.8310",
"6. volume": "33414500",
"7. dividend amount": "0.0000",
"8. split coefficient": "1.0000"
},
"2019-08-06": {
"1. open": "133.8000",
"2. high": "135.6800",
"3. low": "133.2100",
"4. close": "134.6900",
"5. adjusted close": "134.2430",
"6. volume": "32696700",
"7. dividend amount": "0.0000",
"8. split coefficient": "1.0000"
},
"2019-08-05": {
"1. open": "133.3000",
"2. high": "133.9300",
"3. low": "130.7800",
"4. close": "132.2100",
"5. adjusted close": "131.7712",
"6. volume": "42749600",
"7. dividend amount": "0.0000",
"8. split coefficient": "1.0000"
},
"2019-08-02": {
"1. open": "138.0900",
"2. high": "138.3200",
"3. low": "135.2600",
"4. close": "136.9000",
"5. adjusted close": "136.4456",
"6. volume": "30791600",
"7. dividend amount": "0.0000",
"8. split coefficient": "1.0000"
},
"2019-08-01": {
"1. open": "137.0000",
"2. high": "140.9400",
"3. low": "136.9300",
"4. close": "138.0600",
"5. adjusted close": "137.6018",
"6. volume": "40557500",
"7. dividend amount": "0.0000",
"8. split coefficient": "1.0000"
},
"2019-07-31": {
"1. open": "140.3300",
"2. high": "140.4900",
"3. low": "135.0800",
"4. close": "136.2700",
"5. adjusted close": "135.8177",
"6. volume": "38598800",
"7. dividend amount": "0.0000",
"8. split coefficient": "1.0000"
},
"2019-07-30": {
"1. open": "140.1400",
"2. high": "141.2200",
"3. low": "139.8000",
"4. close": "140.3500",
"5. adjusted close": "139.8842",
"6. volume": "16846500",
"7. dividend amount": "0.0000",
"8. split coefficient": "1.0000"
},
"2019-07-29": {
"1. open": "141.5000",
"2. high": "141.5100",
"3. low": "139.3700",
"4. close": "141.0300",
"5. adjusted close": "140.5619",
"6. volume": "16605900",
"7. dividend amount": "0.0000",
"8. split coefficient": "1.0000"
},
"2019-07-26": {
"1. open": "140.3700",
"2. high": "141.6800",
"3. low": "140.3000",
"4. close": "141.3400",
"5. adjusted close": "140.8709",
"6. volume": "19037600",
"7. dividend amount": "0.0000",
"8. split coefficient": "1.0000"
},
"2019-07-25": {
"1. open": "140.4300",
"2. high": "140.6100",
"3. low": "139.3200",
"4. close": "140.1900",
"5. adjusted close": "139.7247",
"6. volume": "18356900",
"7. dividend amount": "0.0000",
"8. split coefficient": "1.0000"
},
"2019-07-24": {
"1. open": "138.8968",
"2. high": "140.7400",
"3. low": "138.8500",
"4. close": "140.7200",
"5. adjusted close": "140.2530",
"6. volume": "20738300",
"7. dividend amount": "0.0000",
"8. split coefficient": "1.0000"
},
"2019-07-23": {
"1. open": "139.7600",
"2. high": "139.9900",
"3. low": "138.0300",
"4. close": "139.2900",
"5. adjusted close": "138.8277",
"6. volume": "18034600",
"7. dividend amount": "0.0000",
"8. split coefficient": "1.0000"
},
"2019-07-22": {
"1. open": "137.4100",
"2. high": "139.1900",
"3. low": "137.3300",
"4. close": "138.4300",
"5. adjusted close": "137.9706",
"6. volume": "25074900",
"7. dividend amount": "0.0000",
"8. split coefficient": "1.0000"
},
"2019-07-19": {
"1. open": "140.2200",
"2. high": "140.6700",
"3. low": "136.4500",
"4. close": "136.6200",
"5. adjusted close": "136.1666",
"6. volume": "48992400",
"7. dividend amount": "0.0000",
"8. split coefficient": "1.0000"
},
"2019-07-18": {
"1. open": "135.5500",
"2. high": "136.6200",
"3. low": "134.6700",
"4. close": "136.4200",
"5. adjusted close": "135.9672",
"6. volume": "30808700",
"7. dividend amount": "0.0000",
"8. split coefficient": "1.0000"
},
"2019-07-17": {
"1. open": "137.7000",
"2. high": "137.9300",
"3. low": "136.2200",
"4. close": "136.2700",
"5. adjusted close": "135.8177",
"6. volume": "20211000",
"7. dividend amount": "0.0000",
"8. split coefficient": "1.0000"
},
"2019-07-16": {
"1. open": "138.9600",
"2. high": "139.0500",
"3. low": "136.5200",
"4. close": "137.0800",
"5. adjusted close": "136.6250",
"6. volume": "22726100",
"7. dividend amount": "0.0000",
"8. split coefficient": "1.0000"
},
"2019-07-15": {
"1. open": "139.4400",
"2. high": "139.5400",
"3. low": "138.4600",
"4. close": "138.9000",
"5. adjusted close": "138.4390",
"6. volume": "16651500",
"7. dividend amount": "0.0000",
"8. split coefficient": "1.0000"
},
"2019-07-12": {
"1. open": "138.8500",
"2. high": "139.1300",
"3. low": "138.0100",
"4. close": "138.9000",
"5. adjusted close": "138.4390",
"6. volume": "18936800",
"7. dividend amount": "0.0000",
"8. split coefficient": "1.0000"
},
"2019-07-11": {
"1. open": "138.2000",
"2. high": "139.2200",
"3. low": "137.8700",
"4. close": "138.4000",
"5. adjusted close": "137.9407",
"6. volume": "22327900",
"7. dividend amount": "0.0000",
"8. split coefficient": "1.0000"
},
"2019-07-10": {
"1. open": "137.1300",
"2. high": "138.5800",
"3. low": "137.0200",
"4. close": "137.8500",
"5. adjusted close": "137.3925",
"6. volume": "24204400",
"7. dividend amount": "0.0000",
"8. split coefficient": "1.0000"
},
"2019-07-09": {
"1. open": "136.0000",
"2. high": "136.9700",
"3. low": "135.8000",
"4. close": "136.4600",
"5. adjusted close": "136.0071",
"6. volume": "19953100",
"7. dividend amount": "0.0000",
"8. split coefficient": "1.0000"
},
"2019-07-08": {
"1. open": "136.4000",
"2. high": "137.1000",
"3. low": "135.3700",
"4. close": "136.9600",
"5. adjusted close": "136.5054",
"6. volume": "16779700",
"7. dividend amount": "0.0000",
"8. split coefficient": "1.0000"
},
"2019-07-05": {
"1. open": "135.9400",
"2. high": "137.3300",
"3. low": "135.7200",
"4. close": "137.0600",
"5. adjusted close": "136.6051",
"6. volume": "18141100",
"7. dividend amount": "0.0000",
"8. split coefficient": "1.0000"
},
"2019-07-03": {
"1. open": "136.8000",
"2. high": "137.7400",
"3. low": "136.2950",
"4. close": "137.4600",
"5. adjusted close": "137.0038",
"6. volume": "13629300",
"7. dividend amount": "0.0000",
"8. split coefficient": "1.0000"
},
"2019-07-02": {
"1. open": "136.1200",
"2. high": "136.5900",
"3. low": "135.3291",
"4. close": "136.5800",
"5. adjusted close": "136.1267",
"6. volume": "15237800",
"7. dividend amount": "0.0000",
"8. split coefficient": "1.0000"
},
"2019-07-01": {
"1. open": "136.6300",
"2. high": "136.7000",
"3. low": "134.9700",
"4. close": "135.6800",
"5. adjusted close": "135.2297",
"6. volume": "22654200",
"7. dividend amount": "0.0000",
"8. split coefficient": "1.0000"
},
"2019-06-28": {
"1. open": "134.5700",
"2. high": "134.6000",
"3. low": "133.1560",
"4. close": "133.9600",
"5. adjusted close": "133.5154",
"6. volume": "30043000",
"7. dividend amount": "0.0000",
"8. split coefficient": "1.0000"
},
"2019-06-27": {
"1. open": "134.1400",
"2. high": "134.7100",
"3. low": "133.5100",
"4. close": "134.1500",
"5. adjusted close": "133.7048",
"6. volume": "16557500",
"7. dividend amount": "0.0000",
"8. split coefficient": "1.0000"
},
"2019-06-26": {
"1. open": "134.3500",
"2. high": "135.7327",
"3. low": "133.6000",
"4. close": "133.9300",
"5. adjusted close": "133.4855",
"6. volume": "23657700",
"7. dividend amount": "0.0000",
"8. split coefficient": "1.0000"
},
"2019-06-25": {
"1. open": "137.2500",
"2. high": "137.5900",
"3. low": "132.7300",
"4. close": "133.4300",
"5. adjusted close": "132.9872",
"6. volume": "33327400",
"7. dividend amount": "0.0000",
"8. split coefficient": "1.0000"
},
"2019-06-24": {
"1. open": "137.0000",
"2. high": "138.4000",
"3. low": "137.0000",
"4. close": "137.7800",
"5. adjusted close": "137.3227",
"6. volume": "20628800",
"7. dividend amount": "0.0000",
"8. split coefficient": "1.0000"
},
"2019-06-21": {
"1. open": "136.5800",
"2. high": "137.7300",
"3. low": "136.4600",
"4. close": "136.9700",
"5. adjusted close": "136.5154",
"6. volume": "36727900",
"7. dividend amount": "0.0000",
"8. split coefficient": "1.0000"
},
"2019-06-20": {
"1. open": "137.4500",
"2. high": "137.6600",
"3. low": "135.7200",
"4. close": "136.9500",
"5. adjusted close": "136.4955",
"6. volume": "33042600",
"7. dividend amount": "0.0000",
"8. split coefficient": "1.0000"
},
"2019-06-19": {
"1. open": "135.0000",
"2. high": "135.9300",
"3. low": "133.8100",
"4. close": "135.6900",
"5. adjusted close": "135.2397",
"6. volume": "23744400",
"7. dividend amount": "0.0000",
"8. split coefficient": "1.0000"
},
"2019-06-18": {
"1. open": "134.1900",
"2. high": "135.2400",
"3. low": "133.5700",
"4. close": "135.1600",
"5. adjusted close": "134.7114",
"6. volume": "25934500",
"7. dividend amount": "0.0000",
"8. split coefficient": "1.0000"
},
"2019-06-17": {
"1. open": "132.6300",
"2. high": "133.7300",
"3. low": "132.5300",
"4. close": "132.8500",
"5. adjusted close": "132.4091",
"6. volume": "14517800",
"7. dividend amount": "0.0000",
"8. split coefficient": "1.0000"
},
"2019-06-14": {
"1. open": "132.2600",
"2. high": "133.7900",
"3. low": "131.6400",
"4. close": "132.4500",
"5. adjusted close": "132.0104",
"6. volume": "17821700",
"7. dividend amount": "0.0000",
"8. split coefficient": "1.0000"
},
"2019-06-13": {
"1. open": "131.9800",
"2. high": "132.6700",
"3. low": "131.5600",
"4. close": "132.3200",
"5. adjusted close": "131.8808",
"6. volume": "17200800",
"7. dividend amount": "0.0000",
"8. split coefficient": "1.0000"
},
"2019-06-12": {
"1. open": "131.4000",
"2. high": "131.9700",
"3. low": "130.7100",
"4. close": "131.4900",
"5. adjusted close": "131.0536",
"6. volume": "17092500",
"7. dividend amount": "0.0000",
"8. split coefficient": "1.0000"
},
"2019-06-11": {
"1. open": "133.8800",
"2. high": "134.2400",
"3. low": "131.2760",
"4. close": "132.1000",
"5. adjusted close": "131.6616",
"6. volume": "23913700",
"7. dividend amount": "0.0000",
"8. split coefficient": "1.0000"
},
"2019-06-10": {
"1. open": "132.4000",
"2. high": "134.0800",
"3. low": "132.0000",
"4. close": "132.6000",
"5. adjusted close": "132.1599",
"6. volume": "26477100",
"7. dividend amount": "0.0000",
"8. split coefficient": "1.0000"
},
"2019-06-07": {
"1. open": "129.1903",
"2. high": "132.2500",
"3. low": "128.2600",
"4. close": "131.4000",
"5. adjusted close": "130.9639",
"6. volume": "33885600",
"7. dividend amount": "0.0000",
"8. split coefficient": "1.0000"
},
"2019-06-06": {
"1. open": "126.4400",
"2. high": "127.9700",
"3. low": "125.6000",
"4. close": "127.8200",
"5. adjusted close": "127.3958",
"6. volume": "21459000",
"7. dividend amount": "0.0000",
"8. split coefficient": "1.0000"
},
"2019-06-05": {
"1. open": "124.9500",
"2. high": "125.8700",
"3. low": "124.2100",
"4. close": "125.8300",
"5. adjusted close": "125.4124",
"6. volume": "24926100",
"7. dividend amount": "0.0000",
"8. split coefficient": "1.0000"
},
"2019-06-04": {
"1. open": "121.2800",
"2. high": "123.2800",
"3. low": "120.6520",
"4. close": "123.1600",
"5. adjusted close": "122.7512",
"6. volume": "29382600",
"7. dividend amount": "0.0000",
"8. split coefficient": "1.0000"
},
"2019-06-03": {
"1. open": "123.8500",
"2. high": "124.3700",
"3. low": "119.0100",
"4. close": "119.8400",
"5. adjusted close": "119.4423",
"6. volume": "37983600",
"7. dividend amount": "0.0000",
"8. split coefficient": "1.0000"
},
"2019-05-31": {
"1. open": "124.2300",
"2. high": "124.6150",
"3. low": "123.3200",
"4. close": "123.6800",
"5. adjusted close": "123.2695",
"6. volume": "26646800",
"7. dividend amount": "0.0000",
"8. split coefficient": "1.0000"
},
"2019-05-30": {
"1. open": "125.2610",
"2. high": "125.7600",
"3. low": "124.7800",
"4. close": "125.7300",
"5. adjusted close": "125.3127",
"6. volume": "16829600",
"7. dividend amount": "0.0000",
"8. split coefficient": "1.0000"
},
"2019-05-29": {
"1. open": "125.3800",
"2. high": "125.3900",
"3. low": "124.0400",
"4. close": "124.9400",
"5. adjusted close": "124.5253",
"6. volume": "22763100",
"7. dividend amount": "0.0000",
"8. split coefficient": "1.0000"
},
"2019-05-28": {
"1. open": "126.9800",
"2. high": "128.0000",
"3. low": "126.0500",
"4. close": "126.1600",
"5. adjusted close": "125.7413",
"6. volume": "23128400",
"7. dividend amount": "0.0000",
"8. split coefficient": "1.0000"
},
"2019-05-24": {
"1. open": "126.9100",
"2. high": "127.4150",
"3. low": "125.9700",
"4. close": "126.2400",
"5. adjusted close": "125.8210",
"6. volume": "14123400",
"7. dividend amount": "0.0000",
"8. split coefficient": "1.0000"
},
"2019-05-23": {
"1. open": "126.2000",
"2. high": "126.2900",
"3. low": "124.7400",
"4. close": "126.1800",
"5. adjusted close": "125.7612",
"6. volume": "23603800",
"7. dividend amount": "0.0000",
"8. split coefficient": "1.0000"
},
"2019-05-22": {
"1. open": "126.6200",
"2. high": "128.2400",
"3. low": "126.5293",
"4. close": "127.6700",
"5. adjusted close": "127.2463",
"6. volume": "15396500",
"7. dividend amount": "0.0000",
"8. split coefficient": "1.0000"
},
"2019-05-21": {
"1. open": "127.4300",
"2. high": "127.5270",
"3. low": "126.5800",
"4. close": "126.9000",
"5. adjusted close": "126.4788",
"6. volume": "15293300",
"7. dividend amount": "0.0000",
"8. split coefficient": "1.0000"
},
"2019-05-20": {
"1. open": "126.5200",
"2. high": "127.5890",
"3. low": "125.7610",
"4. close": "126.2200",
"5. adjusted close": "125.8011",
"6. volume": "23706900",
"7. dividend amount": "0.0000",
"8. split coefficient": "1.0000"
},
"2019-05-17": {
"1. open": "128.3050",
"2. high": "130.4600",
"3. low": "127.9200",
"4. close": "128.0700",
"5. adjusted close": "127.6450",
"6. volume": "25770500",
"7. dividend amount": "0.0000",
"8. split coefficient": "1.0000"
},
"2019-05-16": {
"1. open": "126.7500",
"2. high": "129.3800",
"3. low": "126.4600",
"4. close": "128.9300",
"5. adjusted close": "128.5021",
"6. volume": "30112200",
"7. dividend amount": "0.0000",
"8. split coefficient": "1.0000"
},
"2019-05-15": {
"1. open": "124.2600",
"2. high": "126.7115",
"3. low": "123.7000",
"4. close": "126.0200",
"5. adjusted close": "125.6017",
"6. volume": "24722700",
"7. dividend amount": "0.4600",
"8. split coefficient": "1.0000"
},
"2019-05-14": {
"1. open": "123.8700",
"2. high": "125.8800",
"3. low": "123.7000",
"4. close": "124.7300",
"5. adjusted close": "123.8576",
"6. volume": "25266300",
"7. dividend amount": "0.0000",
"8. split coefficient": "1.0000"
},
"2019-05-13": {
"1. open": "124.1100",
"2. high": "125.5500",
"3. low": "123.0400",
"4. close": "123.3500",
"5. adjusted close": "122.4872",
"6. volume": "33944900",
"7. dividend amount": "0.0000",
"8. split coefficient": "1.0000"
},
"2019-05-10": {
"1. open": "124.9172",
"2. high": "127.9300",
"3. low": "123.8200",
"4. close": "127.1300",
"5. adjusted close": "126.2408",
"6. volume": "30915100",
"7. dividend amount": "0.0000",
"8. split coefficient": "1.0000"
},
"2019-05-09": {
"1. open": "124.2950",
"2. high": "125.7900",
"3. low": "123.5700",
"4. close": "125.5000",
"5. adjusted close": "124.6222",
"6. volume": "27235800",
"7. dividend amount": "0.0000",
"8. split coefficient": "1.0000"
},
"2019-05-08": {
"1. open": "125.4400",
"2. high": "126.3700",
"3. low": "124.7500",
"4. close": "125.5100",
"5. adjusted close": "124.6321",
"6. volume": "28419000",
"7. dividend amount": "0.0000",
"8. split coefficient": "1.0000"
},
"2019-05-07": {
"1. open": "126.4600",
"2. high": "127.1800",
"3. low": "124.2200",
"4. close": "125.5200",
"5. adjusted close": "124.6420",
"6. volume": "36017700",
"7. dividend amount": "0.0000",
"8. split coefficient": "1.0000"
},
"2019-05-06": {
"1. open": "126.3900",
"2. high": "128.5600",
"3. low": "126.1084",
"4. close": "128.1500",
"5. adjusted close": "127.2536",
"6. volume": "24239800",
"7. dividend amount": "0.0000",
"8. split coefficient": "1.0000"
},
"2019-05-03": {
"1. open": "127.3600",
"2. high": "129.4300",
"3. low": "127.2500",
"4. close": "128.9000",
"5. adjusted close": "127.9984",
"6. volume": "24911100",
"7. dividend amount": "0.0000",
"8. split coefficient": "1.0000"
},
"2019-05-02": {
"1. open": "127.9800",
"2. high": "128.0000",
"3. low": "125.5200",
"4. close": "126.2100",
"5. adjusted close": "125.3272",
"6. volume": "27350200",
"7. dividend amount": "0.0000",
"8. split coefficient": "1.0000"
},
"2019-05-01": {
"1. open": "130.5300",
"2. high": "130.6500",
"3. low": "127.7000",
"4. close": "127.8800",
"5. adjusted close": "126.9855",
"6. volume": "26821700",
"7. dividend amount": "0.0000",
"8. split coefficient": "1.0000"
},
"2019-04-30": {
"1. open": "129.8100",
"2. high": "130.7000",
"3. low": "129.3950",
"4. close": "130.6000",
"5. adjusted close": "129.6865",
"6. volume": "24166500",
"7. dividend amount": "0.0000",
"8. split coefficient": "1.0000"
},
"2019-04-29": {
"1. open": "129.9000",
"2. high": "130.1800",
"3. low": "129.3500",
"4. close": "129.7700",
"5. adjusted close": "128.8623",
"6. volume": "16324200",
"7. dividend amount": "0.0000",
"8. split coefficient": "1.0000"
},
"2019-04-26": {
"1. open": "129.7000",
"2. high": "130.5150",
"3. low": "129.0200",
"4. close": "129.8900",
"5. adjusted close": "128.9815",
"6. volume": "23654900",
"7. dividend amount": "0.0000",
"8. split coefficient": "1.0000"
},
"2019-04-25": {
"1. open": "130.0600",
"2. high": "131.3700",
"3. low": "128.8300",
"4. close": "129.1500",
"5. adjusted close": "128.2466",
"6. volume": "38033900",
"7. dividend amount": "0.0000",
"8. split coefficient": "1.0000"
},
"2019-04-24": {
"1. open": "125.7900",
"2. high": "125.8500",
"3. low": "124.5200",
"4. close": "125.0100",
"5. adjusted close": "124.1356",
"6. volume": "31257000",
"7. dividend amount": "0.0000",
"8. split coefficient": "1.0000"
},
"2019-04-23": {
"1. open": "124.1000",
"2. high": "125.5800",
"3. low": "123.8300",
"4. close": "125.4400",
"5. adjusted close": "124.5626",
"6. volume": "24025500",
"7. dividend amount": "0.0000",
"8. split coefficient": "1.0000"
},
"2019-04-22": {
"1. open": "122.6200",
"2. high": "124.0000",
"3. low": "122.5700",
"4. close": "123.7600",
"5. adjusted close": "122.8943",
"6. volume": "15648700",
"7. dividend amount": "0.0000",
"8. split coefficient": "1.0000"
},
"2019-04-18": {
"1. open": "122.1900",
"2. high": "123.5200",
"3. low": "121.3020",
"4. close": "123.3700",
"5. adjusted close": "122.5071",
"6. volume": "27991000",
"7. dividend amount": "0.0000",
"8. split coefficient": "1.0000"
},
"2019-04-17": {
"1. open": "121.2400",
"2. high": "121.8500",
"3. low": "120.5468",
"4. close": "121.7700",
"5. adjusted close": "120.9183",
"6. volume": "19300900",
"7. dividend amount": "0.0000",
"8. split coefficient": "1.0000"
},
"2019-04-16": {
"1. open": "121.6400",
"2. high": "121.6430",
"3. low": "120.1000",
"4. close": "120.7700",
"5. adjusted close": "119.9253",
"6. volume": "14071800",
"7. dividend amount": "0.0000",
"8. split coefficient": "1.0000"
},
"2019-04-15": {
"1. open": "120.9400",
"2. high": "121.5800",
"3. low": "120.5700",
"4. close": "121.0500",
"5. adjusted close": "120.2033",
"6. volume": "15792600",
"7. dividend amount": "0.0000",
"8. split coefficient": "1.0000"
},
"2019-04-12": {
"1. open": "120.6400",
"2. high": "120.9800",
"3. low": "120.3700",
"4. close": "120.9500",
"5. adjusted close": "120.1040",
"6. volume": "19745100",
"7. dividend amount": "0.0000",
"8. split coefficient": "1.0000"
},
"2019-04-11": {
"1. open": "120.5400",
"2. high": "120.8515",
"3. low": "119.9200",
"4. close": "120.3300",
"5. adjusted close": "119.4883",
"6. volume": "14209100",
"7. dividend amount": "0.0000",
"8. split coefficient": "1.0000"
},
"2019-04-10": {
"1. open": "119.7600",
"2. high": "120.3500",
"3. low": "119.5400",
"4. close": "120.1900",
"5. adjusted close": "119.3493",
"6. volume": "16477200",
"7. dividend amount": "0.0000",
"8. split coefficient": "1.0000"
},
"2019-04-09": {
"1. open": "118.6300",
"2. high": "119.5400",
"3. low": "118.5774",
"4. close": "119.2800",
"5. adjusted close": "118.4457",
"6. volume": "17612000",
"7. dividend amount": "0.0000",
"8. split coefficient": "1.0000"
},
"2019-04-08": {
"1. open": "119.8100",
"2. high": "120.0200",
"3. low": "118.6400",
"4. close": "119.9300",
"5. adjusted close": "119.0911",
"6. volume": "15116200",
"7. dividend amount": "0.0000",
"8. split coefficient": "1.0000"
},
"2019-04-05": {
"1. open": "119.3900",
"2. high": "120.2300",
"3. low": "119.3700",
"4. close": "119.8900",
"5. adjusted close": "119.0514",
"6. volume": "15826200",
"7. dividend amount": "0.0000",
"8. split coefficient": "1.0000"
},
"2019-04-04": {
"1. open": "120.1000",
"2. high": "120.2300",
"3. low": "118.3800",
"4. close": "119.3600",
"5. adjusted close": "118.5251",
"6. volume": "20112800",
"7. dividend amount": "0.0000",
"8. split coefficient": "1.0000"
}
}
}
</details>
1. The 5 year history of Apple stock prices (IEX API)
1. All the Swift language repos on Github with Pursuit in their name
1. A list of all Pokemon
1. A list of all items in Fortnite
1. A list of all Game of Thrones Episodes.
1. A list of all songs with "Love" in the title.
1. All information about Petyr Baelish from the Game of Thrones books
1. All the movies Leonardo Dicaprio has acted in
