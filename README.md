  # CampusEcho---Anonymous-University-Complaint-System-backend-
campusecho-backend/
├── src/
│   ├── config/                  # Configuration
│   ├── middleware/              # Global middlewares
│   ├── modules/                 # Feature-based modules
│   │   ├── complaint/
│   │   │   ├── complaint.controller.ts
│   │   │   ├── complaint.routes.ts
│   │   │   ├── complaint.service.ts
│   │   │   └── complaint.validation.ts
│   │   └── admin/
│   │       ├── admin.controller.ts
│   │       ├── admin.routes.ts
│   │       ├── admin.service.ts
│   │       └── admin.validation.ts
│   ├── utils/                   # Helpers, logger, etc.
│   ├── types/                   # Custom types
│   ├── app.ts
│   └── server.ts
├── prisma/
│   └── schema.prisma
├── .env
├── tsconfig.json
└── package.json
