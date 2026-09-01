# Cloud Platform Recommendations for CloudNova Clients

## Client A — Startup Company
**Recommended Platform:** Amazon Web Services (AWS)

**Explanation:** Since Client A has a limited budget but expects rapid growth, AWS is ideal because of its pay-as-you-go pricing and generous free-tier/startup credit programs (e.g., AWS Activate). Its auto-scaling capabilities mean the startup only pays for what it uses today while having a clear path to scale up services as the mobile app's user base grows. AWS's large ecosystem also makes it easy to find developers and documentation as the team expands.

**Services to use:**
1. **Amazon EC2** or **AWS Lambda** — for hosting the mobile app's backend, scaling automatically with demand.
2. **Amazon RDS** or **DynamoDB** — for a managed database that grows with the app.
3. **Amazon S3 + CloudFront** — for storing and delivering static assets (images, app content) quickly to users worldwide.

---

## Client B — University
**Recommended Platform:** Microsoft Azure

**Explanation:** Since the university already relies on Windows Server, Microsoft 365, and Active Directory, Azure is the natural choice because it integrates directly with these existing systems. This minimizes the learning curve for IT staff and avoids costly re-architecting of identity and access management. Azure Arc and Azure AD Connect also allow the university to migrate services gradually rather than all at once, which fits an institution moving cautiously to the cloud.

**Services to use:**
1. **Azure Active Directory (Entra ID)** — extends the university's existing on-prem AD to the cloud.
2. **Azure Virtual Machines** — to migrate existing Windows Server workloads.
3. **Microsoft 365 + Azure integration** — for unified email, collaboration, and file storage.

---

## Client C — AI Research Company
**Recommended Platform:** Google Cloud Platform (GCP)

**Explanation:** Because Client C develops AI/ML applications requiring high-performance computing, GCP is the strongest fit thanks to its custom Tensor Processing Units (TPUs) and Vertex AI platform, which are purpose-built for training and deploying machine learning models efficiently. GCP's heritage as the creator of TensorFlow also means its tooling and documentation for AI research are especially mature.

**Services to use:**
1. **Vertex AI** — for building, training, and deploying ML models.
2. **Compute Engine with TPUs/GPUs** — for high-performance model training.
3. **BigQuery** — for large-scale data analysis to support research datasets.

---

## Client D — Global E-Commerce Company
**Recommended Platform:** Amazon Web Services (AWS)

**Explanation:** Since Client D needs highly available infrastructure with automatic scaling for a global customer base, AWS is well suited due to its extensive network of regions and edge locations, which reduces latency for customers worldwide. AWS also has a long track record hosting large-scale e-commerce platforms (including Amazon.com itself), giving it proven reliability and scaling patterns for handling traffic spikes like sales events.

**Services to use:**
1. **Amazon EC2 with Auto Scaling** — to handle fluctuating global traffic automatically.
2. **Amazon CloudFront** — CDN for fast content delivery to customers worldwide.
3. **Amazon Aurora / DynamoDB** — highly available, globally distributed databases.

---

## Multi-Cloud Decision Matrix

| Business Requirement | Recommended Platform | Justification |
|---|---|---|
| Startup Company | AWS | Flexible pay-as-you-go pricing and startup credit programs support growth without upfront cost. |
| Enterprise Organization | AWS or Azure | Both provide enterprise SLAs and compliance support; choice depends on existing vendor relationships. |
| Microsoft Environment | Azure | Native integration with Windows Server, Active Directory, and Microsoft 365. |
| AI / Machine Learning | GCP | TPUs and Vertex AI give it an edge for ML workloads. |
| Kubernetes Deployment | GCP | GKE is the most mature managed Kubernetes offering. |
| Global Web Application | AWS | Largest global region/edge footprint plus mature CDN and auto-scaling. |
