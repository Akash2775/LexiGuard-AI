# LexiGuard: Your Contextual AI Legal Assistant

Navigating legal documents is a daunting task for the average person, filled with complex jargon, hidden clauses, and potential risks. **LexiGuard** aims to democratize legal understanding by providing an AI-powered assistant that can analyze legal texts and offer clear, contextual insights tailored to the user's specific role (e.g., Tenant, Lender, Employee). Our mission is to empower individuals to make informed decisions and protect their interests when dealing with contracts, agreements, and other legal documents.

## ✨ Features

* **Contextual AI Analysis:** Get summaries, obligations, and risk assessments from the perspective of a specific role (e.g., "Tenant," "Landlord," "Borrower," "Employee"). This is the core differentiating feature.
* **Multiple Input Methods:**
    * **Text Input:** Paste any legal text directly for instant analysis.
    * **Document Upload:** Upload PDF, PNG, or JPG files.
* **OCR Integration:** Automatically extract text from scanned documents and images using Google Cloud Vision API.
* **Real-time Insights:** Get analysis results quickly and efficiently displayed in a user-friendly interface.
* **Secure & Scalable:** Built on Google Cloud and Firebase's serverless architecture, ensuring robust performance and data security.
* **User-friendly Interface:** Intuitive design with React and Material-UI.



## 🏗️ Architecture

LexiGuard leverages a powerful, scalable serverless architecture on Google Cloud and Firebase:
* **Authentication:** Firebase Authentication for secure user management.
* **Backend:** Cloud Functions for Firebase handle document processing, OCR, and AI interactions.
* **AI & ML:**
    * **Vertex AI (Gemini Model):** The core AI engine for contextual legal text analysis.
    * **Google Cloud Vision API:** Used for Optical Character Recognition (OCR) on uploaded images and scanned PDFs.
* **Database & Storage:**
    * **Cloud Firestore:** Stores AI analysis results.
    * **Cloud Storage for Firebase:** Stores user-uploaded documents temporarily.

## 🛠️ Technologies Used

* **Frontend:** React, TypeScript, Material-UI (MUI), Firebase Hosting
* **Backend:** Node.js, Cloud Functions for Firebase
* **Database & Storage:** Cloud Firestore, Cloud Storage for Firebase
* **Authentication:** Firebase Authentication (Google Sign-In)
* **AI/ML:** Google Vertex AI (Gemini Model), Google Cloud Vision API

