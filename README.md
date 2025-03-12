NutriPlan-AI based diet planner 

Overview

NutriPlan is an AI-driven web application designed for nutrition and diet planning. It empowers users to create personalized dietary plans and search for food items using the Nutritionix database. The system intelligently recommends foods based on extracted nutritional features, individual user preferences, and specific dietary goals. Furthermore, it provides a comprehensive nutritional breakdown of suggested foods, utilizing the latest Estimated Energy Requirement (EER) equation [1][2].

Installation Instructions

1.  Ensure that Python 3 is installed on your system.
2.  Install Flask by executing the following command:

    ```bash
    pip install flask
    ```
3.  Start the Flask server using the command:

    ```bash
    python flask_server.py
    ```

How to Use

Searching & Adding Foods

Users can search for food items to add to their food log via the Nutritionix NLP API [6]. The search functionality supports multiple food items within a single query.

Example:

If a user enters multiple food items in the search bar, such as:

🍎🥑 "1 apple, 2 eggs, a bowl of rice"

the system will analyze the input and display the food items in a results table [5].

📌 Adding to Nutrition Log

*   Click the double arrow icon to transfer food details into the nutrition label [7].
*   Select the desired date and time to log the food.

Food History & Logs

Users can track their food intake history for any selected day.

✅ Features:

*   View past entries in the food history log.
*   Delete items from the history log using the delete icon.
*   Labels indicate whether a food is high or low in specific macronutrients.
*   Clicking on a label displays a Decision Tree AI model, providing an explanation of how the classification was determined.

Nutritional Tracking & Graphs

This section offers an interactive breakdown of daily macronutrient intake.

📊 Features:

*   Users can select a date and view their macronutrient breakdown in various graph formats [8].
*   The system suggests additional foods to help balance nutrition levels.
*   Users have the option to reject specific food suggestions by adding them to a "Do Not Suggest" list.

Personalized Diet Planning

Users can define their dietary preferences by adjusting macronutrient sliders.

📌 Key Features:

*   Recommended intake values are provided.
*   Users can modify macronutrient goals based on their individual health needs.
OUTPUTS:

<img width="1429" alt="Screenshot 2025-03-12 at 6 28 26 PM" src="https://github.com/user-attachments/assets/950e9e45-4f97-433e-b7d5-2d0ce2ce13d2" />
<img width="1429" alt="Screenshot 2025-03-12 at 6 28 15 PM" src="https://github.com/user-attachments/assets/0998a524-118d-4c47-86e1-d3d394a17dba" />
<img width="1429" alt="Screenshot 2025-03-12 at 6 28 00 PM" src="https://github.com/user-attachments/assets/8920fc91-3f56-442e-890c-d32a24f683a9" />
<img width="1429" alt="Screenshot 2025-03-12 at 6 27 37 PM" src="https://github.com/user-attachments/assets/183367cf-7325-4489-b10c-6de706996eb9" />
<img width="1429" alt="Screenshot 2025-03-12 at 6 27 14 PM" src="https://github.com/user-attachments/assets/a45e72f4-4384-4c9f-ac08-e16059d41725" />



  
                                                                                                 THANK YOU
