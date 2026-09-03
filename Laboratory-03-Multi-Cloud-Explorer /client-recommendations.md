
# Client Cloud Recommendations

## Client A – Startup Company
* **Recommended Cloud Platform:** Amazon Web Services (AWS)
* **Explanation:** AWS is ideal for startups due to its generous credit programs (AWS Activate) and extensive toolset that supports rapid deployment. Its robust auto-scaling compute capabilities allow a new application to handle initial low traffic affordably while seamlessly scaling up during rapid user growth. Additionally, AWS provides a reliable platform for developer-friendly continuous integration and deployment pipeline setups.
* **Recommended Services:**
  1. **AWS Amplify / App Runner:** Rapid mobile and web application backend deployment.
  2. **Amazon DynamoDB:** Fully managed NoSQL database for flexible data schemas.
  3. **Amazon S3:** Low-cost storage for application assets, media, and user files.

---

## Client B – University
* **Recommended Cloud Platform:** Microsoft Azure
* **Explanation:** Microsoft Azure is the most natural fit for the university because of its existing infrastructure built on Windows Server, Active Directory, and Microsoft 365. Utilizing Azure allows seamless hybrid connectivity using Microsoft Entra ID to synchronize student and faculty access without re-architecting identity platforms. Additionally, the university can leverage existing licensing discounts via Azure Hybrid Benefit to keep migration costs low.
* **Recommended Services:**
  1. **Microsoft Entra ID (Azure AD):** Identity management and single sign-on integration.
  2. **Azure Virtual Machines:** Migration of legacy Windows Server infrastructure to the cloud.
  3. **Azure SQL Database:** Managed hosting for academic databases and administrative records.

---

## Client C – AI Research Company
* **Recommended Cloud Platform:** Google Cloud Platform (GCP)
* **Explanation:** Google Cloud Platform is the industry benchmark for heavy Artificial Intelligence, Machine Learning, and high-performance data crunching workloads. GCP offers custom hardware accelerators like Tensor Processing Units (TPUs) optimized specifically for deep learning model training speed. Their ecosystem offers deep integration with ML pipelines, enabling research organizations to process complex calculations faster and more cost-effectively.
* **Recommended Services:**
  1. **Vertex AI:** Unified AI platform to build, deploy, and scale machine learning models.
  2. **Google Compute Engine (GCE) with Cloud TPUs/GPUs:** High-performance compute instances designed for deep learning.
  3. **BigQuery:** Serverless, highly scalable data warehouse for rapid analytics on massive datasets.

---

## Client D – Global E-Commerce Company
* **Recommended Cloud Platform:** Amazon Web Services (AWS)
* **Explanation:** AWS offers global reach, high availability, and proven reliability for global e-commerce deployments with fluctuating traffic peaks. With over 105 Availability Zones and global edge networks, AWS can reliably serve low-latency content to customers around the world. Its mature Auto Scaling mechanisms ensure high availability during peak shopping events (such as Black Friday) while keeping cost efficiency during quiet periods.
* **Recommended Services:**
  1. **Amazon EC2 Auto Scaling:** Dynamically scales web compute instances based on live incoming traffic volume.
  2. **Amazon CloudFront:** Global Content Delivery Network (CDN) to accelerate static asset delivery to worldwide shoppers.
  3. **Amazon Aurora:** High-performance, highly available relational database for rapid transactional order processing.

---

## Checkpoint 6 – Multi-Cloud Decision Matrix

| Business Requirement | Recommended Platform | Justification |
| :--- | :--- | :--- |
| **Startup Company** | Amazon Web Services | Cost-effective entry points, rich ecosystem support, and rapid scalability. |
| **Enterprise Organization** | Microsoft Azure / AWS | High compliance standards, multi-region operational capacity, and hybrid enterprise tooling. |
| **Microsoft Environment** | Microsoft Azure | Native integration with Active Directory, Windows Server licenses, and M365 systems. |
| **AI / Machine Learning** | Google Cloud Platform | Custom TPU hardware acceleration, Vertex AI ecosystem, and high-speed data pipelines. |
| **Kubernetes Deployment** | Google Cloud Platform | Creator of Kubernetes; offers Google Kubernetes Engine (GKE) for container operations. |
| **Global Web Application** | Amazon Web Services | Massive global footprint with CloudFront edge locations and robust auto-scaling systems. |
