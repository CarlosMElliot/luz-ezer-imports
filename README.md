# Business Inquiry Page | Luz Ezer Imports

A high-conversion, dark-themed business inquiry form designed for **Luz Ezer Imports**. This page allows potential business partners (Supermarkets, Restaurants, Wholesalers) to submit their details directly to the administration.

## 🚀 Live Demo
The form is configured to redirect to:
[https://carlosmelliot.github.io/luz-ezer-imports/](https://carlosmelliot.github.io/luz-ezer-imports/)

## 🛠️ Tech Stack
* **HTML5 & CSS3**: Semantic structure and custom styling.
* **Tailwind CSS**: Utility-first framework for responsive layout and spacing.
* **Formspree**: Serverless backend for handling form submissions and email notifications.
* **Google Fonts**: High-impact typography (Black, Italic, Uppercase).

## 📋 Features
* **Responsive Design**: Fully optimized for mobile, tablet, and desktop using Tailwind's grid system.
* **Spam Protection**: Includes a hidden `_gotcha` honeypot field to prevent automated bot submissions.
* **Dark Mode UI**: A modern Zinc-based aesthetic with "Electric Blue" accents.
* **Custom Validation**: Mandatory fields for essential business data (Owner, Email, Phone).
* **Post-Submission Redirect**: Automatically sends users back to the main site upon successful submission.

## ⚙️ Configuration
The form is linked to Formspree endpoint `xzdjorbb`. 

### Form Fields:
| Field Name | Type | Description |
| :--- | :--- | :--- |
| `owner_name` | Text | Name of the business owner |
| `business_name` | Text | Registered business name |
| `address` | Text | Physical street address |
| `email` | Email | Contact email address |
| `phone` | Tel | Business contact number |
| `business_type` | Select | Category (Supermarket, Restaurant, etc.) |
| `monthly_volume`| Text | Estimated units per month |
| `message` | Textarea | Additional details or specific requests |

## 🛠️ Installation & Setup
1. Clone the repository:
   ```bash
   git clone [https://github.com/carlosmelliot/luz-ezer-imports.git](https://github.com/carlosmelliot/luz-ezer-imports.git)
2. Open index.html in any modern web browser.
3. To change the email destination, update the action attribute in the <form> tag with a new Formspree ID.
