# ISS Tracker & Notification System (A FUN PROJECT)🌌🚀

**Track the International Space Station (ISS) and get notified when it's near your location during dark hours. Perfect for stargazing enthusiasts with or without a telescope!**

## 📜 Features
- **Location Tracking**: Detects your geographic coordinates.  
- **ISS Position**: Tracks the ISS's real-time position in orbit.  
- **Nighttime Detection**: Sends alerts only when it's dark outside.  
- **Email Notifications**: Get an email prompt to "Look Up!"  

## 💻 How It Works
1. The script uses [ISS API](http://open-notify.org/Open-Notify-API/ISS-Location-Now/) for real-time position data.    
2. Nighttime conditions are checked using the sunset/sunrise API.  
3. When all conditions align, you receive an email to view the ISS.  

## 🚀 Setup
1. Clone this repository:  
   ```bash  
   git clone https://github.com/yourusername/iss_tracker.git  
   ```  
2. Install dependencies:  
   ```bash  
   pip install -r requirements.txt  
   ```  
3. Add your credentials to `.env`:  
   ```
   EMAIL=your_email  
   PASSWORD=your_email_password  
   ```  

## 🎯 Usage
Run the script:  
```bash  
python iss_tracker.py  
```  

You'll receive a notification email whenever the ISS is visible at your location during dark hours.  

## 📧 Email Preview
**Subject**: "Look Up! The ISS is Here!"  
**Body**: "The ISS is currently visible in your area. Step outside, look up, and enjoy the view!"
