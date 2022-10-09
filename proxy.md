# proxy list

- https://github.com/clarketm/proxy-list
- https://github.com/TheSpeedX/PROXY-List
- https://github.com/ShiftyTR/Proxy-List
- https://github.com/jetkai/proxy-list

Socks5 for Telegram:
- https://github.com/hookzof/socks5_list 


```
curl -sSf "https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt" > proxy-list.txt

curl "http://pubproxy.com/api/proxy?limit=10&format=txt&http=true&country=US&type=http"

curl "http://pubproxy.com/api/proxy?limit=10&format=txt&type=socks5"

```
### For SOCKS5

```curl https://raw.githubusercontent.com/TheSpeedX/SOCKS-List/master/socks5.txt -o socks5.txt```

### For SOCKS4

```curl https://raw.githubusercontent.com/TheSpeedX/SOCKS-List/master/socks4.txt -o socks4.txt```

### For HTTP(S)

```curl https://raw.githubusercontent.com/TheSpeedX/SOCKS-List/master/http.txt -o http.txt```


```bash
# Download and save to local file `proxt-list.txt` with format `IP:PORT`
curl -sSf "https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt" > proxy-list.txt
```

### Format
```bash
######################
### proxy-list.txt ###
######################

IP [1]
|
| Port [2]
|   |
|   | Country [3]
|   |   |
|   |   | Anonymity [4]
|   |   |  |
|   |   |  |  Type [5]
|   |   |  |   |_ _ _ _
|   |   |  |_ _ _ _ _  | Google passed [6]
|   |   |_ _ _ _ _   | |  |
|   |_ _ _ _ _    |  | |  |
|             |   |  | |  |
200.2.125.90:8080 AR-N-S! +


1. IP address
2. Port number
3. Country code
4. Anonymity
   N = No anonymity
   A = Anonymity
   H = High anonymity
5. Type
     = HTTP
   S = HTTP/HTTPS
   ! = incoming IP different from outgoing IP
6. Google passed
   + = Yes
   – = No




