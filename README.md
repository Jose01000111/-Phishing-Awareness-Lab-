# 🧪 Phishing Awareness Lab – "Oops, You Clicked It!"

## 🛠️ LAB GOAL
In this lab, I am simulating a phishing awareness campaign by sending carefully crafted phishing links to my friends and family. The goal is to help them recognize phishing attempts and understand the risks involved. To keep the campaign realistic and engaging, I created landing pages in both English and Spanish, directing recipients to language-appropriate phishing awareness pages.

Through this hands-on exercise, I also deepen my understanding of what a malicious actor might do to inject viruses or perform other harmful actions, all while keeping the simulation ethical, safe, and educational.

## 🔧 PART 1: SET UP THE PHISHING SITE (ROCKY LINUX)
### 💪 Step 1: Install Apache, PHP, and Utilities
### 📁 Step 2: Create the Campaign Directory
### ✍️ Step 3: Create English Page
### ✍️ Step 4: Create Spanish Page
## 📊 PART 2: ENABLE BASIC ANALYTICS
### 🐾 Step 1: Enable Access Logging (Default)
## 📲 PART 3: SEND TEXTS WITH TWILIO
### ✨ Step 0: Set Up a Free Twilio Account
### 📋 Step 1: Save Contacts as contacts.csv
## 🕒 Step 2: Create send_sms.sh
###🪥 PART 4: SAFETY + HTTPS
## ▶️ RUNNING THE LAB
### ✅ Start Apache (if not running)
### 🔥 Check Firewall for HTTP and HTTPS ports
### 🌐 Check your phishing pages
### 📲 Send the messages

## 🧰 TECHNOLOGY STACK
Operating System: Rocky Linux

Web Server: Apache HTTP Server

Scripting Language: PHP (for potential future enhancements)

Messaging Service: Twilio API (for sending SMS phishing links)

Tools: curl, nano, firewall-cmd, bash scripting

Security: HTTPS via Certbot (Let’s Encrypt) for secure communication

## 🐞 Step: Fix Code and Verify Case Sensitivity
If my SMS messages fail to send, I need to fix some code and double-check my Account SID and Auth Token to make sure every uppercase and lowercase letter matches exactly. These credentials are case-sensitive, so even one wrong letter breaks authentication.

## 🚧 Step: Fix File Names for Consistency
If I accidentally named files differently than the lab instructions (for example, phishing-ex.html instead of phishing-en.html), I must rename them to keep everything clear and consistent.

I use the mv command to rename files quickly:

