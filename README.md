# Synchronization-embedded-chatbot-technique-using-IBM-Watson

In this task i'm using IBM Watson Assistant to create a chatbot to be integrated later in a website. To start you need to create an account in (https://www.ibm.com/sa-en/cloud/watson-assistant).

## 1. Create Assistant
After creating your account you'll see the following screen, click on (create assistant) button which will move you to the next window where you will be asked to provide a name for your chatbot, once you do so click on (create assistant) to start working on your chatbot.

![image](https://user-images.githubusercontent.com/85634099/125784243-fb355397-f72b-448e-bfca-dd3a9fc6e392.png)

![image](https://user-images.githubusercontent.com/85634099/125784748-82a0c348-a48c-4ca6-b6ed-595968c17f3e.png)

## 2. Add Dialog
For the chatbot to be able to interact coreectly we need to add some skills and dialogs so it can understand what to do and how to manage the conversation corrcetly, so write the name of the skill (ex: chatting), specify the lanugage choice and then select the skill type to be a (dialog), then click (Create skill):

![image](https://user-images.githubusercontent.com/85634099/125785057-c6bcb00e-dbb1-4354-9d56-59ca583c1209.png)

![image](https://user-images.githubusercontent.com/85634099/125785167-233d7e6d-ec81-43e1-ac07-6801f431ec7d.png)

## 3. Intents

Now that you have successfully created a dialog, you need to add intents to help the chatbot in understanding diffrent topics that the user may ask about, thus the chatbot can answer correctly , each intent carrys many sentances and words that can be categorized under that specific intent 
(ex: greeting will have Hi, Hello, Hey .. etc) so when the chatbot runs into one of these intents, it will be able to give a correct response.

![image](https://user-images.githubusercontent.com/85634099/125786682-d9b2e732-15f9-4cae-82d8-17157d4736c4.png)

![image](https://user-images.githubusercontent.com/85634099/125786593-eb07e62c-2bc5-405d-b971-ccc74ba54edf.png)

## 4. Entities
some previous intents may provide a value (ex: reservation intent where user provide name, date .. etc) and to handle these values we use entities where we can create them from scratch or use the built-in system entities as follows:

![image](https://user-images.githubusercontent.com/85634099/125787336-85b61b82-1a5f-413f-88ee-31b0eec026b6.png)

## 5. Dialog Nodes
To organize all what the chatbot has learned so far we need to add nodes where we gather each intent with the entities the it requires along with the corresponding responses for the chatbot to have a correct conversation:

![image](https://user-images.githubusercontent.com/85634099/125787699-772d395a-6631-4f9c-a991-e2cf9fb4672c.png)

## 6. Try the Chatbot
To assure that the chatbot is able to chat correctly we can click on (try it) which will open a window that allows you to chat with your chatbot and see how the conversation goes.

![image](https://user-images.githubusercontent.com/85634099/125788069-d78db646-174b-480e-82f3-bdde63cc9f8e.png)
