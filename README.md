Introducing Today's Project!

What is Amazon Lex?
Amazon Lex is an AWS service for building conversational chatbots using voiceand text. It uses advanced machine learning to understand user input and respond naturally.

How I used Amazon Lex in this project
I used Amazon Lex to build a conversational interface for the chatbot, enabling it to understand and respond to user inputs. I configured intents and addedvariations to ensure dynamic, conversational responses.
One thing I didn't expect in this project was...
One thing I didn’t expect was the complexity of fine-tuning the FallbackIntent.Initially, I thought the default FallbackIntent message would be sufficient, but I realized it needed more customization to make the chatbot's responses clearer.

This project took me...
This project took me about an hour to complete.

Setting up a Lex chatbot
I created my chatbot from scratch with Amazon Lex. Setting it up took me 8minutes
While creating my chatbot, I also created a role with basic permissions becausebasic Amazon Lex permissions allow the chatbot to interact with other AWSservices.
In terms of the intent classification confidence score, I kept the default value of0.40. This means that the chatbot needs to be at least 40% confident that it understands what the user is asking to be able to give a response.

<img width="950" alt="Amazon lex0" src="https://github.com/user-attachments/assets/b02ea7a6-5844-4f55-b57b-dcb454e66f5c" />


Intents
Intents are what the user is trying to achieve in their conversation with thechatbot. For example, booking a flight, checking a bank account balance, orordering food.
I created my first intent, WelcomeIntent, to greet users when they start aconversation with the chatbot.


<img width="844" alt="Amazon lex1" src="https://github.com/user-attachments/assets/adda6d51-4033-4a7d-b3c3-b32538d70f89" />


FallbackIntent
I launched and tested my chatbot, which could respond successfully if I enter'Hello'
My chatbot returned the error message 'Intent FallbackIntent is fulfilled' when Ientered 'Good morning' This error message occurred because the chatbot wasunable to match the input to a specific intent.

<img width="932" alt="Amazon Lex2" src="https://github.com/user-attachments/assets/2bc31e8b-fcd8-4b76-b6b5-fdb0747f5aff" />


Configuring FallbackIntent
FallbackIntent is a default intent in every chatbot that gets triggered when thechatbot is unable to recognize or match the user's input to any predefinedintents.
I wanted to configure FallbackIntent because it provides a clearer indication tothe user when the chatbot doesn't understand their request.

Variations
To configure FallbackIntent, I navigated to Closing Response and expanded theResponse sent to the user after the intent is fulfilled section. I replaced thedefault message with a clearer response.This ensures that the userunderstands the chatbot.
I also added variations! What this means for an end user is that it will give adynamic range of responses, making them sound more conversational.

<img width="944" alt="Amazon Lex3" src="https://github.com/user-attachments/assets/d9b82caa-5ff1-440b-9091-96a6eef721a0" />
