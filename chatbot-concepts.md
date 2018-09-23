# Chatbot Concepts

This section covers the basics of various chatbot concepts.


## Blocks

A **block** contains a conversation flow for a bot to respond. Each block is mapped to a user input, which could be a text phrase, pressing a button or another action triggered by a user.
Blocks are the basic building blocks of your bot. 

Each newly created bot comes with three default blocks:

* The **Start** block defines the start of the conversation. It is called automatically when a new conversation is triggered. This block cannot be deleted, but you can edit the message the bot will send to the user [from your account](https://console.recime.io/?utm_source=intercom&utm_medium=email&utm_campaign=welcome).

* if the chatbot doesn’t understand the user input, it will return the message within the **Default** block. This block cannot be deleted, but you can edit the message the bot will send to the user from your account. **Default** block can be used to trigger an external API when your bot does not understand a user input.

* The **About** block is called when the user types “about” when chatting to your bot. This block contains the default branding information of your chatbot. This generally contains the branding information and information about your bot and what it does.


## Expressions

Expressions are phrases or commands that a user would use to trigger a response from the chatbot (😎 à 🤖), related to the selected intent. To train your bot and to improve its ability to respond, it is best to add multiple expressions to each intent (ideally 4-8).
Below is an example of expressions:

* How's the weather in Paris?
* I want to travel from San Francisco to Madrid


## Entities
An entity represents a term or an object in the user's expression that provides clarification or specific context for a intent.

Here in the above statement, Location is an entity.

![](./entities.png)


## Responses

Responses are messages which the bot will send to the user(🤖 à 😎), in a given block. Responses could be:
* Direct replies to user expressions. An example of a bot response would be “It is 82°F in San Francisco right now.”
* Questions, which the bot would use to understand the full context of the conversation. An example would be “How would you like me to report the temperature? In Celsius or Fahrenheit?”

Bot responses can contain text, button(s), image(s), video(s), rich-content gallery or responses from custom plugin(s) or script(s).


***Related topics***

* [Working with Entities](./building-a-bot.md#working-with-entities)





