# Lumina Edu

Lumina Edu is a robust educatinonal institute management system designed to streamline educational administration, enhance communication, and provide analytical insights. The system handles a wide range of school operations, from user management to class schedules, grade management, financial transactions, and real-time data visualization.

**<span style="color: red;">Important Note:</span>**  
<span style="color: red;">If you are unable to sign in due to a database or Prisma error, it may be because the free database hosting on Supabase has been temporarily paused due to inactivity. Please email me regarding the issue, and I will promptly restore the database availability.</span>

### Login Information

#### Admin:

- ID: `0-0001`
- Password: `123456`

#### Teacher:

- ID: `4-0001`
- Password: `123456`

#### Student:

- ID: `8-0002`
- Password: `123456`

#### Parent:

- ID: `9-0001`
- Password: `123456`



## Features

### 1. User Management
- Role-based system for Admins, Teachers, Students, Parents, and Accountants.
- Dynamic ID generation for roles (Admin, Teacher, Student, Parent and Accountant).
- Password protection with encryption.
- Role-specific dashboards with customized permissions.

### 2. Class and Grade Management
- Create and manage classes and grades with relations to students and teachers.
- A class can have a supervisor, courses, students, events, and announcements.
- Logic for preventing course scheduling conflicts within the same class.

### 3. Scheduling and Attendance
- Recurring schedules for courses within the classes.
- Time conflict handling for class schedules and exams.
- Attendance tracking per schedule for students.

### 4. Exams, Assignments, and Results
- Create and manage exams and assignments linked to specific courses.
- Automatic generation of exam results and grades for students.

### 5. Financial Transactions
- Manage student fees with Stripe integration.
- Role-based access for accountants to handle financial records.

### 6. Analytics and Reporting
- Interactive dashboards with real-time data visualization.
- Various graph types such as bar charts, line graphs, pie charts, and others, to visualize key aspects like Student performance, Attendance records, Financial insights.

### 7. Multistep Dynamic Forms
- Advanced, multistep forms with dynamic fields that adjust based on user input and role.
- React Hook Form for form state management and Zod for validation.

### 8. Server Rendering & Server Actions
- **Server-side rendering (SSR)** ensures fast page load times and improved SEO by pre-rendering content on the server.
- **Next.js server actions** are used to handle interactions with the database and perform operations directly from the server, streamlining data fetching and submission processes.

### 9. Suspense and Fallback
- **React Suspense** is used for efficient loading states when fetching data from the server, ensuring a smooth user experience.
- Custom **fallback components** provide a user-friendly interface during data loading periods, reducing perceived latency.

### 10. Communication
- Messaging system for communication between teachers, students, parents.
- Announcements and event management at class and school levels.

### 11. Security and Validation
- Zod-based validation across forms.
- NextAuth.js for authentication and authorization, ensuring secure user access.

### 12. Light/Dark Mode
- User-friendly interface with support for both light and dark modes.
- Theme toggle to enhance user experience and accessibility.

## Tech Stack
- **Frontend**: Next.js, React, React Hook Form, Zod, Zustand, Tailwind CSS, Shadcn/ui, Recharts.
- **Backend**: Node.js, Prisma, PostgreSQL, bcrypt.
- **Additional**: TypeScript, NextAuth.js, Stripe, Cloudinary

---

## Preview

![Admin Dashboard](https://res.cloudinary.com/dsupg9oa8/image/upload/v1729711635/untitled/LuminaEdu_bq9afo.png)
![Teacher Dashboard](https://res.cloudinary.com/dsupg9oa8/image/upload/v1729711632/untitled/LuminaEdu_1_fd3pgl.png)
![Student Dashboard](https://res.cloudinary.com/dsupg9oa8/image/upload/v1729711632/untitled/LuminaEdu_3_n9mffn.png)
![Parent Dashboard](https://res.cloudinary.com/dsupg9oa8/image/upload/v1729711632/untitled/LuminaEdu_4_d5bz2b.png)
