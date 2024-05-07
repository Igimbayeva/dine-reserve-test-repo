**Dine Reserve **
**Description**
This project consisted on developing a reservation system to book a dining spot in restaurants. The goal was design and develop a full-stack restaurant booking application using node.js, express back end and post routes, MySQL, handlebars.![restaurant software](https://github.com/Igimbayeva/dine-reserve-test-repo/assets/139830276/9c5d5fda-3381-4819-9e77-830d52f0b85e)

**Technologies**
• SQL
• Javascript 
• Express
• Handlebar

**Application Structure**
dine-reserve/          # Main project folder
│
├── config/            # Configuration files
│   ├── connection.js  # Database connection configuration
│   └── environment.js # Environment configuration
│
├── db/                # Database related files
│   └── schema.sql     # Database schema definition
│
├── models/            # Sequelize models
│   ├── index.js       # Model index file
│   ├── Post.js        # Post model
│   ├── Reservations.js# Reservations model
│   ├── Restaurants.js # Restaurants model
│   └── User.js        # User model
│
├── public/            # Static assets
│   ├── assets/        # JavaScript files
│   │   └── ...        # Other JavaScript files
│   ├── css/           # CSS stylesheets
│   │   └── ...        # CSS files
│   ├── img/           # Image files
│   └── ...
│
├── routes/            # Express.js routes
│   ├── index.js       # Main router
│   ├── users.js       # User-related routes
│   ├── restaurants.js # Restaurant-related routes
│   └── ...
│
├── seeds/             # Database seed files
│   ├── restaurant-seeds.js # Seed file for restaurants
│   ├── user-seeds.js      # Seed file for users
│   └── ...
│
├── views/             # Handlebars.js templates
│   ├── layouts/       # Layout templates
│   │   └── main.handlebars    # Main layout template
│   ├── homepage.handlebars    # Homepage template
│   ├── login.handlebars       # Login template
│   ├── reservations.handlebars # Reservations template
│   └── restaurants.handlebars  # Restaurants template
│
├── controllers/       # Controller files
│   └── userController.js    # User controller
│
├── .env.example       # Example environment variables
├── .gitignore         # Git ignore file
├── LICENSE            # Project license
├── package.json       # Project dependencies and scripts
├── package-lock.json  # Lock file for dependency versions
├── server.js          # Main server file
└── README.md          # Project README file

Link Deployment 


License 
MIT License

Credits
The group integrated by Justin Boston, Ana Kamran, Dinara Igimbayeva, Ummul Mukta, Zully Paz
