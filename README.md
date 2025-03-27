# getFit

getFit is designed to guide users toward their health goals with clear, goal-based programs.

Main Purpose and Target Audience: Modern lifestyles often limit time for exercise, getFit tackles this
issue by providing straightforward workout plans, simple tracking features, and guidance for users of
all experience levels who need to achieve goals ranging from strength and endurance to weight
management.

Key Features: getFit delivers goal-oriented programs that allow users to track sets, reps, rest times,
and bodyweight. A diet log is available to record meals and offer healthy eating tips. A streak system
rewards daily consistency, while a badge system celebrates major achievements (e.g., maintaining a
routine for a year).

Platform and Data Storage: Built with Flutter, getFit runs on Android from a single codebase.
It stores height, weight, sex, workout logs, and diet entries.

##**Phase One**
###**🔹 1. UI Development**
**Wireframe flow contains 12 screens. The designs were created using Figma and present the main layout and interaction flow of the app.**
![image](/image.jpg)
- **Onboarding (Welcome Screen):** The first screen where users are welcomed and introduced to the app’s purpose, with a button to begin.
- **Register Page 1:** Allows users to create an account by entering their basic information like name and email.
- **Register Page 2:** Users complete their profile by adding additional personal data such as their gender, height, weight and age to customize their app experience.
- **Login Page:** Enables returning users to log into the app. A registration link is also available for new users.
- **Success Register Page:** Confirms successful registration and redirects users to the dashboard.
- **Dashboard (Home Screen):** The screen displays a fitness app interface that offers predefined workout programs with options to view more details. It includes trackers for workouts and calories, presented in a weekly calendar format for progress monitoring. A button to access the user's account is also visible, indicating features for personalization and management. The app focuses on providing structured exercise plans and tracking tools to help users achieve their fitness goals.
- **Workout Details 1:**  Users can navigate back to the main menu using a dedicated button. The page allows users to start a workout and track their progress by marking exercises as completed. Exercises are organized into sets, providing a structured approach. A button is available to open detailed descriptions for each exercise, offering guidance and instructions. Additionally, users can indicate when an exercise is done, enabling real-time progress tracking. This functionality emphasizes user interaction, detailed exercise guidance, progress monitoring, and ease of navigation within the app.
- **Workout Details 2:**  It provides detailed descriptions and step-by-step instructions for exercises, ensuring users understand how to perform them correctly. A button located at the upper left corner allows users to navigate back to the previous page, ensuring easy navigation.
- **Add Workout Schedule:** The image displays a workout scheduling page in a fitness app, featuring two primary buttons: "Choose Workout" and "Custom Workout." The "Choose Workout" button allows users to select from predefined workout plans provided by the app, while the "Custom Workout" button enables users to create their own workout plan by adding custom exercises, which are then displayed in a lower container. Once the workout plan is set, either by selecting a predefined plan or creating a custom one, users can save it using the "Save" button. A back button at the top of the page ensures easy navigation, allowing users to return to the previous screen. This functionality emphasizes the flexibility of selecting predefined plans or creating custom workouts, organizing exercises into a cohesive plan, saving the plan for future use, and providing seamless navigation within the app.
- **Add Exercise:** The interface focuses on tracking workout sets and repetitions. Users can input repetitions, add sets, log weight, edit/delete entries, and add comments. A save button stores the workout data, making it useful for structured strength training.
- **Profile Screen:** Displays user data (e.g., name, height, weight) and offers options to update personal information.
- **Congratulations Screen:** A motivational screen shown when a workout is completed successfully, encouraging users to maintain their streak.
