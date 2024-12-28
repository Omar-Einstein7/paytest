# Simple Payment Method App

This project is a basic Flutter application for testing a simple payment method integration. It demonstrates a straightforward implementation of a payment workflow.

## Features
- User-friendly UI for selecting payment methods.
- Integration with the Stripe payment gateway using `flutter_stripe`.
- Basic validation for payment inputs.
- Confirmation message after a successful payment.

## Prerequisites
Before running the app, ensure you have the following:
- Flutter SDK installed ([Installation Guide](https://flutter.dev/docs/get-started/install))
- An IDE like Android Studio, VS Code, or IntelliJ IDEA.
- A connected device or emulator to test the app.

## Getting Started

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/Omar-Einstein7/paytest.git
   cd paytest
   ```

2. **Install Dependencies:**
   ```bash
   flutter pub get
   ```

3. **Run the App:**
   ```bash
   flutter run
   ```

## Project Structure
```
lib/
|-- main.dart        # Entry point of the application
|-- screens/         # Contains the UI screens
|   |-- home_screen.dart
|-- widgets/         # Reusable UI components
|-- models/          # Data models for payment methods
|-- services/        # Handles payment gateway integration
```

## How It Works
1. **Home Screen:**
   - Users select a payment method and proceed with the payment.
   - Integrates with `flutter_stripe` for handling Stripe payments.
2. **Payment Validation:**
   - The app validates payment inputs before processing.
3. **Confirmation Message:**
   - Displays the payment status (success or failure).

## Stripe Payment Gateway
This app uses `flutter_stripe` to integrate with Stripe's payment system. Update the API keys and configuration in `services/payment_service.dart` to match your Stripe account.

## Testing
To run tests, execute the following command:
```bash
flutter test
```

## Screenshots
![Home Screen](docs/screenshots/home_screen.png)

## Dependencies
- [Flutter](https://flutter.dev/)
- [flutter_stripe](https://pub.dev/packages/flutter_stripe) (Stripe integration)
- [dio](https://pub.dev/packages/dio) (for HTTP requests)

## Contributing
Contributions are welcome! Feel free to open an issue or submit a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Happy coding! ✨

