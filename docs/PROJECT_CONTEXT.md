# HotelHub — Project Context (for AI handoff)

## What is this
Hotel Property Management System (PMS) สำหรับโรงแรมเล็ก-กลางที่บริหารเอง
Portfolio project ของคนเปลี่ยนสายมาเป็น fullstack dev
เป้าหมาย: production-grade, สมัครงาน ส.ค. 2026

## How we work together (IMPORTANT)
- AI = senior reviewing junior. เขียน code + อธิบาย "ทำไม"
- User พิมพ์ code เองทุกบรรทัด (ไม่ copy-paste) เพื่อเรียนรู้
- ก่อนผ่านแต่ละ phase: AI ทำ exit interview, ตอบไม่ผ่าน = ไม่ข้าม phase
- User honest เสมอ ("จะทำ" ≠ "ทำแล้ว")

## User profile
- JS 7/10, TS ใหม่, DB design 5/10 (weak), Security 2-3/10 (weak)
- Full-time, ~6-8 ชม./วัน, target 3 เดือน
- Windows + WSL, VS Code, มี GitHub

## Tech Stack (locked)
- FE: Next.js + TS + Tailwind + shadcn/ui + Zod + React Hook Form + TanStack Query
- BE: NestJS + TS
- DB: PostgreSQL + Prisma
- Auth: bcrypt (hash) + JWT (access+refresh, httpOnly cookie) + RBAC
- Real-time: Socket.IO
- Email: Resend
- Deploy: Vercel (FE) + Railway (BE)
- CI/CD: GitHub Actions
- Monitoring: Sentry

## User Roles (6)
Guest, Customer, Front Desk, Housekeeping, Manager, Admin

## Features
MVP: Auth/RBAC, Room Catalog, Online Booking, Walk-in Booking, Payment,
Check-in/out, Room Status, Housekeeping Tasks, Cancellation, Review,
Email Notification, Analytics Dashboard, Admin Settings, Audit Log Viewer
Killer: Real-time Dashboard (WebSocket), Dynamic Pricing Engine, Audit Log

## Key concepts learned (Phase 0)
SSOT, atomic transaction, HTTP vs WebSocket, race condition + DB locking,
reservation pattern + expires_at, price freeze, JWT/bcrypt separation,
access+refresh token, separation of duties, defense in depth

## Progress
- [x] Phase 0: Project Brief — DONE
- [ ] Phase 1: Design — IN PROGRESS (User Stories, RBAC Matrix, Architecture, DB Design, API, UI)
- [ ] Phase 2-9: see docs/00-roadmap.md for full details

## Roadmap
Full 9-phase roadmap: docs/00-roadmap.md

## Next step
Phase 1 — เริ่มที่ Database Design (user's weak point, ต้องสอนละเอียด)