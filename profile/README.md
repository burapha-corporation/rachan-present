# Rachan | ธนาราชัน

## Financial Operating System

Rachan คือ Financial Operating System สำหรับบุคคลและธุรกิจ ที่ช่วยให้ผู้ใช้จัดการเงิน ปกป้องความมั่งคั่ง เพิ่มพูนสินทรัพย์ และวางแผนอนาคตทางการเงินได้อย่างเป็นระบบ

เราไม่ได้สร้างเพียงแอปบัญชีหรือแพลตฟอร์มลงทุน แต่สร้างระบบที่เชื่อมโยงข้อมูลทางการเงินทั้งหมดเข้าด้วยกัน ตั้งแต่รายรับ รายจ่าย หนี้สิน สินทรัพย์ ประกัน ไปจนถึงการลงทุน เพื่อให้ผู้ใช้เข้าใจสถานะทางการเงินของตนเองและตัดสินใจได้ดีขึ้น

> **จัดการเงิน → ปกป้องเงิน → เพิ่มเงิน → ส่งต่อความมั่งคั่ง**

## Our Architecture

Rachan พัฒนาบนแนวคิดที่ให้ Accounting เป็นฐานข้อมูล และใช้ Financial Intelligence เป็นชั้นกลางในการเชื่อมต่อบริการทางการเงินต่าง ๆ

```text
Rachan Financial Identity
	     │
     ┌──────┴──────┐
 Rachan.app    Rachan.com
 Accounting    Financial Platform
     │              │
     └──────┬───────┘
	     │
   Financial Intelligence
	     │
  Finance · Insurance · Investment · Credit
	     │
	Rachan AI & Marketplace
```

### Rachan.app — Accounting Foundation

ระบบจัดเก็บและทำความเข้าใจเงินที่เกิดขึ้นแล้ว โดยครอบคลุม:

- รายรับและรายจ่าย
- สินทรัพย์ หนี้สิน และมูลค่าสุทธิ
- กระแสเงินสดและธุรกรรม
- Profit & Loss และ Balance Sheet
- รายงานทางการเงินและข้อมูลภาษี

### Rachan.com — Financial Platform

แพลตฟอร์มสำหรับบริหาร ปกป้อง และต่อยอดความมั่งคั่ง:

- **Finance:** Budgeting, Saving, Debt Management, Credit และ Tax Planning
- **Insurance:** วิเคราะห์ความเสี่ยง ตรวจสอบ Coverage Gap และจัดการกรมธรรม์
- **Investment:** สินทรัพย์ทางการเงิน Digital Asset, Real Asset และ Alternative Investment
- **Credit:** สินเชื่อ Refinance และ Asset-backed Lending
- **Marketplace:** เชื่อมต่อผู้ใช้กับผลิตภัณฑ์และโอกาสทางการเงินที่เหมาะสม

## Rachan AI

Rachan AI คือ Financial Intelligence Layer ที่วิเคราะห์ข้อมูลการเงินแบบองค์รวม ไม่ได้ทำหน้าที่เป็นเพียง chatbot แต่ช่วยจัดลำดับการตัดสินใจที่เหมาะสมกับผู้ใช้แต่ละคน

ระบบสามารถประเมิน:

- Financial Health Score
- สภาพคล่องและ Emergency Fund
- หนี้ดอกเบี้ยสูงและ Debt Health
- ช่องว่างด้านประกันและความเสี่ยง
- โครงสร้างสินทรัพย์และการลงทุน
- เป้าหมายทางการเงินและ Next Best Action

ตัวอย่างคำแนะนำที่ Rachan สามารถให้ได้คือ การสร้าง Emergency Fund หรือชำระหนี้ดอกเบี้ยสูงก่อนเพิ่มสัดส่วนการลงทุน เพื่อให้ทุกการตัดสินใจสอดคล้องกับสถานะจริง ไม่ใช่คำแนะนำแบบเดียวสำหรับทุกคน

## Our Principles

1. **Data first** — สร้าง Financial Identity จากข้อมูลที่ถูกต้องและเชื่อมโยงกัน
2. **Intelligence before marketplace** — เข้าใจความต้องการก่อนเสนอผลิตภัณฑ์
3. **Actionable advice** — เปลี่ยนข้อมูลให้เป็นคำแนะนำที่นำไปปฏิบัติได้
4. **Responsible growth** — ให้ความสำคัญกับสภาพคล่อง ความเสี่ยง และความยั่งยืนระยะยาว

## Product Direction

