# Kindergardens
### Project Overview:

-**Title:** Mapping Kindergartens in Salzburg
-**Tool:** Leaflet API
-**Study Area:** Salzburg, Austria
-**Link to Web Map:** https://anoshgayratovna.github.io/Kindergardens/
-**Author:** Dilshoda Norboeva

This project is an interactive web map that displays kindergardens in Salzburg, Austria. The main goal is to provide a user-friendly tool for finding kindergardens for both parents and guardians, as well as to offer a visual platform for analyzing the retail landscape of the city.

---

### **Target Users**

- **Parents and guardians:** Searching for nearby kindergartens.
- **Urban planners and local government:** Monitoring educational facility coverage.
- **Researchers:** Studying early childhood infrastructure.
- **Teachers and school administrators:** Tracking neighboring institutions.


---

### **Data Sources**

- **OpenStreetMap (OSM):** The primary source for kindergarden locations and attributes.
- **Overpass API:** Used to query and filter OSM data for relevant categories (e.g., `kindergarden`).

---

### **Methodology**

- **Data Collection:** Overpass API is used to fetch up-to-date information on kindergardens in Salzburg.
- **Data Processing:** The data is cleaned and structured for mapping (extracting coordinates, names, opening hours, type (public/private), optional metadata (address, contact)).
- **Visualization:** 
1.ArcGIS Pro: Used to convert data to GeoJSON file
2.Leaflet API: Used to build the interactive map
3.Map tiles: OpenStreetMap via Leaflet tile providers
4.JavaScript: Handled map events, marker logic, pop-ups
5.Visual Studio Code: Change files, overview and edit
6.GitHub Pages: Hosted the project for public access
7.CSS: Styled map container and interface
- **User Interface:** Users can click on kindergardens to view details such as name, opening hours, type and other information.

---

### **Design Choices**

- **Color-coded markers:** Each marker indicates a kindergarden
- **Interactive pop-ups:** Show name and basic info.
- **Smooth animation:** Map zoom/pan and marker transitions.
- **Responsive design:** Viewable on desktop and mobile.
- **Minimal layout:** Clean and intuitive for general users

---

### **Spatial Analysis & Insights**

- **Concentration:** Many kindergartens clustered in central Salzburg.
- **Gaps identified:** Some outer residential areas (e.g., Liefering or Gnigl) have fewer options.
- **Equity of access:** Map helps identify underserved neighborhoods.

---

### **Possible Improvements**

- Add filter functionality (e.g., by public/private, capacity).
- Show distance from user location.
- Integrate real-time data (e.g., availability).
- Add routing function (walking/driving directions).

---

### **Critical Reflection**

- **Strengths:** User-friendly, open-access tool with localized data.
- **Limitations:** Static data; relies on manual updates.
- **Scalability:** Could be expanded to other cities
- **Technical reflection:** Leaflet is lightweight but not ideal for advanced analytics (e.g., clustering, heatmaps)
- **Ethical consideration:** Ensure data privacy, especially with sensitive info like children’s facilities

---

### **Key Takeaways**

- This project illustrates the power of interactive web mapping in enhancing public access to educational infrastructure.
- It empowers families and supports evidence-based planning by visualizing the spatial distribution of kindergardens.
- Modern GIS technologies make such projects accessible to both users and professionals.
