# การวางโครงสร้างโฟลเดอร์สำหรับโปรเจค Go

refs: [https://github.com/golang-standards/project-layout](https://github.com/golang-standards/project-layout)

- `/cmd`: โฟลเดอร์นี้ใช้สำหรับแอปพลิเคชันหลักของโปรเจค.
- `/internal`: โฟลเดอร์นี้ใช้สำหรับโค้ดที่ไม่ต้องการให้แอปพลิเคชันอื่นนอกจากแอปพลิเคชันในโปรเจคนี้เข้าถึง.
- `/pkg`: โฟลเดอร์นี้ใช้สำหรับโค้ดที่ต้องการให้แอปพลิเคชันอื่นในโปรเจคนี้หรือแอปพลิเคชันภายนอกเข้าถึง.
- `/api`: โฟลเดอร์นี้ใช้สำหรับไฟล์ API definitions และ protocol files.
- `/web`: โฟลเดอร์นี้ใช้สำหรับ Web application specific components.
- `/configs`: โฟลเดอร์นี้ใช้สำหรับไฟล์ Configuration.
- `/init`: โฟลเดอร์นี้ใช้สำหรับไฟล์ System init (systemd, upstart, sysv) และ process manager/supervisor (runit, supervisord) configs.
- `/scripts`: โฟลเดอร์นี้ใช้สำหรับ Scripts to perform various build, install, analysis, etc operations.
- `/build`: โฟลเดอร์นี้ใช้สำหรับ Packaging and Continuous Integration.
- `/deployments`: โฟลเดอร์นี้ใช้สำหรับ IaaS, PaaS, system and container orchestration deployment configurations and templates.
- `/test`: โฟลเดอร์นี้ใช้สำหรับ Additional external test apps and test data.
- `/docs`: โฟลเดอร์นี้ใช้สำหรับไฟล์ Documentation.
- `/tools`: โฟลเดอร์นี้ใช้สำหรับ Tools and utilities.
- `/examples`: โฟลเดอร์นี้ใช้สำหรับ Examples and sample code.
- `/third_party`: โฟลเดอร์นี้ใช้สำหรับ Third party utilities.
- `/githooks`: โฟลเดอร์นี้ใช้สำหรับ Git hooks.
- `/assets`: โฟลเดอร์นี้ใช้สำหรับ Assets and other resources (images, logos, etc.).
- `/website`: โฟลเดอร์นี้ใช้สำหรับ Website data (if you have one).
