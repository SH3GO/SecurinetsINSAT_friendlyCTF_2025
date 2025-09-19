# Securinets_friendlyCTF_2025(Writeup)

Task1: The Silent Canvas 0
We find a scrap of paper with the username HistoryBuff77.
Looking it up on X (Twitter), we find the account and see the real name in the bio → Samuel Langley.  
<img width="938" height="878" alt="image" src="https://github.com/user-attachments/assets/67558ada-999f-46ac-92cb-3990fad56e89" />  
Flag: Securinets{Samuel_Langley}  

Task2: The Silent Canvas 1
Scrolling Langley’s posts, one shows a photo of a garden.
If we reverse image search it on Google, we see it’s the Palais du Luxembourg / Jardin du Luxembourg. 
<img width="975" height="971" alt="image" src="https://github.com/user-attachments/assets/eee86a56-febe-4a3f-b80f-e524f3c15e8c" />  
In the caption, he mentions a “nearby library.”
By Googling “library near Jardin du Luxembourg” or checking Google Maps, we find Bibliothèque Sainte-Geneviève.  
<img width="975" height="876" alt="image" src="https://github.com/user-attachments/assets/cf60d5b1-4cff-4e26-8c6b-8399112cbb90" />  
Flag: Securinets{Bibliotheque_Sainte-Genevieve}  

Task3: The Silent Canvas 2
At the library, his reserved book has a highlighted line about a wall-hanging acquired in 1882 that’s a masterpiece of Western art.
Searching that quote leads to The Lady and the Unicorn tapestry.
<img width="975" height="956" alt="image" src="https://github.com/user-attachments/assets/043f8251-7848-40fe-8687-4741191ed97d" />  
<img width="975" height="802" alt="image" src="https://github.com/user-attachments/assets/f32d04dc-0bda-4799-b1f9-290dfd278f94" />  
Flag: Securinets{The_Lady_And_The_Unicorn}  

Task4: The Silent Canvas 3
Langley wondered who made the tapestry. When we check, we find that the artist is unknown/anonymous.
Securinets{Anonymous}  

Task5: The Silent Canvas 4
Checking Langley’s X account reveals a suspicious tweet: “hope everybody saw it… couldn’t keep it for long.”
<img width="923" height="159" alt="image" src="https://github.com/user-attachments/assets/54f88311-1393-4f1a-af86-b6288ff6c2fb" />  
That hints at a deleted post. Looking it up in archive.today, we find the removed tweet:
“Everyone stares at the unicorn… but no one notices the little guardian at her feet.”  
<img width="975" height="637" alt="image" src="https://github.com/user-attachments/assets/3d5adcbd-8157-420c-8632-623acecb22d7" />
<img width="975" height="910" alt="image" src="https://github.com/user-attachments/assets/d01e12cc-b7f1-4e4b-9033-15a8511f9b74" />  
Flag: Securinets{The_Little_Guardian}  

Task6: The Silent Canvas 5
We get a password-protected 7z file with the description: “For those who see what no one else notices.”
That’s a hint the password is the previous flag → The_Little_Guardian.
After opening it, we find a letter explaining what happened: Langley’s partner, Marcel Durand, was behind everything and made sure the discoveries would never go public — so he got rid of him.
<img width="975" height="646" alt="image" src="https://github.com/user-attachments/assets/0049bc3c-51fe-4e2e-9006-29ef83a0fdec" />  
Flag: Securinets{Marcel_Durand}













