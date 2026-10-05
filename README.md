
A modern IPO management frontend built with Next.js that supports bulk IPO applications, bulk eligibility checking, BOID management, and historical result tracking, designed for efficiency and scalability in investment workflows.

## Project Structure

```
frontend/
├── public/              # Static assets
├── src/
│   ├── app/
│   │   ├── page.tsx     # Home page
│   │   ├── layout.tsx   # Root layout
│   │   └── globals.css  # Global styles
│   ├── pages/
│   │   ├── bulk-check.tsx
│   │   ├── bulk-apply.tsx
│   │   ├── boids.tsx
│   │   └── history.tsx
│   ├── components/
│   │   ├── BOIDSelector.tsx
│   │   ├── ResultsSummary.tsx
│   │   ├── ResultsList.tsx
│   │   ├── Navigation.tsx
│   │   ├── LoadingState.tsx
│   │   └── ErrorMessage.tsx
│   ├── api/
│   │   └── client.ts    # API client
│   ├── types/
│   │   └── index.ts     # TypeScript types
│   └── styles/
│       └── globals.css
├── .env.example         # Environment variables template
├── next.config.js       # Next.js configuration
├── package.json         # Dependencies
└── tsconfig.json        # TypeScript configuration
```
