<p align="center">
  <img src="https://media.licdn.com/dms/image/D4D12AQE_SAR61tWqBw/article-cover_image-shrink_720_1280/0/1696007532362?e=2147483647&v=beta&t=gHcB0ZSMKfLNU_lfFE6j16VSaYdDxTzbbg4F629EBD4" alt="ceh" width="200"/>
</p>

# Footprinting and Reconnaissance

## DNS
<details>
  <summary>Gobuster</summary>
  
  ```plaintext
  gobuster vhost -u http://example.com -w /DNS_wordlist.txt --append-domain
```
</details>

<details>
  <summary>FFUF</summary>
  
  ```plaintext
  ffuf -u http://example.com -w /DNS-wordlist.txt -H "HOST:FUZZ.example.com"
```
</details>
