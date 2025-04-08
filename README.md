# MrBlackEye DDoS Script V1


# MrBlackEye
## _______________ Description ________________
MrBlackEye DDos Script - Description

The **MrBlackEye DDos Script** is a powerful tool designed for testing the resilience of web servers against Distributed Denial of Service (DDoS) attacks. Created with the intention of simulating high traffic loads, this script is useful for network administrators and security professionals who wish to stress-test their server's capacity and performance under extreme conditions.

## Installation
#### Update Your All Package
```bash
apt update 
apt upgrade -y 
```
#### Install Required Package
```
pkg install git -y 
pkg install python -y 
pkg install python2 -y
pkg install python3 -y
pkg install python-pip
```
#### Clone This Repository
```bash
git clone https://github.com/mrdavid404/MrBlackEye.git
cd MrBlackEye 
```
#### Run This Script 
```
cd MrBlackEye
python3 MrBlackEye404.py
```

## Key Features:

- **Multi-threaded:** The script allows you to configure multiple threads (turbo) to increase the intensity of the attack, enabling you to simulate a high volume of simultaneous requests.

- **Customizable Parameters:** Users can easily set the target server IP (-s), port (-p), and the number of threads (-t) to match specific testing scenarios.

- **Socket-Based Attack:** It uses raw socket connections to send requests, mimicking the behavior of real botnets.

- **User-Agent Randomization:** The script allows for randomization of user-agent headers, making it more difficult for basic protections to detect and block the attack.

- **Real-Time Feedback:** It provides feedback to the user, displaying the attack parameters such as the target host, port, and turbo thread count, and indicating the progress of the attack.

- **Simple Command-Line Interface:** Easy to use through the command line with minimal setup required.


## Usage Warning: 
This script should only be used for ethical testing and educational purposes on servers that you own or have explicit permission to test. Unauthorized use on third-party servers can be illegal and result in severe penalties. Always ensure that you have appropriate authorization before conducting any security tests.

## Disclaimer:
>The MrBlackEye DDoS script is intended solely for lawful penetration testing and research. Misuse of this tool can lead to legal consequences. Always follow ethical guidelines and ensure proper permission before using this script.

## Authors
- Name    :  AH Showev (PRINCE)
- GitHub  :  @mrdavid404
- [Telegram](https://t.me/mrdavid404_bot)
