# Instagrammy

![Instagram Clone](path_to_screenshot.png)  <!-- Replace with a screenshot of your project -->

## Introduction

This is an ongoing project to create an Instagram clone using Laravel Livewire, Alpine.js, and Tailwind CSS. The project aims to replicate the look and feel of Instagram's web interface, including features such as stories, reels, liking videos/photos, following users, and more. Currently, the project is 30% complete.

## Features

- User authentication using Laravel Breeze
- Responsive design using Tailwind CSS
- Interactive components with Alpine.js
- Real-time updates with Laravel Livewire

## Planned Features

- User profiles
- Stories
- Reels
- Liking photos and videos
- Following and unfollowing users
- Comments and direct messages
- Notifications

## Tech Stack

- **Frontend**: Alpine.js, Tailwind CSS
- **Backend**: Laravel, Livewire
- **Authentication**: Laravel Breeze

## Installation

To set up this project locally, follow these steps:

1. **Clone the repository:**

    ```bash
    git clone https://github.com/FaithPhilemon/instagrammy.git
    cd instagram-clone
    ```

2. **Install dependencies:**

    ```bash
    composer install
    npm install
    ```

3. **Set up environment variables:**

    Copy the `.env.example` file to `.env` and configure your database and other settings.

    ```bash
    cp .env.example .env
    php artisan key:generate
    ```

4. **Run database migrations:**

    ```bash
    php artisan migrate
    ```

5. **Start the development server:**

    ```bash
    php artisan serve
    npm run dev
    ```

## Usage

Once the server is running, you can access the application at `http://localhost:8000`. Register for a new account or log in with existing credentials to start using the application.

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeature`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Open a Pull Request.

Please ensure that your code adheres to the existing coding conventions and includes appropriate tests.

## License

This project is open-source and available under the [MIT License](LICENSE).

## Contact

If you have any questions, feel free to reach out:

- **Email**: philemonfaith@gmail.com
- **Twitter**: [@philemonfaith](https://x.com/philemonfaith)
- **GitHub**: [faithphilemon](https://github.com/FaithPhilemon)

## Acknowledgements

- [Laravel](https://laravel.com/)
- [Livewire](https://laravel-livewire.com/)
- [Alpine.js](https://alpinejs.dev/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Laravel Breeze](https://laravel.com/docs/8.x/starter-kits#laravel-breeze)

---

*Note: This project is currently under development and is only 30% complete. Many features are yet to be implemented. Stay tuned for updates!*
