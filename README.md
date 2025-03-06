# 🚗 Vehicle Configurator  

**A dynamic web-based Vehicle Configurator that allows users to customize and visualize vehicles in real time. Built with React, Node.js, and MongoDB.**  

---

## 📌 Features  

✅ **3D Vehicle Customization** - Users can modify colors, wheels, accessories, and more  
✅ **Real-time Rendering** - Changes are updated instantly on the vehicle model  
✅ **User Authentication** - Secure login and profile management  
✅ **Save & Compare** - Users can save configurations and compare different models  
✅ **Admin Panel** - Manage vehicle options and customization presets  
✅ **REST API Integration** - Backend powered by Node.js & Express  
✅ **Database Support** - Configurations stored in MongoDB  

---

## ⚙️ Tech Stack  

- **Frontend:** React.js, Three.js (for 3D models), Tailwind CSS  
- **Backend:** Node.js, Express.js  
- **Database:** MongoDB  
- **Authentication:** JWT-based auth system  
- **Deployment:** Docker, AWS/GCP  

---

## 🛠 Installation & Setup  

Clone the repository:  
```bash
git clone https://github.com/joshipankaj0511/Vehicle-Configurator.git
cd Vehicle-Configurator
```

### **Backend Setup**  
```bash
cd backend
npm install
npm start
```

### **Frontend Setup**  
```bash
cd frontend
npm install
npm start
```

---

## 🔗 API Endpoints  

| Method | Endpoint               | Description                  |
|--------|------------------------|------------------------------|
| **POST**   | `/auth/register`       | Register new user             |
| **POST**   | `/auth/login`          | User login & JWT auth         |
| **GET**    | `/vehicles`           | Get all vehicle models        |
| **POST**   | `/config/save`        | Save a vehicle configuration  |
| **GET**    | `/config/user`        | Get user’s saved configs      |

---

## 🎨 Customization Options  

- **Exterior:** Body color, wheels, headlights  
- **Interior:** Seats, dashboard, entertainment system  
- **Performance:** Engine type, transmission, suspension  
- **Accessories:** Sunroof, spoiler, sound system  

---

## 🤝 Contributing  

Contributions are welcome! Fork the repo, make your changes, and create a pull request.  

---

## 📜 License  
This project is licensed under the **MIT License**.  
