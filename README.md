# PLAYBITE

## Description
PLAYBITE is a full-featured food ordering web application built using the MERN stack (MongoDB, Express.js, React.js, Node.js). It enables users to browse restaurant menus, place orders, make payments, and track their orders in real time. The platform is designed for both customers and restaurant owners, providing a seamless and efficient food ordering experience.

## Features
- User authentication and registration
- Menu browsing and search
- Add items to cart
- Order placement and management
- Payment integration (placeholder)
- Real-time order tracking
- User profile management
- Admin dashboard for restaurant management
- Responsive design for mobile and desktop

## Technologies Used
- **Frontend:** React.js, Redux, CSS3
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Authentication:** JWT
- **Other:** Axios, Mongoose

## Installation

### Prerequisites
- Node.js & npm
- MongoDB (local or cloud)

### Clone the Repository
```bash
git clone https://github.com/ManasJ17/PLAYBITE.git
cd PLAYBITE
```

### Install Dependencies
#### Backend
```bash
cd server
npm install
```
#### Frontend
```bash
cd client
npm install
```

### Environment Variables
Create a `.env` file in the `server` directory and add your MongoDB URI and other secrets:
```env
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
```

### Run the Application
#### Start Backend
```bash
cd server
npm start
```
#### Start Frontend
```bash
cd client
npm start
```

## Usage
1. Register or log in as a user or admin.
2. Browse restaurants and select food items.
3. Add items to your cart and proceed to checkout.
4. Make payment (integration placeholder).
5. Track your order status in real-time.
6. Manage your profile and view order history.

## Screenshots
> _Screenshots will be added soon._
> ![Home Page](screenshots/homepage.png)
> ![Order Tracking](screenshots/order-tracking.png)

## Contributing
Contributions are welcome! To contribute:
- Fork the repository
- Create a new branch (`git checkout -b feature/your-feature`)
- Commit your changes (`git commit -m 'Add new feature'`)
- Push to the branch (`git push origin feature/your-feature`)
- Open a Pull Request

Please follow the project's code style and guidelines.

## License
This project is licensed under the [MIT License](LICENSE).

## Contact
- **Author:** Manas Joshi
- **GitHub:** [ManasJ17](https://github.com/ManasJ17)
- **Email:** manasjoshi@example.com
