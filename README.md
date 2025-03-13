# **TripleTen.Music**  

## **Project Description:**  
This project analyzes the music preferences of residents in two cities — Springfield and Shelbyville. The primary goal is to test three hypotheses based on real user listening data.  

## **Hypotheses:**  
1. User activity varies depending on the day of the week and differs between cities.  
2. On Monday mornings and Friday evenings, residents of Springfield and Shelbyville listen to different genres.  
3. Pop music is more popular in Springfield, while rap is more popular in Shelbyville.  

## **Dataset:**  
- `userID` — user identifier  
- `Track` — track title  
- `artist` — artist name  
- `genre` — music genre  
- `City` — user's city  
- `time` — exact time the track was played  
- `Day` — day of the week  

## **Tools Used:**  
- Python (pandas)  
- Exploratory Data Analysis (EDA)  

## **Key Findings:**  

### **1️⃣ User Activity Analysis**  
- In **Springfield**, the number of songs played peaks on Mondays and Fridays, while Wednesdays show decreased activity.  
- In **Shelbyville**, users listen to more music on Wednesdays, while Mondays and Fridays have lower activity.  
- ✅ Hypothesis confirmed.  

### **2️⃣ Genre Preferences on Different Days**  
- The **top 15 genres** on Monday morning and Friday evening are nearly identical in both cities.  
- In Springfield, the large number of missing values resulted in `'unknown'` appearing in the top 15 genres. This could impact the reliability of the conclusions.  
- ✅ Hypothesis partially confirmed: while there is no major difference between cities, popular genres slightly vary.  

### **3️⃣ Most Popular Genres**  
- **Pop music** is the most popular genre in both Springfield and Shelbyville.  
- **Rap music** did not make it into the top 5 in either city.  
- ✅ Hypothesis partially confirmed: pop music is indeed popular, but there is no significant difference between the cities.  

---  
This project demonstrates proficiency in data analysis, hypothesis testing, and working with real-world datasets.
