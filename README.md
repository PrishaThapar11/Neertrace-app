# NeerTrace
NeerTrace: Real-time water quality monitoring and heavy metal pollution analysis using Streamlit.

# 🌊 NeerTrace

 Detect. Visualize. Protect. 🛡️

NeerTrace is a **real-time water quality monitoring tool** built with Streamlit. It helps researchers, environmentalists, and policymakers quickly **detect heavy metal contamination** in water and **visualize pollution levels** on interactive maps.  

---

## ⚡ Key Features

- 📁 **Batch CSV Upload** – Upload real-world sensor or survey data instantly.  
- 🔬 **Single-Sample Analysis** – Enter water sample data manually and get results immediately.  
- 📊 **Pollution Indices Computed** – CF (Contamination Factor), Igeo (Geoaccumulation Index), PLI (Pollution Load Index), HMPI (Heavy Metal Pollution Index).  
- 🗺️ **Interactive Maps** – Color-coded markers for pollution severity.  
- 💾 **Downloadable Reports** – Export computed indices as CSV for research or reporting.  

---

## 🛠️ Technologies Used

- **Python** – Core programming language  
- **Streamlit** – Web app framework for interactive UI  
- **Pandas & NumPy** – Data handling & computation  
- **Folium** – Map visualization  
- **GitHub** – Version control & collaboration  

---

## 🎬 Demo

Watch the live demo here: https://drive.google.com/file/d/1QdDZyiQ4teUWuJWPTuttPOzzMSokjd6i/view?usp=sharing 

**Screenshots included in the repo:**
1. CSV upload and main interface  ![CSV Upload](screenshots/csvupload_and_mainInterface.png)
2. Computed indices table (PLI, HMPI, CF, Igeo)  ![Indices Table](screenshots/computedindicestable.png)  
3. Color-coded map with sample points ![Map with Samples](screenshots/colorcodedmap.png) 
4. Manual entry ![Manual Entry](screenshots/manualentry.png)  
5. Banner and Results ![Results](screenshots/bannerandresults.png)  
6. Single-sample analysis with mini map & download button ![Banner Results](screenshots/minimap.png)  


🧩 Why NeerTrace?

NeerTrace is not just a project, it's a practical solution for environmental monitoring:

Helps researchers analyze real-world water samples quickly.

Supports decision-makers to spot pollution hotspots on a map.

Allows local communities to visualize water quality near them.

Computes scientifically-backed indices like CF, Igeo, PLI, HMPI for accurate pollution assessment.

📂 Repository Structure
NeerTrace/
├─ streamlit_app.py      # Main app
├─ hmpi_utils.py         # Pollution indices computation
├─ requirements.txt      # Dependencies
├─ assets/               # Icons, images, sample CSVs
├─ README.md  

---

   git clone https://github.com/<your-username>/NeerTrace.git

