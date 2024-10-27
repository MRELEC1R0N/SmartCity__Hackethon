**CityWise: Your Smart Urban Companion**.

---

# CityWise: Your Smart Urban Companion

![CityWise Logo](link-to-logo-image-if-available)

**CityWise** is a comprehensive mobile application designed to improve urban living by providing real-time news, augmented reality (AR) navigation, mental health support, civic issue reporting, and live economic updates. This smart city companion is built in Kotlin and integrates multiple services to empower users with essential information and tools for modern city life.

---

## Inspiration

CityWise was inspired by the need for a centralized platform where city dwellers can easily access essential information and services. The app combines advanced technology with social impact to enhance the quality of urban life, promote civic engagement, and provide real-time support for mental health and navigation.

---

## Features

- **Live News Updates**: Get real-time news tailored to your city.
- **AR Navigation**: Use augmented reality to navigate the city with ease.
- **Mental Health Chatbot**: Access supportive resources through an empathetic chatbot.
- **Civil Issue Reporting**: Report local issues to authorities directly.
- **Economic Data Insights**: Stay informed with real-time GDP and economic metrics.

---

## Tech Stack

- **Frontend**: Kotlin (Jetpack Compose for UI)
- **Backend**: Node.js with Express, REST API
- **Database**: Firebase (cloud storage), Room Database (local storage)
- **APIs**:
  - [News API](https://newsapi.org/)
  - Government Data API for economic metrics
  - Google Maps API for location and navigation
- **Other Tools**: ARCore (for AR features), Redis (for caching), Firebase Analytics (for tracking)

---

## Architecture

The app follows a modular microservices architecture, with each service handling a specific functionality. Here's a high-level overview:

1. **Client (Frontend)**: Handles user interaction and AR rendering.
2. **Backend**: Manages API requests, user authentication, and microservices (news, chatbot, government data).
3. **Storage**: Includes a main database for user data and Redis for caching frequently accessed data.
4. **External Services**: Connects to external APIs for news, government data, and maps.

![System Architecture Diagram]
![image](https://github.com/user-attachments/assets/4213b7bb-93d2-4fa3-b256-d5f64609c627)

---

## Installation

To run CityWise locally, follow these steps:

### Prerequisites

- **Android Studio** for Kotlin development
- **Node.js** and **npm** for backend services
- API keys for [News API](https://newsapi.org/), [Google Maps API](https://cloud.google.com/maps-platform/), and government data sources

### Setup

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/CityWise.git
    cd CityWise
    ```

2. **Backend Setup**:
    - Navigate to the backend directory:
        ```bash
        cd backend
        ```
    - Install dependencies:
        ```bash
        npm install
        ```
    - Add your API keys in a `.env` file.
    - Start the backend server:
        ```bash
        npm start
        ```

3. **Android Client Setup**:
    - Open the project in Android Studio.
    - Add API keys for the necessary services in the `local.properties` file.
    - Build and run the app on an Android emulator or a physical device.

---

## Usage

After setting up, you can explore the following functionalities:

- **News**: View live news updates from your city.
- **AR Navigation**: Use AR mode to navigate through the city.
- **Chatbots**: Access mental health resources or report civic issues directly.
- **Economic Data**: Check the latest economic indicators provided by government APIs.

---

## Challenges

Some key challenges we encountered include:

- **API Integration**: Managing multiple APIs with varied response formats and rate limits.
- **AR Navigation Accuracy**: Ensuring accurate alignment in real-world settings.
- **Chatbot Development**: Designing empathetic responses for the mental health chatbot.

---

## What's Next

Future plans for CityWise include:

- **Enhanced Chatbot Capabilities**: Broaden the chatbot’s scope for more comprehensive support.
- **Public Transportation Data**: Add live transit schedules and information.
- **Emergency Alerts**: Integrate emergency notifications for critical updates.
- **Local Partnerships**: Collaborate with city authorities for more localized features.

---

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch:
    ```bash
    git checkout -b feature/YourFeatureName
    ```
3. Make your changes and commit them:
    ```bash
    git commit -m "Add YourFeatureName"
    ```
4. Push to the branch:
    ```bash
    git push origin feature/YourFeatureName
    ```
5. Create a pull request.

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.

---

## Contact

If you have any questions, please feel free to reach out at [contact@citywise.com](mailto:contact@citywise.com).
