# CardWorkout 🃏

A fun and interactive iOS app that displays random playing cards with timer functionality. Perfect for card-based workouts or games!

## Features

- **Random Card Display**: Automatically cycles through all 52 playing cards
- **Timer Control**: Start, stop, and restart the card cycling timer
- **Complete Deck**: Includes all standard playing cards (Hearts, Diamonds, Spades, Clubs)
- **Smooth UI**: Clean interface with rounded buttons and smooth animations

## Screenshots

*Add your app screenshots here*

## How It Works

The app displays playing cards that change automatically every 0.1 seconds. Users can:
- **Stop**: Pause the card cycling
- **Restart**: Resume the card cycling from the current card

## Technical Details

### Architecture
- **MVC Pattern**: Uses Model-View-Controller architecture
- **Timer-based Animation**: Uses `Timer.scheduledTimer` for smooth card transitions
- **Asset Management**: All 52 card images stored in Assets.xcassets

### Key Components

#### CardSelectionVC.swift
- Main view controller handling the card display logic
- Manages timer lifecycle and user interactions
- Handles start/stop/restart functionality

#### Deck.swift
- Contains static array of all 52 playing card images
- Organized by suits: Hearts (H), Diamonds (D), Spades (S), Clubs (C)
- Each card represented as UIImage for optimal performance

## Requirements

- iOS 13.0+
- Xcode 12.0+
- Swift 5.0+

## Installation

1. Clone the repository:
```bash
git clone https://github.com/devdiop221/card-workout-app.git
```

2. Open the project in Xcode:
```bash
open CardWorkout.xcodeproj
```

3. Build and run the project on your device or simulator

## Usage

1. Launch the app
2. Watch as cards automatically cycle through the deck
3. Tap "Stop" to pause the cycling
4. Tap "Restart" to resume cycling

## Project Structure

```
CardWorkout/
├── CardWorkout/
│   ├── AppDelegate.swift
│   ├── SceneDelegate.swift
│   ├── CardSelectionVC.swift    # Main view controller
│   ├── Deck.swift               # Card deck model
│   ├── Base.lproj/
│   │   └── Main.storyboard      # UI layout
│   ├── Assets.xcassets/         # Card images (52 cards)
│   └── Info.plist
├── CardWorkout.xcodeproj/
└── README.md
```

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## Future Enhancements

- [ ] Add workout exercises for each card
- [ ] Implement different timer intervals
- [ ] Add sound effects
- [ ] Create different game modes
- [ ] Add statistics tracking
- [ ] Implement card filtering options

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Author

**Mouhamed** - *Initial work*

## Acknowledgments

- Card images sourced from standard playing card designs
- Built with Swift and UIKit
- Inspired by fitness card workout routines

---

Made with ❤️ for fitness enthusiasts and card game lovers!
