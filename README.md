<h1 align="center">Devansh Deshpande</h1>

<p align="center">
  <a href="https://www.linkedin.com/in/devansh-deshpande-70982328b">LinkedIn</a> ·
  <a href="mailto:devansh436@gmail.com">Email</a> ·
  <a href="https://devansh436.vercel.app">Portfolio</a> ·
  <a href="https://drive.google.com/file/d/1H8r3q-3doOQ9hjOQJL80JmEKLwB-o3jV/view?usp=sharing">Resume</a>
</p>

<br>

I'm a CS undergrad at Nirma University (CGPA 8.69, Class of 2027), mostly building full-stack web apps and finding practical ways to plug ML into them. Top 9 finisher at Intellihack, a national cybersecurity hackathon.

## Tech Stack

`React` `Vite` `MUI` `Bootstrap` `Node.js` `Express` `TypeScript` `MySQL` `MongoDB` `Git` `Postman`

## Projects

**[Feather Scan](#)** — Bird species recognizer built as a 3-tier system: React frontend, Express/TypeScript API, and a FastAPI layer that unifies multiple classification models (Hugging Face, BioCLIP) behind one endpoint. Auth runs through Firebase with Zod schemas validating requests, MongoDB queries use indexing and pagination to keep lookups fast, and a caching layer cuts down on repeat inference calls. Core endpoints are covered by Jest/Supertest tests (60%+ coverage).

**[Library NLQ System](#)** — Lets users query a library database in plain English instead of SQL. Gemini handles the translation, with a validation layer to keep generated queries safe, and JWT-based role access to control what each user can see.

**[AI Legal Assistant](#)** — Voice-enabled legal consultation tool. Deepgram handles speech-to-text, Gemini generates context-aware responses, and MongoDB keeps conversation history across sessions.

**[Threat Detection & Analysis](#)** — Classifies network traffic using models trained on CICIDS 2017, with a 0–100 risk score and real-time visualization for flagged activity.
