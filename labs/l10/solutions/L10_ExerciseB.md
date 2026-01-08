<img width="2856" height="1787" alt="image" src="https://github.com/user-attachments/assets/4e8e64b3-af8c-4aaf-b4cc-9d3f81379e43" />

Creating new clean workflow without my github name but in next screenshot you will see that I updated it and everything is fine

<img width="2865" height="1794" alt="image" src="https://github.com/user-attachments/assets/54010ae6-9526-4109-bdd8-076dbd988418" />

I added an HTTP Request node that takes the URL from my Webhook and sends it to Jina.ai to get a clean and readable version of the page.

<img width="2873" height="1793" alt="image" src="https://github.com/user-attachments/assets/a36c7c30-6781-4cc7-a7d0-82b33b002dc8" />

Then I set up another HTTP node to push that text into Groq's API, using a specific prompt to make sure the AI returns the data exactly in the JSON format I need.

<img width="2879" height="1799" alt="image" src="https://github.com/user-attachments/assets/ddb2901d-583c-4247-8cb0-350bb103b83e" />

Rest of that HTTP Request node

<img width="2879" height="1798" alt="image" src="https://github.com/user-attachments/assets/5c14fcb0-8f60-4be5-8ce3-dcdba9ba2ecb" />

Here proof of working and sample answer
