# 🗄️ SQL Security Lab
# 🗄️ مختبر أمان قواعد البيانات

## Project Overview
## نظرة عامة على المشروع
This project demonstrates security practices for SQL databases, including preventing SQL injection, access control, and data protection.

يعرض هذا المشروع ممارسات الأمان لقواعد بيانات SQL، بما في ذلك منع هجمات الحقن SQL، التحكم بالوصول، وحماية البيانات.

## Lab Environment
## بيئة المختبر
- DBMS: MySQL 8.0 / إدارة قواعد البيانات: MySQL 8.0  
- Users / المستخدمون: 3 regular users + 1 admin  
- Database / قاعدة البيانات: EmployeeRecords / سجلات الموظفين  
- Tools / الأدوات: SQL queries, permissions, prepared statements / استعلامات SQL، صلاحيات المستخدمين، استعلامات مُحضرة

## Lab Tasks
## مهام المختبر
1. **Access Control / التحكم بالوصول**  
   - Create users with different privileges / إنشاء مستخدمين بصلاحيات مختلفة  
   - Assign read/write permissions / تعيين أذونات قراءة وكتابة  
   - Restrict admin access / تقييد وصول المسؤولين

2. **SQL Injection Prevention / منع هجمات الحقن SQL**  
   - Identify vulnerable queries / تحديد الاستعلامات الضعيفة  
   - Use prepared statements / استخدام الاستعلامات المحضرة  
   - Sanitize user inputs / تنظيف مدخلات المستخدم

3. **Data Protection / حماية البيانات**  
   - Encrypt sensitive data / تشفير البيانات الحساسة  
   - Regular database backups / النسخ الاحتياطي الدوري للقاعدة  
   - Audit access logs / مراجعة سجلات الوصول

## Observations
## الملاحظات
- Users with limited privileges cannot access restricted tables / المستخدمون بصلاحيات محدودة لا يمكنهم الوصول للجداول المقيدة  
- Prepared statements prevent SQL injection attacks / الاستعلامات المحضرة تمنع هجمات الحقن  
- Encryption and backups protect data integrity / التشفير والنسخ الاحتياطي يحمي سلامة البيانات

## Conclusion
## الخلاصة
This SQL security lab demonstrates essential practices for securing database environments.  
Mastering these tasks prepares the learner for real-world database security challenges.

يوضح هذا المختبر ممارسات أساسية لتأمين بيئات قواعد البيانات.  
إتقان هذه المهام يجهز المتعلم لمواجهة تحديات أمان قواعد البيانات في العالم الحقيقي.
