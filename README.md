# Exno.3-Scenario-Based Report Development Utilizing Diverse Prompting Techniques
### DATE: 09-09-2025                                                                        
### REGISTER NUMBER : 212223230249 
### Aim: To design an AI-powered chatbot that assists customers in resolving issues related to product troubleshooting, order tracking, and general inquiries. The chatbot should handle various customer queries efficiently while maintaining a conversational and user-friendly tone. In this experiment, we will employ different prompt patterns to guide the development process of the chatbot, ranging from basic task-oriented prompts to more complex, persona-driven prompts.

## Algorithm:
### 1. Direct Instruction Prompts
**Objective:** Guide the chatbot to respond concisely to customer inquiries.

**Prompt Pattern:**
Prompt: "When a customer asks for the status of their order, reply with: 'Your order is currently being processed and will be delivered by [date].'"
### 2. Contextual Prompting
**Objective:** Incorporate specific context to provide detailed answers based on the user’s previous interaction.

**Prompt Pattern:**
Prompt: "If the customer previously mentioned that they haven’t received their order, say, 'I see that you mentioned your order hasn't arrived yet. Let me check the details for you and get back shortly.'"
### 3. Persona-Based Prompting
**Objective:** Design the chatbot to adopt a specific persona, making the interaction more engaging.

**Prompt Pattern:**
Prompt: "Pretend you are a friendly, helpful customer service representative. Use a conversational tone, such as 'Hey there! I’m here to help with any questions you might have. Let’s get your issue sorted!'"
### 4. Few-Shot Prompting
**Objective:** Teach the AI how to respond using a few examples, enabling it to generalize for similar situations.

**Prompt Pattern:**
Prompt: "Here are some examples of how to handle technical questions:
'My phone isn't charging.' → 'Have you tried using a different cable? If that doesn’t work, it may be an issue with the port.'
'The screen is flickering.' → 'It sounds like a display issue. Have you tried restarting the device?'
Now, respond to: 'My app keeps crashing.'"
### 5. Chain of Thought Prompting
**Objective:** Use a step-by-step reasoning approach for resolving more complex or technical issues.

**Prompt Pattern:**
Prompt: "When a customer reports their laptop overheating, guide them through the following steps:
Ask if they are using the laptop on a soft surface.
Suggest moving the laptop to a flat, hard surface for better airflow.
Ask if they’ve cleaned the vents recently.
Recommend restarting the device to see if the issue persists.
Now, solve: 'My laptop fan is making a loud noise.'"
### 6. Instruction with Constraints
**Objective:** Instruct the chatbot to provide assistance while adhering to specific constraints (e.g., response length or tone).

**Prompt Pattern:**
Prompt: "Respond to order inquiries in no more than 50 words and avoid using technical jargon. For example, 'Your order is on the way and should arrive by [date]. Feel free to reach out if you need anything else.'"
### 7. Reflective Prompting
**Objective:** Ensure that the chatbot reflects the user’s query back to them before providing a response, reducing misunderstandings.

**Prompt Pattern:**
Prompt: "When a customer asks for help, first reflect their question back to them. For example, if they ask 'How can I reset my password?' respond with 'You're asking how to reset your password, correct? Here’s how you can do it.'"


## Output
### 1. Direct Instruction Prompts
**Customer Query 1:**  
"Where is my order?"  
**Chatbot Response:**  
Your order is currently being processed and will be delivered by September 5, 2025.  

---

**Customer Query 2:**  
"Can you tell me the status of my order?"  
**Chatbot Response:**  
Your order is currently being processed and will be delivered by September 7, 2025.  

---

**Customer Query 3:**  
"Has my package shipped yet?"  
**Chatbot Response:**  
Your order is currently being processed and will be delivered by September 10, 2025.  

---

**Customer Query 4:**  
"When will my product reach me?"  
**Chatbot Response:**  
Your order is currently being processed and will be delivered by September 12, 2025.  

---

