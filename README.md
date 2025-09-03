# Analysis Application Suite  

A set of applications built with **C# .NET Framework** that help businesses monitor competitor pricing, analyze market data, and track changes over time.  

## 📦 Applications  

### 1. Main Analysis Application  
A desktop application for analyzing and comparing room prices with competitors.  

#### 🚀 Features  
- **Automated Data Collection** – Takes user inputs and retrieves information from external websites.  
- **Smart Comparison** – Compares collected data with existing records to generate actionable insights.  
- **Price Evaluation** – Analyzes room prices against competitors and suggests whether prices should be increased or decreased, along with the exact percentage.  
- **Admin Panel** – Manage and monitor user activity:  
  - Track how many analyses each user has performed  
  - View overall usage statistics  
- **User Panel** – Simple and intuitive interface for users to run analyses and view results.  

---

### 2. Monitoring Helper Application  
A supporting application that checks requests at scheduled intervals and notifies if any changes are detected in the monitored data.  

#### 🔍 Features  
- **Scheduled Checks** – Runs at predefined time intervals.  
- **Change Detection** – Monitors given requests and highlights if the underlying data has changed.  
- **Integration** – Works alongside the main Analysis Application to keep results up to date.  

---

## 🏢 Use Case  
These applications are ideal for businesses in:  
- **Hospitality** (e.g., hotels, guesthouses, hostels)   

With these tools, companies can:  
- Track competitors’ pricing strategies  
- Adjust their own pricing dynamically  
- Detect data changes automatically  
- Gain insights into market trends and maximize profitability  

---

## 📸 Screenshots  
![analiz_room](https://github.com/coden0th/Analysis-Application/blob/main/Screenshots/analiz_room.jpeg?raw=true)
![add_hotel](https://github.com/coden0th/Analysis-Application/blob/main/Screenshots/otel_ekle.jpg?raw=true)
![add_companies](https://github.com/coden0th/Analysis-Application/blob/main/Screenshots/Add_companies.jpeg?raw=true)
![analiz](https://github.com/coden0th/Analysis-Application/blob/main/Screenshots/analiz.jpeg?raw=true)
![report_bug](https://github.com/coden0th/Analysis-Application/blob/main/Screenshots/report_bug.jpeg?raw=true)

---

## ⚙️ How It Works  
1. User provides input (e.g., room details, location, competitor criteria).  
2. The main system fetches data from relevant websites.  
3. Data is compared with competitors’ prices and existing records.  
4. The application provides a price adjustment recommendation (e.g., *increase by 5%* or *decrease by 3%*).  
5. The helper application runs scheduled checks to see if monitored data has changed.  
6. Results are available in both the **User Panel** and **Admin Panel**.  

---

## 🛠️ Tech Stack  
- **Language:** C#  
- **Framework:** .NET Framework  
- **Data Collection:** Web scraping (from competitor websites)   

---

## 🔒 Access & Authentication  
- Secure login for users and admins  
- Role-based access control  

