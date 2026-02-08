# LebanonShop User App

A comprehensive e-commerce user application built with Flutter, designed to provide a seamless online shopping experience. This application serves as the storefront for users to browse products, manage orders, and interact with the platform.

## 📱 Key Features

### 🔐 Authentication & Security
*   **User Registration & Login**: Email/Password login and sign-up.
*   **Social Login**: Integration with Google, Facebook, and Apple Sign-In.
*   **Secure Session**: Token-based authentication and secure storage.
*   **Password Management**: Forgot password and reset functionality.

### 🛍️ Product Browsing & Discovery
*   **Categories & Brands**: Browse products by categories or specific brands.
*   **Advanced Search**: Search for products with keywords.
*   **Filtering & Sorting**: Filter products by price, detailed attributes, and condition (New/Used).
*   **Product Details**: Rich product presentations with images, descriptions, specifications, and reviews.
*   **Comparison**: Compare multiple products side-by-side.
*   **Featured & Flash Deals**: Highlighted deals and limited-time offers.
*   **Banners**: Promotional banners for checking latest trends.

### 🛒 Shopping Experience
*   **Cart Management**: Easy add-to-cart, update quantities, and remove items.
*   **Wishlist**: Save favorite items for later.
*   **Coupons**: Apply discount codes at checkout.
*   **Shipping Options**: Choose preferred shipping methods.
*   **Secure Checkout**: Streamlined checkout process with address selection.

### 📦 Order Management
*   **Order Tracking**: Real-time tracking of order status.
*   **Order History**: View past orders and detailed summaries.
*   **Reorder**: Quickly repeat previous orders.
*   **Refund Requests**: Manage and track refund requests.

### 👤 User Profile & Wallet
*   **Address Management**: Manage multiple delivery addresses with Google Maps integration.
*   **Wallet System**: Built-in wallet for easy payments and transaction history.
*   **Loyalty Points**: Earn and redeem loyalty points on purchases.
*   **Profile Settings**: Update personal information and app preferences.

### 💬 Communication & Support
*   **Live Chat**: Chat with sellers or admin for inquiries.
*   **Support Tickets**: Raise and track support tickets for issues.
*   **Contact Us**: Direct contact channel.
*   **Push Notifications**: Receive updates on orders, offers, and chat messages.

### 🌐 Localization & Theme
*   **Multi-language Support**: English and Arabic (RTL support).
*   **Theme Customization**: Light and Dark mode support.

## 🛠️ Technology Stack

*   **Framework**: [Flutter](https://flutter.dev/) (Dart)
*   **State Management**: [Provider](https://pub.dev/packages/provider)
*   **Architecture**: Feature-based folder structure with Controller-Service-Repository pattern.
*   **Networking**: [Dio](https://pub.dev/packages/dio) & [Http](https://pub.dev/packages/http)
*   **Local Database**: [Drift](https://pub.dev/packages/drift) (SQLite) & [Shared Preferences](https://pub.dev/packages/shared_preferences)
*   **Backend Services**: 
    *   Firebase Core
    *   Firebase Auth (Social Login)
    *   Firebase Cloud Messaging (Push Notifications)
*   **Maps**: [Google Maps Flutter](https://pub.dev/packages/google_maps_flutter)
*   **Navigation**: [Go Router](https://pub.dev/packages/go_router)
*   **UI Components**: Shimmer effects, Carousel slider, HTML rendering, Custom toasts.

## 🚀 Getting Started

### Prerequisites
*   [Flutter SDK](https://flutter.dev/docs/get-started/install) (version 3.6.2 or higher)
*   Android Studio / VS Code with Flutter extensions
*   CocoaPods (for iOS)

### Installation

1.  **Clone the repository**
    ```bash
    git clone <repository-url>
    cd LebanonShopUserapp
    ```

2.  **Install dependencies**
    ```bash
    flutter pub get
    ```

3.  **Setup Firebase**
    *   Add your `google-services.json` (Android) and `GoogleService-Info.plist` (iOS) to the respective directories.
    *   Update the `main.dart` file with your Firebase configuration if necessary.

4.  **Run the application**
    ```bash
    flutter run
    ```

## 📂 Project Structure

The project follows a clean, feature-driven directory structure:

*   `lib/data`: Data sources (API clients, local storage).
*   `lib/features`: Contains all feature modules (Auth, Cart, Order, etc.). Each feature typically includes:
    *   `controllers`: State management logic.
    *   `domain`: Models and repositories.
    *   `screens` / `widgets`: UI components.
*   `lib/helper`: Utility classes and constants.
*   `lib/localization`: Localization strings and logic.
*   `lib/theme`: App theme definitions (Light/Dark).
*   `lib/utill`: General utilities (Images, Dimensions, ColorResources).

## 📄 License
[Include License Information Here]
