# VRV-Security  

This repository demonstrates advanced **Authentication** and **Authorization** techniques using **NestJS**, designed for the backend assignment at **VRV Security**. The project implements JWT authentication, role-based access control, API key integration, and other real-world security practices.  

GitHub Repository: [VRV-Security](https://github.com/chinmay706/VRV-Security.git)  

---

## Key Features  

- **JWT Authentication**: Refresh tokens and token invalidation.  
- **Role-Based Access Control (RBAC)**: Manage access based on user roles.  
- **Claims-Based Authorization**: Define access rules using claims.  
- **Policy-Based Authorization**: Enforce flexible access policies.  
- **API Key Integration**: Secure API endpoints with API keys.  
- **Server-Side Sessions**: Robust session management.  
- **Two-Factor Authentication (2FA)**: Add an extra security layer.  
- **Google Authentication**: OAuth-based login integration.  
- **Passport.js Integration**: Simplifies session handling.  

---

## Getting Started  

### Prerequisites  

Ensure you have the following installed:  
- **Docker**: For database setup.  
- **Node.js**: To run the application.  

---

### Setup  

1. **Clone the repository**:  
   ```bash  
   git clone https://github.com/chinmay706/VRV-Security.git  
   cd VRV-Security  
## 1. Configure Environment Variables  
## Duplicate .env.example and rename it to .env  
cp .env.example .env  

## Open the .env file and provide values for the required variables  
## Example:  
## DATABASE_HOST=localhost  
## JWT_SECRET=your_secret_key  

## 2. Install Dependencies  
npm install  

## 3. Set up PostgreSQL and Redis with Docker  
docker compose up  

## 4. Running the Application  

## Development mode  
npm run start  

## Watch mode (auto-restart on file changes)  
npm run start:dev  

## Production mode  
npm run start:prod  

## 5. Testing the Application  
## Open Postman and import the VRV-Security.postman_collection file  
## Explore the APIs under the collection "VRV-Security" in your workspace
