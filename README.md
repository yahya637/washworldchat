Opsætningsvejledning – AI Chatbot Prototype

Følg nedenstående trin for at køre chatbot-løsningen korrekt i udviklingsmiljøet. 

---
Hent din gratis API-nøgle

1. Gå til [Google AI Studio](https://aistudio.google.com/app/apikey).  
2. Opret en ny API-nøgle under **API-nøgle sektionen**. Det er gratis!

Din API-nøgle vil ligne noget i stil med:  
`AIzaSyBZG-U-qMbfm9yWbyB_yfNgk31Mynp6CWw`

---
Indsæt API-nøglen i projektet

1. Åbn projektmappen i **Visual Studio Code (VS Code)**.  
2. Find filen med navnet `.env`.  
3. Find linjen med `VITE_API_URL` og erstat `YOUR-API-KEY-HERE` med din rigtige API-nøgle.

---
Gem og test chatbotten

1. Gem `.env`-filen, når du har indsat din nøgle.  
2. Åbn terminalen i VS Code ved at trykke på `Ctrl + J`, og kør følgende kommandoer:
npm install     # Installerer nødvendige afhængigheder
npm run dev     # Starter den lokale udviklingsserver
