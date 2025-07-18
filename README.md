# travel_picks

## What has changed

- splitting main.dart into 
    - app.dart
    - screens/travel_home.dart
    - widgets/country_card.dart

### main.dart

- changed BottomNavigationBar into NavigationBar
- items renamed to destinations
- BottomNavigationBarItem renamed to NavigationDestination

- main only contains main() & runApp()

### app.dart

contains only Scaffold & start logics like navigations, navbar etc.

### screens/travel_home.dart

contains the screen Widget as StatefulWidget including addCountry method

### widgets/country_card.dart

contains the countryCard Widget

