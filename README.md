![image](https://github.com/user-attachments/assets/772c8ca5-60cc-49de-b666-b570a576d026)

# Depined-Auto-Bot

Depined Auto Bot

---

## Features

- **Account Management**: Monitor and manage multiple accounts with ease.
- **Proxy Support**: Use HTTP, HTTPS, or SOCKS proxies for secure connections.
- **Real-Time Stats**: View points, activity logs, and status updates in a dynamic table.

---

## Steps to Join

1. **Join Here**: [https://app.depined.org/onboarding](https://app.depined.org/onboarding)

2. **Sign Up with Email**: Create an account using your email address.

3. **Submit Access Code**: Use the access code: `MrfpB9A4tCOe`

4. **Download the Extension**: Install the Depined extension from the Chrome Web Store:  
   [Depined Extension on Chrome Web Store](https://chromewebstore.google.com/detail/depined/pjlappmodaidbdjhmhifbnnmmkkicjoc)

5. **Run for 25 Hours**: To activate your referral code, you need to run the extension for 10 hours.

6. **Start Earning**: Once the referral code is activated, you can start earning!

---

## Installation

### Prerequisites

Ensure you have the following installed:
- **Node.js** (version 16 or higher)
- **npm** (comes with Node.js)

## Installation
check your nodejs version 
```
node -v
```
![image](https://github.com/user-attachments/assets/184a3188-3920-4f1e-8b80-28b7aa0b93b5)

## ⚠️if your nodejs version was 16 or higher skip this part 
### ⚠️if you haven't install yet or lower version install new version 
```
curl -fsSL https://deb.nodesource.com/setup_23.x | sudo -E bash -
```
install nodejs
```
sudo apt install -y nodejs
```
check version
```
node -v
```
# Installation bot

1. Clone this repository

```bash
git clone https://github.com/mr1992vhy/Depined-bot.git
```
go to directory 
```
cd Depined-bot
```
2. Install dependencies

```bash
npm install
```
3. Fill Data

* for complete this section you need UserID
* 1- login to dashboard and isnpect the page ( F12 or click right and select Inspect )
 
*![image](https://github.com/user-attachments/assets/acba9224-705d-4a96-b375-203deef16c55)

* select network

![image](https://github.com/user-attachments/assets/8df5eaf7-e453-4c17-9d06-a2fd703f3e3c)

* select "Fetch/XHR" and refresh the page
* select "profile"
* scroll down until see "authorization"
* select yellow section start from "eyjh..."
* copy and paste it somewhere like notepad
* you can do it for all accounts ( if you want run multi account )

```bash
nano data.txt
```
![image](https://github.com/user-attachments/assets/7887cad8-fb84-4258-bbcd-a14e819e76a8)

* each account must be in ONE line like this picture ( example : I have 3 accounts here )

you can use proxy ( optional)
```
nano proxy.txt
```
create screen 
```
screen -S depined
```
4. Run Bot

```bash
npm run start
```
![image](https://github.com/user-attachments/assets/58808000-e22c-4d3e-a5c1-d14d6042b52c)

if anything is right you can close the screen by : Ctrl + A +D
- any time you want check the status run this command :
```
screen -r depined
```


## Disclaimer

This bot is for educational purposes only. Use it at your own risk. The developer is not responsible for any account-related issues or potential losses.
