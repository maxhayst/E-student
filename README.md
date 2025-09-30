# Student Information System Mobile App

A comprehensive Flutter mobile application for student information management, designed to match the UI/UX shown in the provided design mockups.

## Features

### 🏠 Home Screen
- Student profile information display
- Real-time notifications
- Quick access cards for main features
- Academic performance overview

### 📅 Schedule Screen
- Daily and weekly schedule views
- Class notifications and reminders
- Schedule changes tracking
- Weekly statistics

### 📊 Grades Screen
- Subject-wise performance tracking
- Lab work grades and status
- Academic statistics
- Progress monitoring

### 🎓 Scholarship Screen
- Scholarship application tracking
- Document submission
- Application status monitoring
- Requirements and guidelines

### 👥 Consultations Screen
- Teacher consultation booking
- Upcoming consultations management
- Teacher availability and ratings
- Online/offline meeting options

### ⚙️ More Screen
- Additional app features
- Settings and preferences
- Help and support
- App information

## Technical Stack

- **Framework**: Flutter
- **State Management**: Provider
- **Architecture**: MVVM with clean separation of concerns
- **UI Components**: Material Design 3
- **Data Models**: Dart classes with JSON serialization

## Project Structure

```
lib/
├── main.dart                 # App entry point
├── models/                   # Data models
│   ├── student.dart
│   ├── notification.dart
│   ├── schedule.dart
│   ├── grade.dart
│   ├── scholarship.dart
│   └── consultation.dart
├── providers/                # State management
│   └── app_state.dart
├── screens/                  # UI screens
│   ├── home_screen.dart
│   ├── schedule_screen.dart
│   ├── grades_screen.dart
│   ├── scholarship_screen.dart
│   ├── consultations_screen.dart
│   └── more_screen.dart
└── widgets/                  # Reusable UI components
    ├── notification_card.dart
    ├── quick_access_card.dart
    ├── academic_performance_card.dart
    ├── schedule_item_card.dart
    ├── schedule_change_card.dart
    ├── general_stats_card.dart
    ├── subject_card.dart
    ├── scholarship_application_card.dart
    ├── scholarship_type_card.dart
    ├── consultation_card.dart
    └── teacher_card.dart
```

## Getting Started

### Prerequisites
- Flutter SDK (3.9.3 or higher)
- Dart SDK
- Android Studio / VS Code with Flutter extensions

### Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd dart_application_2
```

2. Install dependencies:
```bash
flutter pub get
```

3. Run the app:
```bash
flutter run
```

## Dependencies

- `cupertino_icons`: ^1.0.2
- `http`: ^1.2.2
- `uuid`: ^4.4.2
- `intl`: ^0.19.0
- `shared_preferences`: ^2.2.2
- `provider`: ^6.1.1
- `flutter_svg`: ^2.0.9
- `table_calendar`: ^3.0.9

## Design Features

### UI/UX Design
- **Material Design 3**: Modern, clean interface
- **Responsive Layout**: Adapts to different screen sizes
- **Consistent Theming**: Unified color scheme and typography
- **Intuitive Navigation**: Bottom navigation with clear icons
- **Card-based Layout**: Easy-to-scan information presentation

### Color Scheme
- Primary: Blue (#2196F3)
- Success: Green (#4CAF50)
- Warning: Orange (#FF9800)
- Error: Red (#F44336)
- Background: Light Grey (#FAFAFA)

### Typography
- Headers: Roboto Bold, 24px
- Subheaders: Roboto SemiBold, 18px
- Body: Roboto Regular, 16px
- Captions: Roboto Regular, 14px

## Key Components

### State Management
The app uses Provider for state management with a centralized `AppState` class that manages:
- Student information
- Notifications
- Schedule data
- Grades and subjects
- Scholarship applications
- Consultations and teachers

### Data Models
Comprehensive data models for all entities:
- `Student`: User profile and academic info
- `AppNotification`: System notifications
- `ScheduleItem`: Class schedules
- `Subject`: Academic subjects with grades
- `ScholarshipApplication`: Scholarship tracking
- `Consultation`: Teacher consultations

### Widget Architecture
- **Screen Widgets**: Full-page UI components
- **Card Widgets**: Reusable information containers
- **Form Widgets**: Input and selection components
- **Navigation Widgets**: Bottom navigation and routing

## Future Enhancements

- [ ] Backend API integration
- [ ] Real-time notifications
- [ ] Offline data synchronization
- [ ] Push notifications
- [ ] Dark mode support
- [ ] Multi-language support
- [ ] Advanced analytics
- [ ] Social features

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Add tests if applicable
5. Submit a pull request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Support

For support and questions, please contact the development team or create an issue in the repository.