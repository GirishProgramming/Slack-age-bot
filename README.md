# Slack Bot - Age Calculator

A simple Slack bot built with Go and the **slacker** package to calculate age based on the year of birth (YOB).

## 📌 Features
- Slack bot integration using Slack's Real Time Messaging (RTM) API.
- Calculates age based on YOB.
- Listens to commands in Slack and responds with the calculated age.

## 🛠 Tech Stack
- **Go** (Golang)
- **Slacker** (Slack Bot Framework)
- **Slack API** (Bot integration)

## 🚀 Getting Started

### 1️⃣ Clone the Repository
```sh
git clone https://github.com/your-username/slack-bot-age-calculator.git
cd slack-bot-age-calculator
2️⃣ Set Up Slack Tokens
To use this bot, you'll need Slack Bot Token and Slack App Token.

Go to Slack API and create a new app.

Generate your Bot Token and App Token from your Slack app settings.

3️⃣ Set Environment Variables
To set your Slack tokens in the environment, add the following to your .env file (make sure you don't commit this file to Git):

ini
Copy
Edit
SLACK_BOT_TOKEN=your_slack_bot_token
SLACK_APP_TOKEN=your_slack_app_token
Or, you can set them directly in your code (not recommended for production).

4️⃣ Install Dependencies
Install the required Go dependencies:

sh
Copy
Edit
go mod tidy
5️⃣ Run the Project
Run the bot with:

sh
Copy
Edit
go run main.go
6️⃣ Invite Bot to Your Slack Workspace
After starting the bot, invite it to your Slack workspace and use the following command:

csharp
Copy
Edit
my yob is <year>
For example:

csharp
Copy
Edit
my yob is 1990
The bot will respond with your age.

📖 Command
Command	Description
my yob is <year>	Calculates your age based on the year of birth (YOB).
📝 License
This project is open-source and available under the MIT License.

vbnet
Copy
Edit

This README includes all the details needed for someone to set up and use your Slack bot. Let me know if you need any mor
