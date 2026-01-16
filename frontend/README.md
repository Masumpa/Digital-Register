# Digital Farm Register - Frontend

A modern Flutter application for smallholder farmers to digitally manage their farms, crops, livestock, and labor.

## Features

### Implemented (Current MVP)
- **User Authentication**
  - Secure login with validation
  - User registration flow
  - Session management

- **Farm Management**
  - Create and manage multiple farms
  - Farm details (name, area, location, description)
  - List view with search and filtering

- **Crop Management**
  - Track crop planting and growth stages
  - Record fertilizer/pesticide inputs
  - Harvest tracking and yield recording
  - Crop performance reports

- **User Interface**
  - Clean, farmer-friendly design
  - Responsive layout for mobile devices
  - Reusable widget components
  - Form validation and error handling

### Coming Soon
- Livestock management (health, vaccinations, breeding)
- Labor management (attendance, tasks, wages)
- Offline support with data synchronization
- Advanced reports and analytics
- Multi-language support (English, Swahili)

## Project Structure
```text
frontend/
│
├── pubspec.yaml
├── pubspec.lock
├── analysis_options.yaml
├── README.md
├── .gitignore
│
├── android/
│   ├── app/
│   │   ├── src/main/
│   │   │   ├── AndroidManifest.xml
│   │   │   └── res/
│   │   └── build.gradle
│   └── build.gradle
│
├── ios/
│   ├── Runner/
│   │   ├── Assets.xcassets/
│   │   ├── Info.plist
│   │   └── Runner-Bridging-Header.h
│   └── Podfile
│
├── web/
│   ├── index.html
│   ├── favicon.png
│   └── icons/
│
└── lib/
    │
    ├── main.dart
    ├── app.dart
    │
    ├── config/
    │   └── constants.dart
    │
    ├── models/
    │   ├── user.dart
    │   ├── farm.dart
    │   ├── crop.dart
    │   ├── crop_input.dart
    │   └── harvest.dart
    │
    ├── services/
    │   └── api_service.dart
    │
    ├── providers/
    │   └── auth_provider.dart
    │
    ├── screens/
    │   ├── auth/
    │   │   ├── login_screen.dart
    │   │   └── register_screen.dart
    │   │
    │   ├── farms/
    │   │   ├── farms_list_screen.dart
    │   │   ├── farm_detail_screen.dart
    │   │   └── add_edit_farm_screen.dart
    │   │
    │   └── crops/
    │       ├── crops_list_screen.dart
    │       ├── crop_detail_screen.dart
    │       ├── add_edit_crop_screen.dart
    │       ├── crop_inputs_screen.dart
    │       ├── add_crop_input_screen.dart
    │       ├── harvests_screen.dart
    │       ├── add_harvest_screen.dart
    │       └── crop_report_screen.dart
    │
    ├── widgets/
    │   ├── custom_app_bar.dart
    │   ├── loading_indicator.dart
    │   ├── error_widget.dart
    │   └── custom_text_field.dart
    │
    └── utils/
        └── validators.dart
```

