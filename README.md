# Build an LLM Chat app in 5 minutes 
## Overview

This repository shows you how to build a simple chat app using Snowflake's API. 

<img width="500" alt="Screenshot 2025-04-15 at 9 07 42 PM" src="https://github.com/user-attachments/assets/77d46ef8-a4c8-481e-b07c-a81f4c6bbaed" />

## Instructions 

1. Clone this repo.

2. Create a folder called `.streamlit` and a file called `secrets.toml` inside.

3. Sign up for a new Snowflake account [here](https://mlh.link/snowflake). Activate your account by e-mail, and you should see a welcome screen. 
  
4. Click on your name in the bottom left corner, and select `Connect a tool to Snowflake`.

 <img width="294" alt="Screenshot 2025-04-15 at 9 08 27 PM" src="https://github.com/user-attachments/assets/d485f628-e397-4869-82d7-c5e1c1af24c0" />
  
  
Copy and paste the below into your `secrets.toml` file, replacing values in `[]` using the connect dialog information above: 

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
