# customer-support-ticket-tagger
Classify customer support tickets into predefined categories

This project demonstrates fine-tuning a pretrained language model (DeBERTa-v3-base) to classify customer support tickets into predefined categories. The objective is to automate the classification of support tickets to improve operational efficiency in an organization.

Problem Statement:

Efficiently managing customer support tickets is critical for delivering excellent customer service. However, manually tagging tickets based on their content is time-consuming, especially when handling high volumes of tickets.

This inefficiency leads to delayed ticket resolution, customer dissatisfaction, and challenges in prioritizing and routing tickets to the appropriate teams.
To automate the process of tagging customer support tickets using a Large Language Model (LLM) via text classification, the system should accurately classify tickets into predefined categories based on their content, such as Technical Support, Billing and Payments, IT support etc.


---

## 🧠 Project Type

**Fine-Tuning**: A pretrained model is further trained on a labeled dataset (customer support tickets) to adapt it to a specific text classification task.

---

## 🧾 Dataset

The dataset used for training is a CSV file containing:
- **text**: The content of the customer support ticket
- **labels**: The corresponding support category or issue type

---

## 📦 Dependencies

Install required libraries using:

```bash
pip install transformers datasets torch scikit-learn