**Customer Query 5:**  
"Can you check the delivery date for my order?"  
**Chatbot Response:**  
Your order is currently being processed and will be delivered by September 15, 2025.  

---

### 2. Contextual Prompting
**Customer Query 1:**  
"I haven’t received my order yet. Can you help?"  
**Chatbot Response:**  
I see that you mentioned your order hasn't arrived yet. Let me check the details for you and get back shortly.  

---

**Customer Query 2:**  
"My package hasn’t come even though it was supposed to be delivered yesterday."  
**Chatbot Response:**  
I see that you mentioned your order hasn't arrived yet. Let me check the details for you and get back shortly.  

---

**Customer Query 3:**  
"It’s been a week and I still don’t have my order."  
**Chatbot Response:**  
I see that you mentioned your order hasn't arrived yet. Let me check the details for you and get back shortly.  

---

**Customer Query 4:**  
"The delivery status says ‘delivered’ but I never got the package."  
**Chatbot Response:**  
I see that you mentioned your order hasn't arrived yet. Let me check the details for you and get back shortly.  

---

**Customer Query 5:**  
"I ordered last week and still haven’t received my items."  
**Chatbot Response:**  
I see that you mentioned your order hasn't arrived yet. Let me check the details for you and get back shortly.  

---

### 3. Persona-Based Prompting
**Customer Query 1:**  
"My phone isn’t charging."  
**Chatbot Response:**  
Hey there! I’m here to help with any questions you might have. Let’s get your issue sorted! Have you tried using a different charging cable or checking the power outlet? Sometimes the issue is with the accessories.  

---

**Customer Query 2:**  
"The screen on my laptop keeps flickering."  
**Chatbot Response:**  
Hi! Thanks for reaching out. Let’s get this sorted together. Flickering screens are often caused by display settings or drivers. Have you tried restarting the laptop or updating your graphics drivers?  

---

**Customer Query 3:**  
"My order hasn’t been delivered yet."  
**Chatbot Response:**  
Hey! I totally understand how frustrating that can be. Don’t worry—we’ll figure this out. Let me quickly check your order details so we can get your delivery status.  

---

**Customer Query 4:**  
"The app keeps crashing whenever I open it."  
**Chatbot Response:**  
Oh no! That’s annoying, I get it. Let’s fix this together. Can you try clearing the app cache or reinstalling it? Those steps usually help stop the crashing.  

---

**Customer Query 5:**  
"How do I reset my password?"  
**Chatbot Response:**  
Hey there! No worries, I can guide you through it. Just go to the login page, click on **‘Forgot Password’**, and follow the instructions in the email you’ll receive. Easy fix! 

---

### 4. Few-Shot Prompting
**Customer Query 1:**  
"My app keeps crashing."  
**Chatbot Response:**  
It sounds like the app might have a stability issue. Have you tried clearing the app’s cache or reinstalling it? That usually fixes crashing problems.  

---

**Customer Query 2:**  
"The Bluetooth on my phone won’t connect."  
**Chatbot Response:**  
Have you tried turning Bluetooth off and back on again? If that doesn’t work, unpair and re-pair the device to see if the connection stabilizes.  

---

**Customer Query 3:**  
"My laptop isn’t turning on."  
**Chatbot Response:**  
Have you checked if the laptop is charging? Try plugging it into a different power outlet or using another adapter. It could also be a battery issue.  

---

**Customer Query 4:**  
"The sound isn’t coming from my headphones."  
**Chatbot Response:**  
It may be an audio settings issue. Have you tried checking if the headphones are set as the default output device and testing them with another gadget?  

---

**Customer Query 5:**  
"The Wi-Fi keeps disconnecting on my tablet."  
**Chatbot Response:**  
It could be a network issue. Have you tried restarting your router or reconnecting to the Wi-Fi network on your tablet?  

---

### 5. Chain of Thought Prompting

