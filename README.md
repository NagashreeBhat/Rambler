# Rambler
I spent more than half the time on designing and architecting the app(I wanted to follow MVVM architecture to showcase my skills writing modular code)

**Key Feature**
1. Used Kotlin
2. MVVM(loosely coupled)
3. LiveData
4. Google Fit

**Repository Pattern**: The viewModel is seperated from Data Source
The view is seperatedd from the business logic

The project has two modeuls - Activities, Modules

**Bonus Feature**: Added toggle button for chronological view in ascending or descending format

**How to install**:
1. Open the project in Android Studio
2. Under the Google API Console create a new/existing app with FitnessAPI enabled(use the client.json file/firebase connection)
3. Enable acccess from Google Fit(it should have some data inorder for the app to display) else it throws a warning message of no steps found in Google Fit 


![MainScreen In Ascending order of dates](https://github.com/NagashreeBhat/Rambler/blob/master/Screenshot_20200710-162548.png)
