work in progress, star and follow to track progress

![DALL·E 2024-04-20 23 27 00 - Create a digital banner for the GitHub repository named 'HackerToolkit', ensuring it mirrors the previous design closely with only one change correct](https://github.com/ChrisJr404/HackerToolkit/assets/11917633/170bf9c2-03c0-40ef-a9e9-230c76f65122)

# Welcome to the HackerToolkit 🛠️

**Your comprehensive suite for penetration testing and bug bounty hunting.**

Whether you're a seasoned penetration tester or just starting out in the world of bug bounty hunting, HackerToolkit offers a curated selection of tools designed to enhance your hacking capabilities. This repository not only organizes these tools but provides information about them.

## Features:
- **Complete Tool Listings:** Access a meticulously organized list of tools included in the `install.sh` file, each with a detailed description to help you understand and choose the right tool for the right job.
- **Quick Installation:** Get up and running quickly with our `install.sh` script that allows you to download and install all tools at once (unless noted) — streamlining your setup process and saving you valuable time.
- **Cross-Distribution Compatibility:** Originally tailored for Kali Linux, our toolkit is compatible with many other Linux distributions, ensuring flexibility regardless of your preferred environment.

## Installation Instructions:
1. **Clone the Repository:** `git clone https://github.com/ChrisJr404/HackerToolkit.git`
2. **Navigate to the Repository:** `cd HackerToolkit`
3. **Run the Installation Script:** `./install.sh`

Embrace the power of a comprehensive hacking suite with HackerToolkit. Star the repo and follow me to stay updated with the latest tools and improvements!

# Enumeration & Recon Tools
## Ad & Analytic Trackers
### relations.sh
Find related domains and subdomains by looking at a target’s ad/analytics tracker codes
* https://gist.github.com/hateshape/393ab7003023f3b13126a4892100c8ff

![Google_Analytics_Tracking_Code](https://github.com/ChrisJr404/HackerToolkit/assets/11917633/89a9192a-e9ea-4847-96e6-7b30827d9812)

## Apex Domain Enumeration
### check_mdi
Python script to enumerate valid Microsoft 365 domains, retrieve tenant name, and check for a Microsoft Defender for Identity (MDI) instance.
* https://github.com/expl0itabl3/check_mdi

![Fpg1kqZWABgCJGx](https://github.com/ChrisJr404/HackerToolkit/assets/11917633/9c60b863-4c6c-4fba-b631-5e3b325cfd9c)

### CloudRecon
Finding assets and subdomains from certificates! Scan the web! 
* https://github.com/g0ldencybersec/CloudRecon

![324196773-8fe87016-1459-4d3a-a964-6b169325ec8c](https://github.com/ChrisJr404/HackerToolkit/assets/11917633/9190fd8b-8017-44f2-a14b-4dbd9f9d8b8d)

### FavFreak
Use favicon.ico hashes for finding new assets/IP addresses and technologies owned by a company.
* https://github.com/devanshbatham/FavFreak

![68747470733a2f2f63646e2d696d616765732d312e6d656469756d2e636f6d2f6d61782f313230302f312a737176314b4c6f354242614c4b5347535577465566772e706e67](https://github.com/ChrisJr404/HackerToolkit/assets/11917633/2aeb847e-f3fe-4a7f-a653-8b4236c5d391)

## Github Enumeration
### github-search
Perform code search through GitHub API. Finds contributors, dorks, employees, endpoints, secrets, subdomains, users, etc. 
* https://github.com/gwen001/github-search

![github-search](https://github.com/ChrisJr404/HackerToolkit/assets/11917633/0a689973-fac3-4e25-9479-c25eae0ca733)

## Port Scanners (Active)
### Naabu
Naabu is a port scanning tool written in Go that allows you to enumerate valid ports for hosts in a fast and reliable manner. It is a really simple tool that does fast SYN/CONNECT/UDP scans on the host/list of hosts and lists all ports that return a reply. Most usable port scanner.
* https://github.com/projectdiscovery/naabu

![180417395-25b1b990-c032-4b5c-9b66-03b58db0789a](https://github.com/ChrisJr404/HackerToolkit/assets/11917633/6259ec60-d179-451f-8cfb-b1fa3ad7ca8f)

### Nmap
Most extensible scanner.
* https://github.com/nmap/nmap

![image](https://github.com/ChrisJr404/HackerToolkit/assets/11917633/b785b1bc-2fc0-4bc8-bda4-3f7de4153368)

### RustScan
RustScan is empirically the fastest modern port scanner.
* https://github.com/RustScan/RustScan

![fast](https://github.com/ChrisJr404/HackerToolkit/assets/11917633/07ee2643-76d3-4023-aa14-c91b5568336e)

## Port Scanners (Passive) 
### Smap
Smap is a port scanner built with shodan.io's free API. It takes same command line arguments as Nmap and produces the same output which makes it a drop-in replacament for Nmap.
* https://github.com/s0md3v/Smap

![smap-demo](https://github.com/ChrisJr404/HackerToolkit/assets/11917633/add08959-8071-46df-9852-dbbeaade4deb)

## Recon Frameworks
### reconFTW
reconFTW automates the entire process of reconnaissance for you. It outperforms the work of subdomain enumeration along with various vulnerability checks and obtaining maximum information about your target.
* https://github.com/six2dez/reconftw

![mindmap_obsidian](https://github.com/ChrisJr404/HackerToolkit/assets/11917633/d39f578b-eeeb-4741-a131-efe8de6eae11)

### reNgine
reNgine is your go-to web application reconnaissance suite that's designed to simplify and streamline the reconnaissance process for security professionals, penetration testers, and bug bounty hunters. With its highly configurable engines, data correlation capabilities, continuous monitoring, database-backed reconnaissance data, and an intuitive user interface, reNgine redefines how you gather critical information about your target web applications. 
* https://github.com/yogeshojha/rengine

![164993749-1ad343d6-8ce7-43d6-aee7-b3add0321da7](https://github.com/ChrisJr404/HackerToolkit/assets/11917633/efed20d0-285a-4fd2-857d-f3ffe5f3e0c4)

## Shodan Tools
### karma v2
𝚔𝚊𝚛𝚖𝚊 𝚟𝟸 can be used by Infosec Researchers, Penetration Testers, Bug Hunters to find deep information, more assets, WAF/CDN bypassed IPs, Internal/External Infra, Publicly exposed leaks and many more about their target. Shodan Premium API key is required to use this automation. Output from the 𝚔𝚊𝚛𝚖𝚊 𝚟𝟸 is displayed to the screen and saved to files/directories. 
* https://github.com/Dheerajmadhukar/karma_v2

![image](https://github.com/ChrisJr404/HackerToolkit/assets/11917633/2f317bed-b64f-4067-a848-e5e621429b1c)

### shosubgo
Small tool to Grab subdomains using Shodan api.
* https://github.com/incogbyte/shosubgo

![shosubgo](https://github.com/ChrisJr404/HackerToolkit/assets/11917633/b29be12b-4a8b-4f19-a0a4-7e78836bc6fc)

### Smap
Smap is a port scanner built with shodan.io's free API. It takes same command line arguments as Nmap and produces the same output which makes it a drop-in replacament for Nmap.
* https://github.com/s0md3v/Smap

![smap-demo](https://github.com/ChrisJr404/HackerToolkit/assets/11917633/add08959-8071-46df-9852-dbbeaade4deb)

### wtfis
Passive hostname, domain and IP lookup tool for non-robots.
* https://github.com/pirxthepilot/wtfis

![demo](https://github.com/ChrisJr404/HackerToolkit/assets/11917633/11088982-3350-48ec-a070-b913e3bbcdca)

## Screenshotting
### Aquatone
Aquatone is a tool for visual inspection of websites across a large amount of hosts and is convenient for quickly gaining an overview of HTTP-based attack surface.
* https://github.com/michenriksen/aquatone

![rszscreenshot280](https://github.com/ChrisJr404/HackerToolkit/assets/11917633/ef2532ae-4c9e-40b3-95df-81a09ff0d508)

### Eyeballer
Eyeballer is meant for large-scope network penetration tests where you need to find "interesting" targets from a huge set of web-based hosts. Go ahead and use your favorite screenshotting tool like normal (EyeWitness or GoWitness) and then run them through Eyeballer to tell you what's likely to contain vulnerabilities, and what isn't.
* https://github.com/BishopFox/eyeballer

![eyeballer_logo](https://github.com/ChrisJr404/HackerToolkit/assets/11917633/7627421d-aaca-44fa-b397-8fc2af6ef98e)

### EyeWitness
EyeWitness is designed to take screenshots of websites provide some server header info, and identify default credentials if known.
* https://github.com/RedSiege/EyeWitness

![image](https://github.com/ChrisJr404/HackerToolkit/assets/11917633/27da8e8a-a63b-418c-ab9a-c9131b3fdd80)

### go-stare
A fast & light web screenshot without headless browser but Chrome DevTools Protocol!
* https://github.com/dwisiswant0/go-stare

![94014291-86398780-fdd5-11ea-803d-4eb3ec64bd7b](https://github.com/ChrisJr404/HackerToolkit/assets/11917633/af9d996a-e4a6-4e14-9504-5ccdc7676cd6)

### httpscreenshot
HTTPScreenshot is a tool for grabbing screenshots and HTML of large numbers of websites. The goal is for it to be both thorough and fast which can sometimes oppose each other.
* https://github.com/breenmachine/httpscreenshot

![image](https://github.com/ChrisJr404/HackerToolkit/assets/11917633/edd505fc-d48f-47de-bddf-50c4913560cd)

### httpx
httpx is a fast and multi-purpose HTTP toolkit that allows running multiple probes using the retryablehttp library. It is designed to maintain result reliability with an increased number of threads.
* https://github.com/projectdiscovery/httpx

![135731750-4c1d38b1-bd2a-40f9-88e9-3c4b9f6da378](https://github.com/ChrisJr404/HackerToolkit/assets/11917633/58e90897-e35c-4e6a-ad80-40fc79e50b90)

## Spiders
### GoSpider is a fast web spider written in Go
* https://github.com/jaeles-project/gospider

![Example12](https://github.com/ChrisJr404/HackerToolkit/assets/11917633/b741fa50-f7a9-4cc1-97d4-5dc37e8026bd)

### hakrawler
Fast golang web crawler for gathering URLs and JavaScript file locations. This is basically a simple implementation of the awesome Gocolly library.
* https://github.com/hakluke/hakrawler

![1 kpuT3tZ7bS5qSLJPQa_7IQ](https://github.com/ChrisJr404/HackerToolkit/assets/11917633/16ebc455-da68-4f32-a78e-d744f50122cc)

## Subdomain Enumeration and Brute Force
### Altdns
Altdns is a DNS recon tool that allows for the discovery of subdomains that conform to patterns. Altdns takes in words that could be present in subdomains under a domain (such as test, dev, staging) as well as takes in a list of subdomains that you know of.
* https://github.com/infosec-au/altdns

![68747470733a2f2f692e696d6775722e636f6d2f4a7966756532362e706e67](https://github.com/ChrisJr404/HackerToolkit/assets/11917633/2de07fcf-2473-4854-b92d-d9dfe4234463)

### AlterX
Fast and customizable subdomain wordlist generator using DSL.
* https://github.com/projectdiscovery/alterx

![229380735-140d3f25-d0cb-461d-8c49-4c1eff43d1f4](https://github.com/ChrisJr404/HackerToolkit/assets/11917633/653389cb-db3f-486d-92fe-aabf48da7c5f)

### Amass
The OWASP Amass Project performs network mapping of attack surfaces and external asset discovery using open source information gathering and active reconnaissance techniques.
* https://github.com/owasp-amass/amass

![image](https://github.com/ChrisJr404/HackerToolkit/assets/11917633/2d260a63-e529-444d-aadb-7099d59a8b01)

### BBOT
BBOT (Bighuge BLS OSINT Tool) is a recursive internet scanner inspired by Spiderfoot, but designed to be faster, more reliable, and friendlier to pentesters, bug bounty hunters, and developers.
* https://github.com/blacklanternsecurity/bbot

![296080072-53e07e9f-50b6-4b70-9e83-297dbfbcb436](https://github.com/ChrisJr404/HackerToolkit/assets/11917633/3250d9e2-a31e-40a6-b08a-0744aeb3ced8)

### CloudRecon
Finding assets and subdomains from certificates! Scan the web! 
* https://github.com/g0ldencybersec/CloudRecon

![324196773-8fe87016-1459-4d3a-a964-6b169325ec8c](https://github.com/ChrisJr404/HackerToolkit/assets/11917633/9190fd8b-8017-44f2-a14b-4dbd9f9d8b8d)

### dnsgen
This tool generates a combination of domain names from the provided input. Combinations are created based on wordlist. Custom words are extracted per execution.
* https://github.com/AlephNullSK/dnsgen

![68747470733a2f2f307870617472696b2e636f6d2f636f6e74656e742f696d616765732f323031392f30392f646e7367656e2d312e706e67](https://github.com/ChrisJr404/HackerToolkit/assets/11917633/15a9dd87-f5b1-4537-b20d-417813dbf802)

### FavFreak
Use favicon.ico hashes for finding new assets/IP addresses and technologies owned by a company.
* https://github.com/devanshbatham/FavFreak

![68747470733a2f2f63646e2d696d616765732d312e6d656469756d2e636f6d2f6d61782f313230302f312a737176314b4c6f354242614c4b5347535577465566772e706e67](https://github.com/ChrisJr404/HackerToolkit/assets/11917633/2aeb847e-f3fe-4a7f-a653-8b4236c5d391)

### github-subdomains
This Go tool performs searches on GitHub and parses the results to find subdomains of a given domain. May have to run several times to get complete results.
* https://github.com/gwen001/github-subdomains

![preview](https://github.com/ChrisJr404/HackerToolkit/assets/11917633/82c6bbc7-2520-463f-a4a2-73e2687f1924)

### puredns
puredns is a fast domain resolver and subdomain bruteforcing tool that can accurately filter out wildcard subdomains and DNS poisoned entries.
* https://github.com/d3mondev/puredns

![puredns-terminal](https://github.com/ChrisJr404/HackerToolkit/assets/11917633/63f23c67-331d-47b1-9756-36665b265e5a)

### shosubgo
Small tool to Grab subdomains using Shodan api.
* https://github.com/incogbyte/shosubgo

![shosubgo](https://github.com/ChrisJr404/HackerToolkit/assets/11917633/b29be12b-4a8b-4f19-a0a4-7e78836bc6fc)

### Subfinder
Subdomain discovery tool that returns valid subdomains for websites, using passive online sources. It has a simple, modular architecture and is optimized for speed. 
* https://github.com/projectdiscovery/subfinder

![subfinder-run](https://github.com/ChrisJr404/HackerToolkit/assets/11917633/adde8c28-c77a-48b1-84c6-9744c042eec9)

### SubreconGPT
This (VERY BETA) Python script performs AI-assisted subdomain discovery. It takes a list of subdomains as input, generates similar subdomains using the OpenAI GPT-3 model, and attempts to resolve these subdomains.
* https://github.com/jhaddix/SubreconGPT

![324197238-19ae48c3-2d04-4e24-a0c7-5e5cd29dfbe8](https://github.com/ChrisJr404/HackerToolkit/assets/11917633/481076b1-8761-4351-92bc-dca5e8fda281)

# Burp Suite Extensions (Doesn't Automatically Install)
### Active Scan++
ActiveScan++ extends Burp Suite's active and passive scanning capabilities. Designed to add minimal network overhead, it identifies application behaviour that may be of interest to advanced testers.
* https://portswigger.net/bappstore/3123d5b5f25c4128894d97ea1acc4976

### Additional Scanner Checks
This extension provides some additional passive Scanner checks such as: DOM-based XSS, HTTP -> HTTPS redirection, missing HTTP headres, and more. 
* https://portswigger.net/bappstore/a158fd3fc9394253be3aa0bc4c181d1f

### Agartha LFI, RCE, SQLi, Auth, HTTP to JS
Agartha creates payloads to reveal injection flaws, generates user request/response tables to spot access violations, and converts Http requests to JavaScript code for further XSS exploitation.
* https://portswigger.net/bappstore/b4915681326648b1a12e4059d71bc909

### AutoRepeater
This extension automatically repeats requests, with replacement rules and response diffing. It provides a general-purpose solution for streamlining authorization testing within web applications.
* https://portswigger.net/bappstore/f89f2837c22c4ab4b772f31522647ed8

### Autorize
Autorize is an extension aimed at helping the penetration tester to detect authorization vulnerabilities, one of the more time-consuming tasks in a web application penetration test. It is sufficient to give to the extension the cookies of a low privileged user and navigate the website with a high privileged user. The extension automatically repeats every request with the session of the low privileged user and detects authorization vulnerabilities. It is also possible to repeat every request without any cookies in order to detect authentication vulnerabilities in addition to authorization ones.
* https://portswigger.net/bappstore/f9bbac8c4acf4aefa4d7dc92a991af2f

### Burp Bounty Scan Check Builder
This BurpSuite extension allows you, in a quick and simple way, to improve the active and passive BurpSuite scanner by means of personalized rules through a very intuitive graphical interface. Through an advanced search of patterns and an improvement of the payload to send, we can create our own issue profiles both in the active scanner and in the passive.
* https://portswigger.net/bappstore/618f0b2489564607825e93eeed8b9e0a

### Collaborator Everywhere
This extension augments your in-scope proxy traffic by injecting non-invasive headers designed to reveal backend systems by causing pingbacks to Burp Collaborator.
* https://portswigger.net/bappstore/2495f6fb364d48c3b6c984e226c02968

### Content Type Convertor
This extension converts data submitted within requests between various common formats. This is useful for discovering vulnerabilities that can only be found by converting the content type of a request.
* https://portswigger.net/bappstore/db57ecbe2cb7446292a94aa6181c9278

### CORS Additional Checks
This extension can be used to test websites for CORS misconfigurations. It can spot trivial misconfigurations, like arbitrary origin reflection, but also more subtle ones where a regex is not properly configured.
* https://portswigger.net/bappstore/420a28400bad4c9d85052f8d66d3bbd8

### Error Message Checks
This extension passively reports detailed server error messages.
* https://portswigger.net/bappstore/4f01db4b668c4126a68e4673df796f0f

### Flow
This extension provides a Proxy history-like view along with search filter capabilities for all Burp tools. Requests without responses received are also shown and they are later updated as soon as response is received. This might be helpful to troubleshoot e.g. scanning issues.
* https://portswigger.net/bappstore/ee1c45f4cc084304b2af4b7e92c0a49d

### Freddy Deserialization Bug Finder
Helps with detecting and exploiting serialization in libraries and APIs.
* https://portswigger.net/bappstore/ae1cce0c6d6c47528b4af35faebc3ab3

### HTTP Request Smuggler
This is an extension for Burp Suite designed to help you launch HTTP Request Smuggling attacks. It supports scanning for Request Smuggling vulnerabilities, and also aids exploitation by handling cumbersome offset-tweaking for you.
* https://portswigger.net/bappstore/aaaa60ef945341e8a450217a54a11646

### Java Deserialization Scanner
The extension allows the user to discover and exploit Java Deserialization Vulnerabilities with different encodings (Raw, Base64, Ascii Hex, GZIP, Base64 GZIP).
* https://portswigger.net/bappstore/228336544ebe4e68824b5146dbbd93ae

### InQL - GraphQL Scanner
This Burp extension is designed to assist in your GraphQL security testing efforts.
* https://portswigger.net/bappstore/296e9a0730384be4b2fffef7b4e19b1f

### JS Miner
This tool tries to find interesting stuff inside static files; mainly JavaScript and JSON files. Scans for secrets, credentials, subdomains, cloud URLs, API endpoints, etc.
* https://portswigger.net/bappstore/0ab7a94d8e11449daaf0fb387431225b

### JSON Web Tokens
JSON Web Tokens (JWT4B) lets you decode and manipulate JSON web tokens on the fly, check their validity and automate common attacks.
* https://portswigger.net/bappstore/f923cbf91698420890354c1d8958fee6

### Param Miner
This extension identifies hidden, unlinked parameters. It's particularly useful for finding web cache poisoning vulnerabilities. It combines advanced diffing logic from Backslash Powered Scanner with a binary search technique to guess up to 65,536 param names per request. Param names come from a carefully curated built in wordlist, and it also harvests additional words from all in-scope traffic.
* https://portswigger.net/bappstore/17d2949a985c4b7ca092728dba871943

### Software Vulnerability Scanner
This extension scans for vulnerabilities in detected software versions using the Vulners.com API. 
* https://portswigger.net/bappstore/c9fb79369b56407792a7104e3c4352fb

### SQLiPy Sqlmap Integration
This extension integrates Burp Suite with SQLMap.
* https://portswigger.net/bappstore/f154175126a04bfe8edc6056f340f52e

### Reflected Parameters
This extension monitors traffic and looks for request parameter values (longer than 3 characters) that are reflected in the response.
* https://portswigger.net/bappstore/8e8f6bb313db46ba9e0a7539d3726651

### Turbo Intruder
Turbo Intruder is a Burp Suite extension for sending large numbers of HTTP requests and analyzing the results. It's intended to complement Burp Intruder by handling attacks that require extreme speed or complexity.
* https://portswigger.net/bappstore/9abaa233088242e8be252cd4ff534988

# Firefox Browser Extensions (Doesn't Automatically Install)
### Cookie-Editor
Efficiently create, edit and delete a cookie for the current tab. Perfect for developing, quickly testing or even manually managing your cookies for your privacy.
* https://addons.mozilla.org/en-US/firefox/addon/cookie-editor/

### FoxyProxy
FoxyProxy is an open-source, advanced proxy management tool that completely replaces Firefox's limited proxying capabilities. No paid accounts are necessary; bring your own proxies or buy from any vendor.
* https://addons.mozilla.org/en-US/firefox/addon/foxyproxy-standard/

### Firefox Multi-Account Containers
Firefox Multi-Account Containers lets you keep parts of your online life separated into color-coded tabs. Cookies are separated by container, allowing you to use the web with multiple accounts and integrate Mozilla VPN for an extra layer of privacy.
* https://addons.mozilla.org/en-US/firefox/addon/multi-account-containers/

### HackTools
Hacktools, is a web extension facilitating your web application penetration tests, it includes cheat sheets as well as all the tools used during a test such as XSS payloads, Reverse shells to test your web application.
* https://addons.mozilla.org/en-US/firefox/addon/hacktools/

### Open Multiple URLs
Opens a list of URLs
* https://addons.mozilla.org/en-US/firefox/addon/open-multiple-urls/

### PwnFox
PwnFox is a Firefox/Burp extension that provide usefull tools for your security audit. Single click BurpProxy, Containers Profiles, PostMessage Logger, Toolbox injection, and Security header remover
* https://addons.mozilla.org/en-US/firefox/addon/pwnfox/

### Shodan
The Shodan plugin tells you where the website is hosted (country, city), who owns the IP and what other services/ ports are open.
* https://addons.mozilla.org/en-US/firefox/addon/shodan-addon/

### Wappalyzer
Wappalyzer is a browser extension that uncovers the technologies used on websites. It detects content management systems, eCommerce platforms, web servers, JavaScript frameworks, analytics tools and many more.
* https://addons.mozilla.org/en-US/firefox/addon/wappalyzer/

### WhatRuns
Discover what runs a website - This Firefox extension helps you identify technologies used on any website at the click of a button.
* https://addons.mozilla.org/en-US/firefox/addon/whatruns/
