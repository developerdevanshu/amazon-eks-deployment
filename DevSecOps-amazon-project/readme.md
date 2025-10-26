# Amazon Clone Project (3-Tier Architecture)

## Project Overview
This project is a fully functional Amazon clone built with modern web technologies, implementing a 3-tier architecture. It demonstrates a complete e-commerce solution with frontend, backend, and database integration.

## 🛠️ Technologies Used

### Frontend
- React.js
- Redux for state management
- Tailwind CSS for styling
- Responsive design principles

### Infrastructure & DevOps
- Docker for containerization
- Kubernetes for orchestration
- Jenkins for CI/CD pipeline
- HTTPS configuration with host-based routing

## 🚀 Features
- Product catalog with search functionality
- Shopping cart management
- Product details and ratings
- Carousel for featured products
- Responsive navigation
- Category-based browsing
- Secure checkout process

## 📦 Project Structure
```
DevSecOps-amazon-project/
├── Dockerfile
├── Jenkinsfile
├── package.json
├── tailwind.config.js
├── k8s-hostbased-https/
│   └── amazon-deplyment-hostbased.yaml
├── public/
│   ├── data/
│   └── images/
└── src/
    ├── components/
    ├── redux/
    └── utils/
```

## 🔧 Setup and Installation

1. Clone the repository:
```bash
git clone https://github.com/developerdevanshu/amazon-3-tier-application.git
```

2. Install dependencies:
```bash
npm install
```

3. Run the development server:
```bash
npm start
```

## 🚢 Deployment

### Docker Build
```bash
docker build -t amazon-clone .
```

### Kubernetes Deployment
```bash
kubectl apply -f k8s-hostbased-https/amazon-deplyment-hostbased.yaml
```

## 🔐 Security Features
- HTTPS configuration
- Host-based routing
- Secure API endpoints
- DevSecOps practices implementation

## 🤝 Contributing
Feel free to contribute to this project by creating issues or submitting pull requests.

## 📝 License
This project is licensed under the MIT License - see the LICENSE file for details.

## 👨‍💻 Author
- [Devanshu](https://github.com/developerdevanshu)

## 🔗 Links
- [Project Repository](https://github.com/developerdevanshu/amazon-3-tier-application)
- [Live Demo](https://your-live-demo-link.com)

## 📞 Contact
For any queries or suggestions, feel free to reach out:
- GitHub: [@developerdevanshu](https://github.com/developerdevanshu)
