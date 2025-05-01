#Intelligent Recipe Recommendation System
This is an advanced Recipe Suggestion System that helps users discover the most relevant recipes based on their available ingredients, preferred cuisine, course type, dietary preferences, tags and total cooking time.

#🚀 Features
🔍 Input multiple filters to refine search:

Ingredients

Cuisine (e.g., Indian, Chinese)

Course (e.g., Main course, Dessert, Side Dish)

Diet (e.g., Vegetarian, Non Vegetarian)

Tags (e.g., spicy, quick)

Maximum total cooking time

🧠 Smart matching using TF-IDF vectorization and cosine similarity

📊 Rank-based recipe suggestions

📦 Works efficiently with large datasets

#🛠️ Technologies Used
Python

Pandas

Scikit-learn

NumPy

Jupyter Notebook

#🧩 Project Structure

recipes_suggestion.ipynb     # Main Notebook containing all code and logic
food_recipes.csv                          # Dataset of recipes (expected format)
⚙️ How It Works
Data Cleaning: Preprocess the recipes dataset to handle missing values and prepare fields.

Feature Engineering: Combine selected recipe attributes into a unified text corpus.

Vectorization: Convert combined text into numerical vectors using TF-IDF.

Filtering: User provides input for:

Ingredients

Cuisine

Course

Diet

Tags

Maximum Total Time

Matching: System calculates cosine similarity between the input vector and each recipe.

Output: Top 10 similar recipes are displayed.

#📥 Inputs
The user can input values for the following fields:

Field	Type	Description
Ingredients	List	Comma-separated list of ingredients
Cuisine	String	Preferred cuisine
Course	String	Type of course (e.g., Main course)
Diet	String	Dietary preference (e.g., Vegetarian)
Tags	List	Related tags (e.g., spicy, healthy)
Total Time	Integer	Max total preparation time in minutes

#📤 Sample Input

Ingredients: chicken, garlic, onion
Cuisine: Indian
Course: Main course
Diet: High-Protein
Tags: spicy, dinner
Total Time: 45
📈 Sample Output
Returns top 10 recipes sorted by relevance score:

Recipe Name	Cuisine	  Total     Time	     Diet	
Spicy Garlic Chicken	Indian	40 mins	High-Protein	
Tandoori Chicken	Indian	45 mins	High-Protein	
...	...	...	...	...

#🛠️ Setup Instructions
Clone the repository


git clone https://github.com/Pratyush-Basu/Recipe-Recommendation-System.git
cd Recipe-Recommendation-System
Install dependencies


pip install pandas numpy scikit-learn
Run the notebook


jupyter notebook
#🤝 Contribution
Feel free to raise issues or submit pull requests to improve this project.

#🧑 Author
Pratyush Basu


