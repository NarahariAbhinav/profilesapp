# 🔐 Build a Secure Web App for File Sharing using AWS Transfer Family

## 📌 Objective
To develop and deploy a modern full-stack web application using **React.js** and **AWS Amplify**, integrating user authentication, serverless backend functions (via **AWS Lambda**), and a secure database for managing user data.

## 🎯 Relevance
AWS Amplify simplifies full-stack development by integrating hosting, authentication, APIs, and backend logic into a single workflow. This reduces complexity, speeds up deployment, and ensures scalability for modern web apps.

---

## ⚙️ Methods and Materials

### 🖥️ Frontend
- **React.js** – JavaScript library for building the UI

### 🧠 Backend
- **AWS Lambda** – Serverless compute to execute backend logic

### 🔐 Authentication
- **AWS Amplify Auth (Cognito)** – Manages secure user authentication

### 🗂️ Database
- **AWS Amplify DataStore / DynamoDB** – Stores user data and syncs across devices

### 🌐 Hosting
- **AWS Amplify Hosting** – Global deployment with CDN

### 🔧 Key Development Tools
- **AWS Amplify CLI** – Setup & deployment
- **Node.js & npm** – Runtime & package manager
- **Git & GitHub** – Version control
- **Visual Studio Code** – Development environment

---

## 🔄 Process Flow

1. Initialize React App using Create React App.
2. Connect to AWS Amplify via CLI.
3. Add Authentication with Amplify Auth (Sign-In & Sign-Out).
4. Create Lambda function to store user email after signup.
5. Integrate API & Database for real-time interaction.
6. Deploy app using Amplify Hosting.

---

## 🖥️ Web Interface Features

- Secure Sign-up/Login with Amplify Auth (Cognito)
- Automatic email capture & backend storage on registration
- Real-time data interaction with the database
- Live deployment using Amplify Hosting

---

## ✅ Testing Results

- Successfully deployed full-stack app
- Lambda function verified for email capture on sign-up
- Confirmed DynamoDB data insertion
- User-friendly interface with secure login flow

---

## 🚫 Limitations

- Currently supports only Amazon S3 buckets within the same AWS account.
- Maximum single file upload size is **160 GB**.
- Folder names starting or ending with a dot (`.`) are not supported due to legacy naming issues.

---

## 🔮 Future Directions

- **Cross-Account Access**: Enable file sharing across departments or partners.
- **Data Dashboards**: Track uploads/downloads for better visibility and transparency.

---

## 📚 References

- [AWS Transfer Family Web App Setup – AWS Docs](https://docs.aws.amazon.com/transfer/latest/userguide/transfer-web-app.html)
- [Scaling Data Access with Amazon S3 Access Grants](https://aws.amazon.com/blogs/storage/introducing-amazon-s3-access-grants/)
- [AWS Transfer Family Developer Guide](https://docs.aws.amazon.com/transfer/latest/userguide/what-is-aws-transfer.html)

---

## 🙏 Acknowledgements

Special thanks to **Dr. Naresh Vurukonda** and **Prof. Chandrakanth Wani** for their guidance and support throughout this project. Their insights were instrumental to its success.

---

## 👨‍💻 Author

**Narahari Abhinav**  
SAP ID: 70572200031  
B.Tech – STME, NMIMS Hyderabad  
Department of CSE (Data Science)
