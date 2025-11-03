# 🎓 Online Learning Platform using AWS

A **cloud-based online learning platform** built with **AWS Serverless Architecture**.  
Students can enroll, browse courses, watch videos, and track their learning progress — all without any traditional servers.

---

## ☁️ AWS Services Used
- **S3** – Hosts the website and videos  
- **API Gateway** – Connects frontend with backend  
- **Lambda** – Handles enrollment and progress updates  
- **DynamoDB** – Stores user details and course progress  
- **CloudFront** – Delivers content globally with low latency  
- **CloudWatch** – Logs and monitoring  
- **IAM** – Provides secure access between AWS services  

---

## ⚙️ Workflow
1. User opens the site hosted in **S3 / CloudFront**  
2. Enrolls through a web form  
3. **API Gateway → Lambda** stores details in **DynamoDB**  
4. Videos are streamed via **S3 + CloudFront**  
5. Progress updates are tracked automatically in **DynamoDB**

---

## 💡 Features
✅ Serverless & scalable design  
✅ Real-time progress tracking  
✅ Cost-effective (pay-per-use)  
✅ No backend maintenance  

---

## 🏁 Conclusion
This project shows how **AWS Serverless Services** can power a complete e-learning platform efficiently —  
with scalability, high availability, and zero server management. ☁️
