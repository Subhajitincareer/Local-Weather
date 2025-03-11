# Weather App 🌦️

This is a simple **Weather App** that fetches real-time weather data based on the user's **current location** using the **FreeCodeCamp Weather API**. The app displays the **temperature, weather condition, location, and an icon** representing the weather.

---

## 🌟 Features
- ✅ **Detects user location** using the **Geolocation API**  
- ✅ **Fetches live weather data** using the FreeCodeCamp Weather API  
- ✅ **Displays weather details** (temperature, description, and icon)  
- ✅ **Supports temperature unit toggle** between **°C and °F**  
- ✅ **Dynamic weather backgrounds** based on the weather condition  

---

## 🚀 Technologies Used
- **HTML** → Structure of the app  
- **CSS** → Styling, animations, and dynamic backgrounds  
- **JavaScript (Vanilla JS)** → Fetch API, DOM manipulation, and Geolocation API  
- **FreeCodeCamp Weather API** → Fetching live weather data  
- **Font Awesome** → Weather icons  

---

## 📜 How It Works
1. The app requests **location access** from the user.  
2. Once access is granted, it **fetches latitude and longitude** using the **Geolocation API**.  
3. The app sends a **GET request** to the FreeCodeCamp Weather API using the coordinates.  
4. The API responds with **weather data**, including:
   - Temperature (in °C)
   - Weather condition (clear, rainy, cloudy, etc.)
   - Location (city, country)
   - Weather icon  
5. The app dynamically **updates the UI** with this information.  
6. Users can **toggle between Celsius (°C) and Fahrenheit (°F)** using a button.  

---

## 📦 API Used
The app uses the **FreeCodeCamp Weather API**:


This API returns weather data based on the given latitude and longitude.

---

## 🛠️ Setup & Usage
1. **Download or clone** the repository.
2. Open the `index.html` file in any modern browser.
3. Allow **location access** when prompted.
4. View your **current weather details** in the app.

---

## 🔧 Possible Improvements
- 🌍 **Add city search** feature instead of just fetching current location  
- 🎨 **Improve UI** with animations and better styles  
- ☁️ **Add a forecast feature** for multiple days  
- 📱 **Make the app responsive** for all devices  

---

## ⚠️ Known Issues
- If **location access is denied**, the app will not work properly.
- Some weather icons may **not match perfectly** with the actual weather conditions.

---

## 📝 License
This project is **free to use** and open-source. You are welcome to modify and improve it. 🚀

---

Enjoy using the **Weather App**! 🌤️🌧️❄️

