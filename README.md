 🚗 Car Rental Management System

A web-based Car Rental Management System developed using ASP.NET Web Forms and C#

📌 About the Project

This project is designed to manage car rental operations through a web application.

Users can browse available cars and perform car rental-related operations through the website.

 🛠️ Technologies Used

* ASP.NET Web Forms
* C#
* .NET Framework
* HTML
* CSS
* JavaScript
* SQL Server
* Visual Studio

 ✨ Features

* User-friendly car rental website
* Car information and availability
* Car rental management
* User-related pages
* Database connectivity
* Web-based interface
* ASP.NET Web Forms with C# code-behind

#📂 Project Structure


car_rental/
│
├── Account/
├── App_Data/
├── Scripts/
├── Styles/
├── image/
├── videos/
├── bin/                 # Ignored by Git
├── obj/                 # Ignored by Git
│
├── *.aspx               # Web Forms pages
├── *.aspx.cs            # C# code-behind files
├── *.aspx.designer.cs   # Designer files
├── Web.config
├── Global.asax
├── car_rental.csproj
└── README.md


 🗄️ Database

The project uses SQL Server for database connectivity.

Before running the project, configure the database connection in `Web.config` according to your local SQL Server setup.

Example:


<connectionStrings>
    <add name="car_rentalDBConnection"
         connectionString="YOUR_CONNECTION_STRING"
         providerName="System.Data.SqlClient" />
</connectionStrings>


> Replace the connection string with your own local database configuration.

 ▶️ How to Run

1. Clone the repository:


git clone https://github.com/anupatil804/car-rental.git


2. Open the project in Visual Studio.

3. Open the `car_rental.sln` or project file if available.

4. Configure the SQL Server database connection in `Web.config`.

5. Build the project.

6. Run the project using IIS Expressor the configured ASP.NET development server.

 Requirements

Before running the project, install:

* Visual Studio
* ASP.NET / .NET Framework development tools
* SQL Server
* SQL Server Management Studio (SSMS)

 Author

Anushka Patil

GitHub:
https://github.com/anupatil804

 📄 License

This project is created for learning and development purposes.
