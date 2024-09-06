![image](https://github.com/user-attachments/assets/09808911-1a42-496f-9072-b71756351a0c)![image](https://github.com/user-attachments/assets/e0853e74-8ea5-4377-aa1b-d59229a7a41e)# 1. Nguyên tắc cơ bản của DevOps (CI/CD)
- - - - -

**1. Tự động hóa** quy trình phát triển, kiểm thử, triển khai và quản lý hệ thống để giảm thiểu sự can thiệp thủ công và lỗi nhân tạo (human misstake).<br>
**2. Tích hợp liên tục** (Continuous integration - CI): Tích hợp liên tục mã nguồn từ nhiều nguồn khác nhau và test tự động để đảm bảo tính ổn định của ứng dụng.<br>
**3. Triển khai liên tục** (Continuous Deployment - CD): Tự động triển khai các phiên bản mới của ứng dụng vào môi trường một cách tự động và an toàn.<br>
**4. Theo dõi và phản hồi** (Monitoring and Feedback): Theo dõi sự hoạt động của ứng dụng và hệ thống thời gian thực để phát hiện và khắc phục lỗi nhanh chóng.<br>
**5. Tự phục vụ** (Self-service): Cung cấp các công cụ cho các nhóm phát triển (Dev) và vận hành (Operation) để họ có thể làm việc một cách độc lập và hiệu quả.<br>

**CI/CD** là viết tắt của **Continuous Integration** và **Continuous Deployment** (hoặc **Continuous Delivery**), đây là một phương pháp quy trình phát tiển phần mềm để tạo và triển khai ứng dụng một cách tự động và liên tục. Đây là một trong những phần quan trọng của quy trình phát triển phần mềm hiện đại và giúp tối ưu hóa quy trình phát triển, kiểm tra và triển khai phần mềm.
![image](https://github.com/user-attachments/assets/03181978-e9cb-4381-b1f0-65cad45dfe57)
![image](https://github.com/user-attachments/assets/0265624a-1c04-4cfe-8d28-f42eb4e28c31)

- - - - -
# 2. Trang bị những kiến thức gì
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
# 3. Tổng quan về các dịch vụ trên AWS
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
# 4. Mô hình kiến trúc
## IAM Concepts
Để có thể thiết kế & xây dựng hệ thống trên AWS đảm bảo tiêu chí về Security cũng như không gặp trouble, chúng ta cần nắm vững các concept cơ bản của IAM bao gồm:
- User
- Group
- Role
- Permission (Policy)
![image](https://github.com/user-attachments/assets/c20a8baf-e3cb-4b9c-bebb-a48d6c71bc86)

## Simple Storage Service (S3)
![image](https://github.com/user-attachments/assets/b748741e-a05b-4df6-a658-28e07be00e13)

## VPC & Networking
- VPC: Một mạng ảo được tạo ra ở cấp độ region.
- Subnet: Một dải IP được định nghĩa nằm trong VPC. Mỗi subnet phải được quyết định Availability Zone tại thời điểm tạo ra.
- IP Address: IP v4 hoặc v6 được cấp phát. Có 2 loại là: Public IP và Private IP.
- Routing: Xác định traffic sẽ được điều hướng đi đâu trong mạng.
- Elastic IP: IP được cấp phát riêng, có thể access từ internet (public), không bị thu hồi khi instance start -> stop.
![image](https://github.com/user-attachments/assets/8ab17e23-1aab-44f8-8a1d-725ae1f589dc)

### VPC & Networking - Components
![image](https://github.com/user-attachments/assets/49ebf242-8e15-4015-8922-8f25d9645e00)

### VPC & Networking - Standard design for a VPC
![image](https://github.com/user-attachments/assets/c2459b08-7068-462d-8186-762af5e2d843)

### VPC & Networking - Route table
![image](https://github.com/user-attachments/assets/63f611d0-eaa3-4c75-8d4c-5ffcf2fad28d)

### VPC & Networking - Standard design for Security Groups
**Security Group** <br>
Thường được dùng để gom nhóm các resource có chung network setting (in/out, protocol, port).<br>
Khi cần thiết kế cần quan tâm tới tính tái sử dụng, dễ quản lý.<br>
Source của một Srcurity Group có thể là CIDR haowjc id của một Security Group khác.<br>
Rule của Security Group là stateful và không có deny rule.<br>
**Statefull** có nghĩa là nếu Inbound cho phép traffic đi vào thì khi request tới sẽ nhận được response mà không cần explicit allow Outbound. Khác với Network ACL.<br>
![image](https://github.com/user-attachments/assets/f11e209f-01de-4518-88e1-c1a0aeddd174)

# 5. Load Balancing
- Load Balancing cho phép setting các listener (trên 1 port nào đó. VD: HTTP: 80, HTTPS: 443).
- Mỗi Listener cho phép cấu hình nhiều rule.
- Request sau khi đi vào listener, được đánh giá bởi các rule sẽ được forward tới target group phù hợp.
- Target group có nhiệm vụ health check để phát hiện và loại bỏ target un-healthy
![image](https://github.com/user-attachments/assets/9c07c739-b817-4c1a-b639-8b620c7be53e)

## Có 4 loại load balancer chính:
- Application LB
- Network LB
- Gateway LB
- Classic LB
![image](https://github.com/user-attachments/assets/f1c4567a-ca14-4494-8b0e-c62195f6eff2)

### Relational Database Service (RDB)
![image](https://github.com/user-attachments/assets/0ee371f8-a0cf-4a1e-8cd3-77157e2082c2)

#### Các mô hình triển khai RDS
![image](https://github.com/user-attachments/assets/4afd686f-c012-44f1-949c-ce12af5f1a49)

#### RDS Proxy
![image](https://github.com/user-attachments/assets/a0de04cd-a87a-4eeb-8d17-48e5f168f7c6)

## Serverless Architect (API Gateway, Cognito, Lambda)
![image](https://github.com/user-attachments/assets/758aa2fd-840d-4bb2-86d6-75869fc7cfa6)

![image](https://github.com/user-attachments/assets/a60bd397-818a-44e5-ac97-555099b23752)

![image](https://github.com/user-attachments/assets/6bc733e6-f242-4bb8-83fe-fd62a68701f8)

![image](https://github.com/user-attachments/assets/5a920fb4-6031-4278-a63a-c9f167ca93f8)


# 6. Content Delivery Network
Khi có CDN, tài nguyên của server sẽ được cache trên máy chủ Edge, request của user tới một tài nguyên trên CloudFront sẽ được redirect tới máy chủ Edge gần nhất.
![image](https://github.com/user-attachments/assets/e1f97064-7d4f-40d4-be5c-135a19f0f0eb)

Website static (chỉ gồm HTML, CSS, JS, ...) có thể được deploy lên S3 kết hợp với CloudFront.<br>
Hầu hết các framework hiện nay như Angular, Vue, Nodejs đều hỗ trợ build website thành dạng static chỉ gồm HTML, CSS, JS để deploy lên S3
![image](https://github.com/user-attachments/assets/a8823229-a91d-4e81-9c67-f77d67d7173c)

Bằng việc cấu hình các behavior khác nhau, ClouldFront giúp điều hướng request của người dùng tới đúng origin mong muốn.








