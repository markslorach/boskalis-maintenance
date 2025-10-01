![boskalis-dashboard-banner](.github/readme-assets/boskalis-dashboard-banner.png)

# Boskalis Maintenance System

A custom-built maintenance management system for maritime equipment tracking and maintenance scheduling.

**Client:** Boskalis  
**Status:** In Production

## Features

- Maintenance status tracking with automated status calculations
- Create, update and delete maintenance records
- Mark items as under maintenance
- Archive system for inactive or decommissioned equipment
- Track equipment details, maintenance types and schedules
- Add notes to records
- Filter by status (Overdue, Due Soon, etc.)
- Multi-term search across all fields
- Sort by due date, name or status
- Persisted filter state using cookies (equipment type & status filters)
- CSV export for reporting
- User authentication (email/password)
- Responsive design for desktop and mobile

## Tech Stack

- Next.js 15 (React 19)
- TypeScript
- Tailwind
- shadcn/ui
- Prisma (PostgreSQL)
- Better Auth
- SWR
- React Hook Form
- Zod
- date-fns
- TanStack Table