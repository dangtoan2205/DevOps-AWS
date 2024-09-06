# Nguyên tắc cơ bản của DevOps (CI/CD)
- - - - -

**1. Tự động hóa** quy trình phát triển, kiểm thử, triển khai và quản lý hệ thống để giảm thiểu sự can thiệp thủ công và lỗi nhân tạo (human misstake).
**2. Tích hợp liên tục** (Continuous integration - CI): Tích hợp liên tục mã nguồn từ nhiều nguồn khác nhau và test tự động để đảm bảo tính ổn định của ứng dụng.
**3. Triển khai liên tục** (Continuous Deployment - CD): Tự động triển khai các phiên bản mới của ứng dụng vào môi trường một cách tự động và an toàn.
**4. Theo dõi và phản hồi** (Monitoring and Feedback): Theo dõi sự hoạt động của ứng dụng và hệ thống thời gian thực để phát hiện và khắc phục lỗi nhanh chóng.
**5. Tự phục vụ** (Self-service): Cung cấp các công cụ cho các nhóm phát triển (Dev) và vận hành (Operation) để họ có thể làm việc một cách độc lập và hiệu quả.

**CI/CD** là viết tắt của **Continuous Integration** và **Continuous Deployment** (hoặc **Continuous Delivery**), đây là một phương pháp quy trình phát tiển phần mềm để tạo và triển khai ứng dụng một cách tự động và liên tục. Đây là một trong những phần quan trọng của quy trình phát triển phần mềm hiện đại và giúp tối ưu hóa quy trình phát triển, kiểm tra và triển khai phần mềm.
![image](https://github.com/user-attachments/assets/03181978-e9cb-4381-b1f0-65cad45dfe57)
![image](https://github.com/user-attachments/assets/0265624a-1c04-4cfe-8d28-f42eb4e28c31)

- - - - -
# Trang bị những kiến thức gì
1. Cloud Computing (AWS, Azure, GCP, ..)
2. Operating System (Windows Server, Linux, Redhat, CentOS)
3. Version Control System (Github, Gitlab, Bitbucket)
4. Project management tool (Jira, Trello)
5. Networking, Database, Security & other Cloud's managed services
6. Automation and CICD tools (Terraform, Ansigle, Jenkins, GitlabCI, GithubCI, Code Pipeline, CircleCI, ...)
7. Framework (Angular, Nodejs, Spring Boot, .NET, ..)
8. Docker and Kubernetes
9. Monitoring, Alert and Notification tools
10. Other: Problem solving, COmmunication skill

- - - - -
# Tổng quan về các dịch vụ trên AWS
**Computing & Container**
![image](https://github.com/user-attachments/assets/45cca269-61a5-4818-9fca-a2fc78ce31a2)

**Storage**
![image](https://github.com/user-attachments/assets/388b7219-dabd-43cf-afc1-fc9b7580d0af)

**Networking**
![image](https://github.com/user-attachments/assets/112b5ece-2d78-4a35-b08b-10d41b52131b)

**Database**
![image](https://github.com/user-attachments/assets/bd70d6ce-1229-446a-a0db-94c26820286e)

**Security & Identity**
![image](https://github.com/user-attachments/assets/35b53fe2-e9ca-4586-aefa-331c74a6c325)

**Management & Governance**
![image](https://github.com/user-attachments/assets/0687d1c3-d1c1-4198-b4d7-6dfc2824d9b0)

**Monitoring**
![image](https://github.com/user-attachments/assets/6140f204-56c4-4261-a5ca-b9eab5bba082)

**Messaging, Application integration**
![image](https://github.com/user-attachments/assets/fdd0f5c3-3373-4b97-83ef-2b9b2fdb432c)

**Deoloyment & Automation**
![image](https://github.com/user-attachments/assets/5380e04a-a991-4b7e-9d8f-3f5c3b1aedce)

**Migration**
![image](https://github.com/user-attachments/assets/c268ea20-5f1d-4840-9389-7ddc4126cc10)

**Big data & Data analytic**
 ![image](https://github.com/user-attachments/assets/95acb568-5fd1-43a2-8c5f-7df0673a18f4)

 **AI & Machine learning**
 ![image](https://github.com/user-attachments/assets/a0c2031f-ef15-48ed-94e1-cd4c24a4afdd)

- - - - -
# Mô hình kiến trúc
## IAM Concepts
Để có thể thiết kế & xây dựng hệ thống trên AWS đảm bảo tiêu chí về Security cũng như không gặp trouble, chúng ta cần nắm vững các concept cơ bản của IAM bao gồm:
- User
- Group
- Role
- Permission (Policy)
![image](https://github.com/user-attachments/assets/9b5a3c6d-0df8-4966-b549-e42f13848423)
