**Customer Query 1:**  
"My laptop fan is making a loud noise."  
**Chatbot Response:**  
I understand. Let’s go through this step by step:  
1. First, are you using your laptop on a bed, sofa, or other soft surface? That can block airflow.  
2. If yes, try placing it on a flat, hard surface to improve cooling.  
3. Next, have you cleaned the vents recently? Dust buildup often causes fans to work harder.  
4. Finally, try restarting the laptop after cleaning—sometimes that helps stabilize the fan speed.  

---

**Customer Query 2:**  
"My laptop gets really hot when I use it for gaming."  
**Chatbot Response:**  
Let’s troubleshoot step by step:  
1. Are you placing the laptop on a soft surface while gaming? That could trap heat.  
2. Try keeping it on a desk or table for better airflow.  
3. Check and clean the cooling vents if possible—dust can trap heat inside.  
4. Restart your device and monitor the temperature after gaming.  

---

**Customer Query 3:**  
"The fan suddenly became noisy after an update."  
**Chatbot Response:**  
Alright, let’s take this one step at a time:  
1. Is the laptop on a soft surface right now?  
2. If so, move it to a flat surface like a desk to allow airflow.  
3. Have you cleaned the vents recently? Dust could have built up.  
4. Try restarting after the update—it might reset the fan’s operation.  

---

**Customer Query 4:**  
"My laptop overheats even during normal use."  
**Chatbot Response:**  
Here’s a step-by-step check:  
1. Do you usually place it on your lap or a bed? That reduces airflow.  
2. Move it to a solid surface to keep it cool.  
3. Clean the vents and fans if you haven’t done so in a while.  
4. Restart the system to see if the issue persists.  

---

**Customer Query 5:**  
"The fan keeps running loudly, even when I’m just browsing."  
**Chatbot Response:**  
Let’s work through this:  
1. Is the laptop resting on a soft surface? That could be trapping air.  
2. Shift it onto a hard surface for better cooling.  
3. Check and clean dust from the vents.  
4. Restart the laptop after cleaning to reset the fan performance.

---

### 6. Instruction with Constraints

**Customer Query 1:**  
"Where is my order?"  
**Chatbot Response:**  
Your order is on the way and should arrive by September 6, 2025. Please let us know if you need further help.  

---

**Customer Query 2:**  
"Can you update me on my package delivery?"  
**Chatbot Response:**  
Sure! Your package is currently in transit and will arrive by September 9, 2025.  

---

**Customer Query 3:**  
"My order still hasn’t come. What’s going on?"  
**Chatbot Response:**  
I understand your concern. Your order is out for delivery and should reach you by September 11, 2025.  

---

**Customer Query 4:**  
"When will my product reach me?"  
**Chatbot Response:**  
Your product is on its way and expected to be delivered by September 13, 2025.  

---

**Customer Query 5:**  
"Can you check the delivery date for my order?"  
**Chatbot Response:**  
Yes! Your order is on schedule and will be delivered by September 15, 2025. 

---

### 7. Reflective Prompting

**Customer Query 1:**  
"How can I reset my password?"  
**Chatbot Response:**  
You're asking how to reset your password, correct? Here’s how you can do it: go to the login page, click **Forgot Password**, and follow the instructions sent to your email.  

---

**Customer Query 2:**  
"My order hasn’t arrived yet. What should I do?"  
**Chatbot Response:**  
You’re saying your order hasn’t arrived yet, correct? Let me check the details for you and update you shortly.  

---

**Customer Query 3:**  
"How do I track my shipment?"  
**Chatbot Response:**  
You’d like to know how to track your shipment, right? You can check the tracking link sent to your email or use your order ID on our website’s tracking page.  

---

**Customer Query 4:**  
"Why is my app crashing all the time?"  
**Chatbot Response:**  
You’re asking why your app keeps crashing, correct? Try clearing the app’s cache or reinstalling it—this usually fixes stability issues.  

---

**Customer Query 5:**  
"Can you tell me how to change my delivery address?"  
**Chatbot Response:**  
You want to know how to change your delivery address, correct? You can update it in the “My Orders” section under your profile before the order is shipped.  

## Result:
Thus the Prompts were exected succcessfully .


