# storyChatBot
Implements a chatbot which suggests a possible continuation to the user's story based on the user's input. The chatbot looks for pre-defined keywords in the user's input and updates some state variables based on the keywords that it finds. The chatbot then identifies the best possible contuation to the story based on the values of these variables as well as some pre-defined rules. Below is a screenshot of the interactive story-writer system which incorporated the chatbot to help users with their stories.

![interactive-storyWriter](interactive-storyWriter.png)

## Sample interaction with the chatbot

*Chatbot*: It's the perfect weather to be playing outside, Bart thought as he gazed at the clear blue sky.  
*Me*: So, Bart decided to go out into the yard.  
*Chatbot*: Bart saw the basketball lying in the yard.  
*Me*: He went up to the basketball and picked it up.  
*Chatbot*: Bart picked up the basketball and started dribbling.  
*Me*: He dribbled upto the hoop and lined up to take a shot.  
*Chatbot*: Let me just practice till the others get here, Bart thought.  
*Me*: So, he continued to practice.  
*Chatbot*: Bart thought that this'd be a great time for some lemonade!  
*Me*: He got some lemonade from the fridge and started to drink it.  
*Chatbot*: Bart drank the lemonade and felt a sudden surge of energy.  
*Me*: Then, he just lied down on the grass.  
*Chatbot*: Bart thought that this'd be a great time for some ice-cream!  
*Me*: So, he got some ice-cream and ate it!  
*Chatbot*: Pikachu took his skateboard and headed to his house.  
*Me*: Cool, Pikachu will be here soon, Bart thought in his head.  
*Chatbot*: Spongebob took his car and headed to Bart's house.  
*Me*: Soon, Spongebob, Pikachu and Bart were in the yard.  
*Chatbot*: Spongebob saw the basketball lying in the yard.  
*Me*: So, he picked it up.  
*Chatbot*: Bart picked up the basketball and passed it.  
*Me*: Spongebob  recieved the pass and dribbled forward.  
*Chatbot*: Spongebob passed the ball to Spongebob.  
*Me*: That is a really neat self-pass, Bart muttered to himself.  
*Chatbot*: But the pass gets blocked by Pikachu.  
*Me*: Pikachu is lightning quick and takes a shot!  
*Chatbot*: Did you see that shot?, Spongebob exclaimed!  

The chatbot tries to understand the context of the story by looking for certain pre-defined keywords in the user's input, and seems to do an alright job in the example above. 