เราจะเริ่มจากการสร้างรากฐานข้อมูลทางการเงินที่แข็งแรงใน Rachan.app จากนั้นจึงต่อยอดไปสู่ Finance, Insurance, Investment และ Credit บน Rachan.com โดยมี Rachan AI ทำหน้าที่วิเคราะห์และเชื่อมโยงทุก module เข้าด้วยกัน

เป้าหมายของเราคือการสร้างระบบที่ช่วยให้ผู้ใช้:

> **เข้าใจเงินของตัวเอง วางแผนได้ดีขึ้น ป้องกันความเสี่ยง และสร้างความมั่งคั่งได้อย่างมีเหตุผล**

---

## English

### Rachan | Financial Operating System

Rachan is a Financial Operating System for individuals and businesses. It helps people manage money, protect wealth, grow assets, and plan for their financial future in one connected system.

Rachan is more than an accounting app or investment platform. It connects income, expenses, liabilities, assets, insurance, and investments to help users understand their financial position and make better decisions.

> **Manage money → Protect wealth → Grow wealth → Pass on wealth**

### Product Architecture

- **Rachan.app:** The accounting foundation for income, expenses, assets, liabilities, cash flow, financial reports, and net worth.
- **Rachan.com:** The financial platform for Finance, Insurance, Investment, Credit, and Marketplace services.
- **Rachan AI:** The intelligence layer that provides Financial Health Scores, risk analysis, personalized recommendations, and Next Best Actions.

Rachan follows a data-first approach: build a reliable Financial Identity first, then connect users with relevant financial services and opportunities.

### Product Direction

We start with a strong financial data foundation in Rachan.app and expand into Finance, Insurance, Investment, and Credit through Rachan.com. Our goal is to help users understand their money, make better plans, manage risk, and build sustainable wealth.

---

## 中文

### Rachan | 个人与企业的金融操作系统

Rachan 是面向个人和企业的金融操作系统，帮助用户管理资金、保护财富、增加资产，并系统化地规划未来的财务生活。

Rachan 不只是记账应用或投资平台，而是将收入、支出、负债、资产、保险和投资连接在一起，让用户全面了解自己的财务状况并做出更好的决策。

> **管理资金 → 保护财富 → 增长财富 → 传承财富**

### 产品架构

- **Rachan.app：** 财务数据基础，涵盖收入、支出、资产、负债、现金流、财务报表和净资产。
- **Rachan.com：** 金融服务平台，涵盖财务管理、保险、投资、信贷和金融市场。
- **Rachan AI：** 智能分析层，提供财务健康评分、风险分析、个性化建议和下一步最佳行动。

Rachan 以数据为基础，先建立可靠的 Financial Identity，再根据用户的真实需求连接合适的金融产品与机会。

### 产品方向

我们将从 Rachan.app 的金融数据基础开始，逐步扩展至 Finance、Insurance、Investment 和 Credit，并通过 Rachan.com 提供完整的金融服务体验。我们的目标是帮助用户理解资金状况、制定更好的计划、管理风险并持续积累财富。

---

## Español

### Rachan | Sistema Operativo Financiero

Rachan es un Sistema Operativo Financiero para personas y empresas. Ayuda a gestionar el dinero, proteger el patrimonio, hacer crecer los activos y planificar el futuro financiero desde un sistema conectado.

Rachan es más que una aplicación contable o una plataforma de inversión. Conecta ingresos, gastos, deudas, activos, seguros e inversiones para que los usuarios comprendan su situación financiera y tomen mejores decisiones.

> **Gestionar el dinero → Proteger el patrimonio → Hacer crecer la riqueza → Transmitir la riqueza**

### Arquitectura del producto

- **Rachan.app:** La base contable para ingresos, gastos, activos, pasivos, flujo de caja, informes financieros y patrimonio neto.
- **Rachan.com:** La plataforma financiera para Finanzas, Seguros, Inversiones, Crédito y Marketplace.
- **Rachan AI:** La capa de inteligencia que ofrece puntuación de salud financiera, análisis de riesgos, recomendaciones personalizadas y la próxima mejor acción.

Rachan prioriza los datos: primero construye una Financial Identity confiable y luego conecta al usuario con los servicios y oportunidades financieras más relevantes.

### Dirección del producto

Comenzamos con una base sólida de datos financieros en Rachan.app y después ampliamos hacia Finanzas, Seguros, Inversiones y Crédito mediante Rachan.com. Nuestro objetivo es ayudar a las personas a comprender su dinero, planificar mejor, gestionar los riesgos y construir un patrimonio sostenible.
