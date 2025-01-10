
# **Feedback System for Companies and Users**

This repository provides a feedback system allowing companies and users to submit, manage, and embed feedback. It features company and user authentication, company-specific feedback, and a testimonial system where companies can embed feedback on their websites.

## **Features**

- **Company Admin Routes:**
  - **Signup & Login:** Register and authenticate companies.
  - **Company Profile:** View, update, or delete company details.
  - **Feedback Management:** Companies can view feedback submitted by users.
  - **Admin Functions:** Change password, search, and delete company profiles.

- **User Routes:**
  - **Signup & Login:** Register and authenticate users.
  - **Feedback Submission:** Authenticated users can submit feedback to specific companies.

- **Feedback System:**
  - **Company Feedback:** Companies receive feedback from users that can be embedded on their website.
  - **Feedback Retrieval:** Admins and users can view feedback related to a specific company.

- **Authentication & Authorization:**
  - Secured routes using JWT authentication.
  - Admin middleware to ensure only authenticated company admins can access their data.

## **Technologies Used**

- **Backend:** Node.js, Express.js, MongoDB, Mongoose
- **Authentication:** JWT (JSON Web Tokens)
- **Validation:** Zod for schema validation
- **Security:** bcrypt for password hashing

## **Installation**

To get started with the project, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/smartcraze/FeedMeBack.git
   ```

2. Navigate into the project directory:

   ```bash
   cd FeedMeBack
   ```

3. Install the dependencies:

   ```bash
   npm install
   ```

4. Set up environment variables in a `.env` file:

5. Start the server:

   ```bash
   npm run dev
   ```


## **Contributing**

We welcome open-source contributions! If you're interested in contributing, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-name`).
3. Make your changes and commit them (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature-name`).
5. Open a pull request to merge your changes into the `main` branch.

### **Contributions Guidelines:**

- Ensure your code is well-documented and follows the project's coding standards.
- Write tests for new features or bug fixes.
- Be respectful and constructive in all discussions and contributions.

