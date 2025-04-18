# Build an LLM Chat app in 5 minutes 
## Overview

This repository shows you how to build a simple chat app using Snowflake's API. 

<img width="500" alt="App Example" src="https://github.com/user-attachments/assets/77d46ef8-a4c8-481e-b07c-a81f4c6bbaed" />

## Instructions 

1. Clone this repo.

2. Sign up for a new Snowflake account [here](https://mlh.link/snowflake-signup). Activate your account by e-mail (see screenshot below), pick a username and password, and you should see a welcome screen.

<img width="500" src="https://github.com/user-attachments/assets/1a11cd4c-514d-4ac0-98b2-5e2207dc6698" />

3. Once you are logged in to Snowflake, click on your name in the bottom left corner, and select `Connect a tool to Snowflake`:

 <img width="294" alt="Screenshot 2025-04-15 at 9 08 27 PM" src="https://github.com/user-attachments/assets/d485f628-e397-4869-82d7-c5e1c1af24c0" />

  _\* if you can't find your login info, search your inbox for an e-mail from "Snowflake Computing"._
  
4. Use the information in the connect dialog to fill in your `secrets.toml` file:   

 <img width="500" src="https://github.com/user-attachments/assets/c4839cb9-585f-4af7-a7fb-40c328153786" />

  ```
[snowflake]
account = "[Account Identifier]"
user = "[User Name]"
password = "[Same as when you signed up. Be careful here and don't check this in to GitHub!"
role = "[Role]"
host = "[Account/Server URL]"
```

5. Run `pip install -r requirements.txt` to make sure you have all the dependencies working.

6. Run `streamlit run streamlit.app` and you should see a simple chat app ready to chat with you! Try changing the model used: `mistral-large2`, `claude-3-5-sonnet` or `llama3.1-70b` and compare the chat interaction! 
