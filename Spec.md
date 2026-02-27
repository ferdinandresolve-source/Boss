boss-bot/
├── README.md                 # User guide
├── Spec.md                   # ← THIS FILE (copy everything)
├── package.json              # Dependencies
├── tsconfig.json            # TypeScript config
├── .env.example             # Environment vars
├── docker-compose.yml       # Local PostgreSQL
├── src/
│   ├── index.ts             # Bot entry point
│   ├── commands/
│   │   ├── ping.ts
│   │   ├── help.ts
│   │   ├── assist.ts
│   │   └── next.ts
│   ├── database/
│   │   └── db.ts           # PostgreSQL setup
│   ├── types/
│   │   └── index.ts        # TypeScript types
│   └── utils/
│       └── logger.ts       # Logging
└── dist/                    # Compiled JS (gitignored)
