# FarmFusion360-v2.5

FarmFusion360 is a comprehensive farm management system designed to help farmers and agricultural businesses efficiently manage their operations. This system provides tools for tracking debts, expenses, sales, harvests, and generating reports to facilitate better decision-making and financial management.

## Features

- User authentication and management (login, register, forgot password)
- Dashboard overview of farm activities and financial status
- Management of debts and expenses
- Sales and harvest tracking
- Exportable reports for financial and operational analysis
- Settings customization
- Backup and restore functionality
- Currency exchange rate caching for financial calculations

## Technologies Used

- PHP for server-side scripting
- MySQL for database management (SQL schema and database files included)
- HTML, CSS, and JavaScript for frontend interface
- Composer for PHP dependency management

## Installation

1. Clone or download the repository to your local server environment (e.g., XAMPP).
2. Import the database schema and data using the provided SQL files:
   - `farmfusion360_db.sql`
3. Configure your database connection in `config.php`.
4. Install PHP dependencies using Composer:
   ```
   composer install
   ```
5. Ensure the `cache/` and `backup/` directories are writable by the web server.
6. Start your local server and navigate to the application (e.g., `http://localhost/farmfusion360/dashboard.php`).

## Usage

- Access the system via the login page.
- Use the dashboard to get an overview of your farm's financial and operational status.
- Manage debts, expenses, sales, and harvests through their respective modules.
- Generate and export reports for analysis.
- Adjust settings as needed for your farm's specific requirements.

## Backup and Cache

- The system maintains backups in the `backup/` directory.
- Currency exchange rates are cached in the `cache/` directory to optimize performance.

## Contributing

Contributions are welcome. Please fork the repository and submit pull requests for any enhancements or bug fixes.




