# SkillSync

> SkillSync is an AI-Powered Peer Learning Network for SRM AP with integrated GraphRAG.
built by Team OnSight for Fortex36 hackathon, SRM AP.

 
## 🛠️ Tech Stack

| Layer | Technology |
|-------|------------|
| Frontend | Next.js 14, TypeScript, Tailwind, shadcn/ui |
| Backend | Node.js, Express.js, MongoDB |
| AI | Groq (Llama 3.3), NetworkX, LangChain.js |
| Auth | NextAuth.js, JWT |
| Deploy | Vercel, MongoDB Atlas, Railway |


## Project Structure 

```
skillsync/
├── directives/          # Layer 1: What to do (SOPs)
│   ├── skillsync.md     # Master directive
│   ├── auth.md          # Authentication flow
│   ├── matching.md      # Peer matching logic
│   ├── events.md        # Event discovery
│   └── ratings.md       # Rating system
│
├── execution/           # Layer 3: Doing the work (Scripts)
│   ├── auth/            # Auth scripts
│   ├── graphrag/        # Graph matching scripts
│   ├── events/          # Event scripts
│   └── ratings/         # Rating scripts
│
├── frontend/            # Next.js app
├── graphrag/            # Python microservice
├── .tmp/                # Intermediate files (gitignored)
├── docs/                # Documentation
└── .env                 # Environment variables
```


