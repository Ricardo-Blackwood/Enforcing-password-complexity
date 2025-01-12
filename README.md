# Enforcing-password-complexity

this Porject shows how to enforce password complexity using windows active directory 

First start up your server manager (if it isnt started automatically)

Navigate to the "tools" section in the upper right

![WS1](https://github.com/user-attachments/assets/a71a08a1-c217-4d64-aa98-42b5901062eb)

Navigate to the "group policy management" then left click on it to open 

![WS2](https://github.com/user-attachments/assets/a55f08ea-e15b-46b0-a36a-ce89b1627b45)

Open your forest and then open your companies domain, in the dashboard click "Linked Group Policy Object", right click then press "edit"

![WS3](https://github.com/user-attachments/assets/9c43b9b4-e089-4a41-a8ef-d4d94574eb37)

Navigate the following 

Computer configuration > Windows Settings > Security Settings > Account Policies then double click to open 

![WS4](https://github.com/user-attachments/assets/f8a6181a-e6dc-48d9-8dd7-991438afec39)

Then left click to open "Password Policy"

![WS5](https://github.com/user-attachments/assets/b0e2c033-9b56-47cf-9b97-484baad95082)

You can currently oberseve that there is no password complexity being enforced 

We will enforce the "Maximum password age", "Maximum password lenght" and "Password must meet complexity requirements"

![WS6](https://github.com/user-attachments/assets/ebcd4574-68f9-4020-a5bf-25cd8eb2f3d7)


Now you can see that we have successfully enforced password complexity requirements.

![WS done](https://github.com/user-attachments/assets/61299668-086c-408d-a381-5f5d251b1de4)















