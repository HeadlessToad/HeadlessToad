# Hi, I'm Omri Asudon

**B.Sc. Computer Science Student @ Bar Ilan University | IDF Captain (Res.)**

I am a software developer focused on **Backend Engineering, AI/ML, and Systems Architecture**. I specialize in bridging the gap between sophisticated research and production-ready, automated infrastructure. My approach combines the technical precision of a CS degree with the operational leadership of an IDF Captain.

---

### Expertise & Tech Stack

* **Languages:** Python (FastAPI), Java, C++, Node.js, SQL, JavaScript.
* **AI & DevOps:** Automated ML Pipelines (MLOps), Docker, Google Cloud Platform (Cloud Run, GCS), Linux.
* **Backend & Systems:** RESTful API Design, Microservices, System Architecture, SMTP/Communication Protocols.

---

### Featured Projects

#### [Villa Guest Engagement & CRM Automation](https://github.com/HeadlessToad/Villa-Contact-Automation)
* **Developed** a production-ready serverless backend that automated 100% of guest outreach workflows by engineering a **FastAPI** webhook listener integrated with **Google Sheets**.
* **Architected** a cloud-native infrastructure on **GCP Cloud Run** using **Docker**, utilizing **Google Cloud Storage (GCS)** as a persistent registry to eliminate duplicate communications.
* **Orchestrated** engagement by integrating **SMTP SSL**, ensuring 99.9% delivery reliability through robust error handling and data normalization.

#### [Waste Image Recognition & Analysis Platform](https://github.com/HeadlessToad/Final-Project.git)
* **Engineered** an end-to-end automated ML training pipeline on **GCP** that reduced model deployment cycles by containerizing workflows with **Docker**.
* **Architected** a scalable cloud-native platform for real-time image classification, facilitating seamless transitions from research models to production environments.

#### [YouTube Replica Backend & Mobile](https://github.com/HeadlessToad/Mytube.git)
* **Spearheaded** the development of a distributed application featuring an **Android Studio** mobile frontend and a custom **Node.js** backend.
* **Optimized** system performance by designing modular **REST APIs** and implementing relational data persistence via **SQL** to handle high-frequency metadata requests.

* #### 🏨 Villa Contact Automation
*A production-ready backend automation service driving instantaneous guest engagement by integrating spreadsheet-driven CRM rows with enterprise communication APIs.*

| Metric / Attribute | Details |
| :--- | :--- |
| **Tech Stack** | Python 3.12, FastAPI, Pydantic v2, Uvicorn, Google Cloud Run, Google Cloud Storage, Meta WhatsApp Cloud API, SMTP |
| **Architecture**| Serverless Webhook Engine / Event-Driven Automation |
| **Core Focus** | High-reliability delivery, defensive key-normalization, and idempotency tracking |

* **Architected and Deployed** a containerized FastAPI webhook engine to Google Cloud Run to process inbound booking-inquiry payloads via an automated spreadsheet pipeline.
* **Engineered a Robust Payload Normalizer** utilizing Pydantic v2 to isolate core models from brittle, changing spreadsheet column headers, resolving dynamic headers with non-alphanumeric characters into stable `snake_case` fields.
* **Integrated Meta WhatsApp Cloud API & Secure SMTP Suite** to dynamically build localized, positional multi-parameter template payloads for automated custom WhatsApp dispatch alongside high-fidelity fallback email notifications with dynamic brochure attachments.
* **Implemented Fault-Tolerant Auditing** by constructing a decentralized Cloud Storage registry tracking sent communication metadata with automated open-fail configurations to maximize service continuity.
* **Streamlined CI/CD Infrastructure** via a parameterized Google Cloud Build setup, wrapping continuous deployment to `europe-west1` and automated secret injection (`GOOGLE_CREDENTIALS_JSON`) inside a single-command deployment manifest.

➡️ **[View Repository](https://github.com/HeadlessToad/Villa-Contact-Automation)**

---

### Connect with Me
* **LinkedIn:** [linkedin.com/in/omri-asudon](https://www.linkedin.com/in/omri-asudon)
* **Email:** [doppelger.oa@gmail.com](mailto:doppelger.oa@gmail.com)

---
*"Beyond the diagrams and code, I believe innovation is only truly meaningful when it serves a human purpose. I am driven to contribute to projects that translate complex engineering into a tangible, positive impact on people’s lives."*
