# 💰 Loan Calculator

แอปคำนวณสินเชื่อแบบ interactive พร้อมแสดงกราฟ, ตารางผ่อนชำระ และ export รายงาน

## Features

- กรอกข้อมูลสินเชื่อ: วงเงิน, ดอกเบี้ย, ระยะเวลา
- เลือกประเภทการชำระ (ต้น+ดอก, ดอกอย่างเดียว ฯลฯ)
- แสดงผลลัพธ์: ค่างวด, ดอกเบี้ยรวม, ตารางผ่อนรายเดือน
- แผนภูมิ: Pie, Bar, Line
- Export PDF/Excel
- บันทึกหลายรายการไว้เปรียบเทียบ
- Authentication
- Supabase Auth: Register, Login, Logout
- Middleware ป้องกัน route
- จำ session

## Tech Stack

- Nuxt 3 + TypeScript
- TailwindCSS + ShadCN-UI
- Pinia (State management)
- Supabase (Auth + Storage)
- Chart.js / Recharts
- UI shadcn-vue

## วิธี Setup

```bash
# 1. Clone repo
git clone https://github.com/Chidchai/Loan-Calculator
cd loan-calculator

# 2. Install dependencies
pnpm install

# 3. Run dev
pnpm dev
```

## Demo Credentials

Email: demo@loanapp.com  
Password: demo1234
