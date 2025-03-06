# 🚗 Vehicle Configurator  

**A dynamic web-based Vehicle Configurator that allows users to customize and visualize vehicles in real time. The project includes two separate backends built with Java (Spring Boot) and C# (.NET), along with a React.js frontend.**  

---

## 📌 Features  

✅ **3D Vehicle Customization** – Modify colors, wheels, interiors, and accessories  
✅ **Real-time Visualization** – Instantly see changes applied to vehicle models  
✅ **Dual Backend Support** – Java (Spring Boot) & C# (.NET) as separate backend services  
✅ **User Authentication** – Secure login & JWT-based authentication  
✅ **Save & Compare Configurations** – Users can store and compare different vehicle setups  
✅ **Admin Dashboard** – Manage vehicle options and customization presets  
✅ **REST API & Database Support** – Uses MongoDB for storing user configurations  

---

## 🏗️ Project Structure  

```
Vehicle-Configurator/
│── backend-java/         # Java (Spring Boot) backend
│── backend-dotnet/       # C# (.NET Core) backend
│── frontend/             # React.js frontend
│── README.md             # Project Documentation
```

---

## ⚙️ Tech Stack  

### **Frontend:**  
- **React.js** – UI framework  
- **Three.js** – 3D model rendering  
- **Tailwind CSS** – Styling  

### **Backend 1: Java (Spring Boot)**  
- **Spring Boot** – REST API development  
- **MongoDB** – Database for storing user configurations  
- **JWT Authentication** – Secure login system  

### **Backend 2: C# (.NET Core)**  
- **ASP.NET Core** – REST API development  
- **MongoDB** – Database integration  
- **JWT Authentication** – Secure login system  

---

## 🛠 Installation & Setup  

### **1️⃣ Clone the repository:**  
```bash
git clone https://github.com/joshipankaj0511/Vehicle-Configurator.git
cd Vehicle-Configurator
```

---

### **2️⃣ Backend Setup**  

#### **For Java (Spring Boot) Backend**  
```bash
cd backend-java
mvn clean install
mvn spring-boot:run
```
_Default port: `http://localhost:8080`_

#### **For C# .NET Backend**  
```bash
cd backend-dotnet
dotnet restore
dotnet run
```
_Default port: `http://localhost:5000`_

---

### **3️⃣ Frontend Setup**  
```bash
cd frontend
npm install
npm start
```
_Default port: `http://localhost:3000`_

---

## 🔗 API Endpoints  

| Method | Endpoint               | Java (Spring Boot) URL         | C# (.NET Core) URL         | Description                  |
|--------|------------------------|-------------------------------|---------------------------|------------------------------|
| **POST**   | `/auth/register`   | `http://localhost:8080/auth/register` | `http://localhost:5000/auth/register` | Register new user |
| **POST**   | `/auth/login`      | `http://localhost:8080/auth/login`  | `http://localhost:5000/auth/login` | User login & JWT auth |
| **GET**    | `/vehicles`        | `http://localhost:8080/vehicles` | `http://localhost:5000/vehicles` | Get all vehicle models |
| **POST**   | `/config/save`     | `http://localhost:8080/config/save` | `http://localhost:5000/config/save` | Save a vehicle configuration |
| **GET**    | `/config/user`     | `http://localhost:8080/config/user` | `http://localhost:5000/config/user` | Get user’s saved configs |

---

## 🎨 Customization Options  

- **Exterior:** Body color, wheels, headlights  
- **Interior:** Seats, dashboard, entertainment system  
- **Performance:** Engine type, transmission, suspension  
- **Accessories:** Sunroof, spoiler, sound system  

---

## 🔥 Choosing a Backend  

By default, the frontend connects to the **Java (Spring Boot) backend**. To switch to **C# (.NET backend)**, update the API Base URL in the frontend’s `.env` file:  

```env
# For Java Backend (Default)
REACT_APP_API_BASE_URL=http://localhost:8080

# For .NET Backend
# REACT_APP_API_BASE_URL=http://localhost:5000
```

---

## 🏗️ Future Enhancements  

- ✅ AR/VR Integration for a more immersive experience  
- ✅ AI-based recommendation system for custom vehicle builds  
- ✅ Cloud-based storage for saved configurations  

---

## 🤝 Contributing  

Contributions are welcome! Fork the repo, make your changes, and create a pull request.  

---

## 📜 License  
This project is licensed under the **MIT License**.  
