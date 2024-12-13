1. Multi agent system
   - achieved functioning three agent system - supervisor, researcher and communication
   - researcher and communication agents successfully communicated and provided feedback to each other
   - supervisor failed to terminate discussion within recursive limit of 25 and system crashed
   - in multi agent file - also contains prompt (which can be used to create different tool/agent) - where accesses data on clients and chooses best three clients to recommend a certain item to and gives a varying discount depending on how long theyve been with the company for - useful for overstocks

2. Sending emails
   - achieved functioning sending email function using mailjet which allowed me to send emails to anyone about anything without exiting my code
   - sending email tool did not work when incorporated into agent, attempted debugging but ran out of time

3. Memory
   - succeeded in achieving memory in our llm model using chains
   - failed to incorporate this chain/memory into our agent

4. User interface
   - suceeded in setting up gradio interface which allowed single input
   - system crashed when agent attempted to give back output to interface
   - error of filename being too long - did not have enough time to debug

5. Guard rails
   - attempted to introduce guardrails to prevent users from abusing chatbot and from agent revealing private company data
