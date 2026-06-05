# hotelhub

    Hotel Property Management System สำหรับโรงแรมขนาดเล็ก-กลางที่บริหารเอง

[ สถานะปัจจุบัน: อยู่ในขั้นตอนการวางแผนพัฒนา. . . ]

## Overview

จากการสำรวจพบว่าโรงแรมขนาดเล็กไปจนถึงขนาดกลางที่เจ้าของเป็นคนบริหารเองในประเทศไทยยังมีระบบการบริหารจัดการภายในโรงแรมที่ยังคงมีช่องโหว่อยู่ เช่น

- การอัพเดตสถานะของสิ่งต่างๆ ภายในโรงแรม เช่น สถานะห้องพัก ประวัติการจองห้องพักและงานของแม่บ้าน เหล่านี้ยังคงใช้รูปแบบกระดาษหรือโทรศัพท์เพื่อดำเนินการอยู่

ช่องโหว่นี้อันตรายสำหรับธุรกิจ เช่น ทำให้เกิดการจองห้องพักซ้ำกันหรือเกิดการเสียโอกาสในการบริการลูกค้าเพราะ Work load ของพนักงานในบางตำแหน่งที่มีมากเกินไป

ซึ่ง HotelHub ออกแบบมาเพื่อปิดช่องโหว่นี้ด้วย

- แดชบอร์ดแสดงการจัดการภายในโรงแรมที่อัตเดตสถานะแบบ**เรียลไทม์**
- ระบบ**ป้องกันการเกิดข้อผิดพลาดทางธุรกิจ**อย่างครบถ้วน
- โอกาสในการทำกำไรที่มากขึ้นจากการทำ **Dynamic pricing**

เหมาะสำหรับโรงแรมขนาดเล็กไปจนถึงขนาดกลางที่ต้องการเปลี่ยนมาใช้ระบบ PMS ในการจัดการแบบครบวงจรในราคาที่ถูกลงและยังสามารถรองรับการบริการที่มีขนาดใหญ่ขึ้นในอนาคตได้อีกด้วย

## Key Features

### Killer Features: 

- Real-time Operations Dashboard

- Dynamic Pricing Engine

- Audit Log & Activity Timeline

### Core Features:

- Authentication & Authorization (RBAC)

- Room Catalog & Search

- Online Booking (Customer flow)

- Walk-in/Phone Booking (Frontdesk flow)

- Payment Processing

- Check-in and Check-out

- Room Status Management

- Housekeeping Task Management

- Booking Cancellation

- Review System

- Email Notifications

- Analytics Dashboard

- Admin settings

- Audit Log View

## Tech Stack

- **Frontend:** Next.js, TypeScript, Tailwind CSS, shadcn/ui, Zod, React Hook Form, TanStack Query (React Query)

- **Backend:** NestJS, TypeScript

- **Database:** PostgreSQL, PrismaORM

- **Real-time:** Socket.IO

- **Deployment:** Vercel, Railway

## Documentation

- [Project Brief](./docs/01-project-brief.md)

## Getting Started

    กำลังพัฒนา. . .

## License

    MIT