# TusharPaul_Assignment
My task : Forge an 💬NLP chatbot that doesn’t just answer, but masters science-related questions.
I have shown few sample response, which can be seen in the image below & in the main python file.

Users can engage with the chatbot by posing questions or inputting queries, and in return, they receive insightful and intelligent responses. The chatbot excels in providing astute answers, particularly in the realm of science-related inquiries, showcasing its proficiency and versatility.

Another similar project of mine, which masters drug related questions :
Link : https://knowledgeable-strident-cold.anvil.app/
It's live!!! You can check it. 
(Tech stack - ML, LLM, Fine-tuning, Phi-2, PEFT, Lora, AWS)

**Major steps :-**

Step 1: Set Up the Environment
Ensure Python 3.x is installed.
Verify GPU with CUDA support for optimal performance.
Install required dependencies using pip install torch transformers einops.

Step 2: Load the Model and Tokenizer
Import necessary libraries.
Load the Microsoft Phi2 language model and tokenizer.
The code initializes PyTorch to utilize the GPU by setting the default device. It then loads a pre-trained conversational language model, specifically Microsoft Phi-2, and its corresponding tokenizer. The generate_response function accepts input text, employs the model to generate a response, and optimizes performance by caching results for repeated queries. The generated text is split into individual lines. The function returns a specified number of lines, controlled by the max_lines parameter. This implementation leverages GPU acceleration to enhance the efficiency of natural language generation tasks, ensuring quick and responsive conversational interactions.

Step 3: Define the Response Generation Function
Create a function for generating responses with caching to enhance performance.

Step 4: Deployment on AWS SageMaker
Follow AWS SageMaker deployment guidelines to deploy the model.

Step 5: Create a Web App using Anvil
Develop an interactive web app using Anvil to connect with the SageMaker endpoint.

Step 6: Connect Anvil Web App
Implement the connection code between the Anvil app and the SageMaker endpoint.

Step 7: Ready for Interaction
Users can ask questions or input queries to receive thoughtful responses from the chatbot. It also answers science related questions smartly.

Step 8: Conversational AI Experience
Access the Anvil web app for a user-friendly interface, offering an immersive chatbot experience.

User interface (Chatbot)
![image](https://github.com/TusharPaul01/TusharPaul_Assignment/assets/97314846/75ade90e-fa64-43e5-bff8-0cb3aa09b1b2)

Amazon Web Services (AWS) has been used for cloud support, at the final stage of deployment.

![image](https://github.com/TusharPaul01/TusharPaul_Assignment/assets/97314846/202ac531-8d0b-406b-b12a-5fb57cf29016)
