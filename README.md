# EventEase

EventEase is a full-stack application designed to streamline the event planning process. It 
features a Next.js frontend and a Node.js backend, connecting users with vendors for various services. The system allows for event creation, package building, and handles bookings and payments through a commission-based model.
## ✨ Features

- **User Roles:** Differentiate between `USER` (event planners) and `VENDOR` roles.
- **Vendor Profiles:** Vendors can create detailed profiles including business name, category, location, pricing, and contact information.
- **Event Management:** Users can create and manage events, specifying the type, date, location, and budget.
- **Package Creation:** Users can build customized event packages by selecting multiple vendors.
- **Booking and Payments:** A robust system for handling vendor bookings and processing payments with a built-in commission structure.
- **AI-Powered Chat:** An integrated chat feature to provide users with event planning recommendations.

## 🚀 Getting Started

Follow these steps to set up and run the complete EventEase application locally.

### Prerequisites

- **Node.js**: The application's frontend (Next.js) and backend are built with Node.js.
- **Docker & Docker Compose**: Used to run the PostgreSQL database.

### Installation(local)

1. Download and install Docker on your pc
2. **Clone the repository:**
    
    ```
    git clone https://github.com/your-username/eventease.git
    cd eventease
    
    ```
    
3. **Start the PostgreSQL database:**
Create a `docker-compose.yml` file in the project's root and run the following command. The database will be available on `port 5432`.
    
    ```
    docker-compose up -d
    ```
    

## Contributing

Contributions are welcome! If you find a bug or have a suggestion, please open an issue or submit a pull request.

## 📄 License

This project is licensed under the MIT License.
