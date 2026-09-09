### ผู้จัดทำ

นางสาวรสริน เมืองหงษ์

รหัสนักศึกษา 673380289-4

SEC1

---
### 📂Test Cases

ผลการทดลองและหลักฐานการทดสอบถูกจัดเก็บไว้ในโฟลเดอร์ `test-cases`

| ไฟล์ | ใช้แสดง |
|---|---|
| `1_POST_accounts.png` | การสร้าง Account |
| `2_GET_accounts_byId.png` | การตรวจสอบข้อมูล Account |
| `3_POST_deposit.png` | การฝากเงินสำเร็จ |
| `4_GET_accounts_byId_after_deposit.png` | การตรวจสอบยอดเงินหลังการฝาก |
| `5_deposit_transaction_table.png` | การตรวจสอบข้อมูล DepositTransaction |
| `6_POST_deposit_testrollback.png` | การทดลอง Rollback เมื่อเกิด Error โดยมี `@Transactional` |
| `7_GET_accounts_byId_testrollback.png` | การตรวจสอบ Account หลังเกิด Rollback |
| `8_deposit_transaction_table_testrollback.png` | การตรวจสอบ DepositTransaction หลังเกิด Rollback |
| `9_POST_deposit_noTransaction.png` | การทดลองฝากเงินกรณีไม่มี `@Transactional` |
| `10_GET_accounts_byId_noTransaction.png` | การตรวจสอบ Account กรณีไม่มี `@Transactional` |
| `11_deposit_transaction_table_noTransaction.png` | การตรวจสอบ DepositTransaction กรณีไม่มี `@Transactional` |

---
### 📝Report

รายงานผลการทดลองฉบับเต็มอยู่ในไฟล์:

`Lab9_673380289-4_Report.pdf`
