# 🧪 Phishing Awareness Lab – "Oops, You Clicked It!"

## 🛠️ LAB GOAL
In this lab, I am simulating a phishing awareness campaign by sending carefully crafted phishing links to my friends and family. The goal is to help them recognize phishing attempts and understand the risks involved. To keep the campaign realistic and engaging, I created landing pages in both English and Spanish, directing recipients to language-appropriate phishing awareness pages.

Through this hands-on exercise, I also deepen my understanding of what a malicious actor might do to inject viruses or perform other harmful actions, all while keeping the simulation ethical, safe, and educational.

## 🔧 PART 1: SET UP THE PHISHING SITE (ROCKY LINUX)
### 💪 Step 1: Install Apache, PHP, and Utilities

![ASrUib8](https://github.com/user-attachments/assets/b1f83595-dd1b-41fd-89b2-9bf380907dc4)

![jAxjBs2](https://github.com/user-attachments/assets/8f611bdd-730b-4c9d-8d33-2e72932fcdb0)

![OPOCyLH](https://github.com/user-attachments/assets/461c3279-e6e6-48ae-957c-2abba1a4dce0)

### 📁 Step 2: Create the Campaign Directory

![Ri9Dj6b](https://github.com/user-attachments/assets/bf26930d-ec33-45a7-9fb8-f70477d8b410)

### ✍️ Step 3: Create English Page

![KrK78Py](https://github.com/user-attachments/assets/affb2650-00c1-4172-9c1b-ae32a2017d19)

### ✍️ Step 4: Create Spanish Page

![MR03Qyi](https://github.com/user-attachments/assets/e9752668-3ba3-4d8c-927e-ddca7b4139a7)

### ## 🚧 Step: Fix File Names for Consistency
If I accidentally named files differently than the lab instructions (for example, phishing-ex.html instead of phishing-en.html), I must rename them to keep everything clear and consistent.

### I use the mv command to rename files quickly:

![H0v7hwb](https://github.com/user-attachments/assets/3a2e4a09-6c58-461e-a234-0b30787bccc5)

## 📊 PART 2: ENABLE BASIC ANALYTICS

### 🐾 Step 1: Enable Access Logging 

![Nr8Eema](https://github.com/user-attachments/assets/1f9d7b4a-90d1-46c4-a1bf-0d978a585dc5)

## 📲 PART 3: SEND TEXTS WITH TWILIO

### ✨ Step 0: Set Up a Free Twilio Account

![7BQczF1](https://github.com/user-attachments/assets/ad4f7311-fbdc-477e-a583-dc1a031537df)

![KRwd9p0](https://github.com/user-attachments/assets/78e6de0d-9638-4837-845c-4d837e30dfe4)

# ☎️ Step: Twilio Verification Required

I had to verify phone numbers (or upgrade my account) in Twilio before I could successfully send messages during testing.

### 📋 Step 1: Save Contacts as contacts.csv
### (Had to keep the contacts information private)

![RYHMtU2](https://github.com/user-attachments/assets/a9e37b46-6cff-46a4-b9cd-429de391d762)

## 🕒 Step 2: Create send_sms.sh

![x4rIc4e](https://github.com/user-attachments/assets/2e2ab54a-b377-4b2a-9174-7d1f30655fab)

![KNZGNSO](https://github.com/user-attachments/assets/713fea83-c343-4c10-b74d-95ccd040fcc0)

###🪥 PART 4: SAFETY + HTTPS

![YgWhjj8](https://github.com/user-attachments/assets/f065a31b-912b-4c65-a0d3-4d69a295fee3)

![qCNwJAT](https://github.com/user-attachments/assets/bd282c21-640b-4902-95dd-93eb34049f32)

![SIhP6vm](https://github.com/user-attachments/assets/35d9d40b-ab46-441a-aca3-d072db435094)

![gDUnMZK](https://github.com/user-attachments/assets/7cad683a-c9df-4d76-86a5-a85b2587221a)

## ▶️ RUNNING THE LAB
### ✅ Start Apache (if not running)

![bR1vuFI](https://github.com/user-attachments/assets/26e0a250-df5a-4e72-ad0c-d1b866a05168)

### 🔥 Check Firewall for HTTP and HTTPS ports

![jNpIeUM](https://github.com/user-attachments/assets/393a0514-69dc-4aa6-a9a8-02e5ab6319a9)

### 🌐 Check your phishing pages

![Nhk1Xgn](https://github.com/user-attachments/assets/21d4ed5a-0904-4ed2-bfee-77c3566157d6)

![TRo656h](https://github.com/user-attachments/assets/00241fe9-6bdf-4f43-bd62-af2b56f3dabf)

## 🐞 Step: Fix Code and Verify Case Sensitivity
If my SMS messages fail to send, I need to fix some code and double-check my Account SID and Auth Token to make sure every uppercase and lowercase letter matches exactly. These credentials are case-sensitive, so even one wrong letter breaks authentication.

![WmvdYiW](https://github.com/user-attachments/assets/fc7c36b5-7d9b-4afd-8599-9bae1c9d2cb0)

### 📲 Send the messages

![rIVe7ke](https://github.com/user-attachments/assets/bd01e9c7-4d71-478e-9007-ceba922b9349)

![WdrDUoO](https://github.com/user-attachments/assets/ece9a050-90b1-45de-9050-c60b67e63790)

# Phishing Awarness campaign is live!
---

## 📚 Lessons Learned
💻 I learned how HTML syntax works to build simple, effective phishing awareness pages.

🐧 Linux really rocks—I got hands-on managing services and files on Rocky Linux.

🛠️ Bash scripting can be powerful and complex, requiring attention to detail.

📲 I used the Twilio API to send SMS messages programmatically.

🔐 Case sensitivity in Account SID and Auth Token is crucial—one wrong letter breaks things!

🌐 Setting up language-specific phishing pages made the campaign more engaging.

📡 Monitoring access logs helped me track who clicked the phishing links.

🔄 Troubleshooting file names and scripts kept my lab running smoothly.

🧑‍💻 I gained insight into how attackers might try to deliver malicious payloads via phishing.

---

## 🧰 TECHNOLOGY STACK
Operating System: Rocky Linux

Web Server: Apache HTTP Server

Scripting Language: PHP (for potential future enhancements)

Messaging Service: Twilio API (for sending SMS phishing links)

Tools: curl, nano, firewall-cmd, bash scripting

Security: HTTPS via Certbot (Let’s Encrypt) for secure communication

---

# 🔜 To Be Continued...
Now, I wait and watch to see who clicks the links and learn from their behavior.



