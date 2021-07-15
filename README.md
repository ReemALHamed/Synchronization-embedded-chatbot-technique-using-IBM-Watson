# Synchronization-embedded-chatbot-technique-using-IBM-Watson

In this task, I'm using IBM Watson Assistant to create a chatbot to be integrated later into a website. To start you need to create an account in (https://www.ibm.com/sa-en/cloud/watson-assistant).

## 1. Create Assistant
After creating your account you'll see the following screen, click on the (create assistant) button which will move you to the next window where you will be asked to provide a name for your chatbot, once you do so click on (create assistant) to start working on your chatbot.

![image](https://user-images.githubusercontent.com/85634099/125784243-fb355397-f72b-448e-bfca-dd3a9fc6e392.png)

![image](https://user-images.githubusercontent.com/85634099/125784748-82a0c348-a48c-4ca6-b6ed-595968c17f3e.png)

## 2. Add Dialog
For the chatbot to be able to interact correctly we need to add some skills and dialogs so it can understand what to do and how to manage the conversation correctly, so write the name of the skill (ex: chatting), specify the language choice, and then select the skill type to be a (dialog), then click (Create skill):

![image](https://user-images.githubusercontent.com/85634099/125785057-c6bcb00e-dbb1-4354-9d56-59ca583c1209.png)

![image](https://user-images.githubusercontent.com/85634099/125785167-233d7e6d-ec81-43e1-ac07-6801f431ec7d.png)

## 3. Intents

Now that you have successfully created a dialog, you need to add intents to help the chatbot in understanding different topics that the user may ask about, thus the chatbot can answer correctly, each intent carries many sentences and words that can be categorized under that specific intent 
(ex: greeting will have Hi, Hello, Hey .. etc) so when the chatbot runs into one of these intents, it will be able to give a correct response.

![image](https://user-images.githubusercontent.com/85634099/125786682-d9b2e732-15f9-4cae-82d8-17157d4736c4.png)

![image](https://user-images.githubusercontent.com/85634099/125786593-eb07e62c-2bc5-405d-b971-ccc74ba54edf.png)

## 4. Entities
some previous intents may provide a value (ex: reservation intent where user provide name, date .. etc), and to handle these values we use entities where we can create them from scratch or use the built-in system entities as follows:

![image](https://user-images.githubusercontent.com/85634099/125787336-85b61b82-1a5f-413f-88ee-31b0eec026b6.png)

## 5. Dialog Nodes
To organize all what the chatbot has learned so far we need to add nodes where we gather each intent with the entities it requires along with the corresponding responses for the chatbot to have a correct conversation:

![image](https://user-images.githubusercontent.com/85634099/125787699-772d395a-6631-4f9c-a991-e2cf9fb4672c.png)

## 6. Try the Chatbot
To assure that the chatbot can chat correctly we can click on (try it) which will open a window that allows you to chat with your chatbot and see how the conversation goes.

![image](https://user-images.githubusercontent.com/85634099/125788069-d78db646-174b-480e-82f3-bdde63cc9f8e.png)

## 7. Download The JSON File
Now that you made sure your chatbot is working fine you can export it as a JSON file and to do so click on the 3 dots next to your chatbot skill's name and choose Download and it will start downloading automatically 

![image](https://user-images.githubusercontent.com/85634099/125788483-58c26087-b959-45ff-b0da-e527e545bbbf.png)

## 8. Integrate The Chatbot With a Website
To add your chatbot to your website click on (Integrate webchat) and enter the name of the integration, the following window will appear for you to customize your chatbot (color, tabs, name ..etc) and once you are done customizing your chatbot click on (Embed) tab where you'll find the script that you can copy and paste in your website for your chatbot to appear on:

![image](https://user-images.githubusercontent.com/85634099/125788870-5807fb9c-3d3d-4259-854e-0858dc7bb551.png)

![image](https://user-images.githubusercontent.com/85634099/125789088-c0a26f3e-9e08-4e25-b4ff-1efbdd9bb047.png)

![image](https://user-images.githubusercontent.com/85634099/125789267-3e42869f-1abc-4a11-8b2c-441b1c3b1144.png)

![image](https://user-images.githubusercontent.com/85634099/125793847-889e7d6e-49c6-4de2-b96c-c420e4a29465.png)


## 9. Final Results !!
I used one-page Bootstrap and added my chatbot to it to test if it works and it did! YAY !!
I chose a restaurant Bootstrap and built my chatbot according to the needs of my website so the chatbot can :

* Greet and thanks
* Provide the restaurant location
* Provide the restaurant contact info
* Provide the restaurant working hours
* Reserve a table for the customer
* Reserve an overview of the menu

https://user-images.githubusercontent.com/85634099/125790469-fb3f97db-ac74-4d30-8b7d-27647dfd4e2b.mp4

https://user-images.githubusercontent.com/85634099/125791456-4a561fb2-44c7-4182-bc47-ab7bc305cd7b.mp4


## About The Bootstrap:
I downloaded the bootstrap from (https://uicookies.com/downloads/resto-free-restaurant-responsive-bootstrap-website-template/) and used NetBeans to run it, I edited it a bit and I added my chatbot to it and this is how it went :)

## Bootstrap Overview:
https://user-images.githubusercontent.com/85634099/125792830-13d137c9-8dc8-4938-a67e-94f5e7bc6d8b.mp4

## Integrated Chatbot Overview
https://user-images.githubusercontent.com/85634099/125792813-d6430831-8c06-481a-858a-020b67e44cb3.mp4

