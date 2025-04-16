# Build an LLM Chat app in 5 minutes 
## Overview

This repository shows you how to build a simple chat app using Snowflake's API. 

<img width="500" alt="Screenshot 2025-03-07 at 12 04 05 AM" src="https://github.com/user-attachments/assets/889a971b-2c04-4b57-a43d-a1c626b290bf" />

## Instructions 

1. Clone this repo. 

2. Sign up for an account [here](https://signup.snowflake.com/?utm_source=github&utm_campaign=cortex-rest-api-demo). Activate your account and you should see a welcome screen. 

3. Create a folder called `.streamlit` and a file called `secrets.toml` inside.
  
4. Click on your name in the bottom left corner, and select `Connect a tool to Snowflake`. Use the dialog to fill out your information, replacing values in `[]` like so: 

  ```
[snowflake]
account = "[Account Identifier]"
user = "[User Name]"
password = "[Same as when you signed up. Be careful here and don't check this in to GitHub!"
role = "[Role]"
host = "[Account/Server URL]"
```

9. Run `pip install -r requirements.txt` to make sure you have all the dependencies working.

10. Run `streamlit run streamlit.app` and you should see a simple chat app ready to chat with you! Try changing the model used: `mistral-large2`, `claude-3-5-sonnet` or `llama3.1-70b` and compare the chat interaction! 
