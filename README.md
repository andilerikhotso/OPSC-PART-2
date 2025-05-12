BudgetEase – Personal Budget Tracker App

BudgetEase, a fully functional personal budget tracking app that we built using Kotlin in Android Studio. This app was developed as part of our coursework for Part 2 — App Prototype Development, and we're proud to say that it meets all the requirements outlined in the assignment brief. The goal was to create a working prototype that focuses on user experience, data persistence, and core budgeting functionalities, and we’ve ensured it delivers on every front.

The app starts with a secure login screen where users enter their username and password to access their budget space. After logging in, users are welcomed with a friendly and colorful dashboard that allows them to view transactions, add expenses, add income, and create custom categories. We designed this interface to be clean, intuitive, and easy to navigate for users of all experience levels.

When users add an expense, they can enter the amount, select the date using a built-in date picker, add a description, assign it to a category, and even upload an optional receipt photo. The app also supports monthly spending goals—users can set both minimum and maximum limits, giving them better control over their finances. All the information is stored locally using RoomDB, so the app works even when there's no internet connection.

One of our favorite parts of building this app was implementing the reporting features. Users can view all expenses within a selected time period, and if a receipt photo was attached, it’s easily accessible from the list. We also added functionality that allows users to see how much they’ve spent per category over a specific time range. This kind of visibility helps people make informed decisions about their spending habits.

We made sure that the app is robust and doesn’t crash when unexpected input is provided. For example, if a user leaves a required field empty or enters the wrong data type, the app responds with helpful prompts instead of errors. We also used logging throughout our code to show our understanding of the app’s inner workings and to help with debugging.

To manage version control, we used GitHub, where we committed our progress regularly. We also integrated GitHub Actions to automatically build and test the app on every push, ensuring that it works smoothly not just on our machine, but anywhere. Our code is well-commented, organized, and demonstrates our knowledge of working with layouts, activities, intents, event handling, and RoomDB.
