# Login
Generic PHP Code for a login module

Prompt for username individually
     If username exists, prompt for password
       If hashed password is correct, send 6-digit code to assigned phone number
     If username doesn't exist, display message and ask if they want to create a new account
       Remember username
       Prompt twice for password
       Prompt for cell phone number for multifactor authentication
       Include a pull down for what they will use the account for
Display a link for forgotten password
