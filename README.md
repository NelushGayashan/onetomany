# Hibernate One-to-One and One-to-Many Mapping Example

This project demonstrates Hibernate annotations for one-to-one and one-to-many mappings between `Question` and `Answer` entities.

## Technologies Used

- Hibernate
- H2 Database (for example purposes)
- JUnit (for testing)

## Project Structure
````
SpringHibernateMappingExample
├── src
│ ├── main
│ │ └── java
│ │ └── com
│ │ └── javatpoint
│ │ ├── model
│ │ ├── repository
│ │ ├── service
│ │ └── SpringHibernateMappingExampleApplication.java
│ └── test
│ └── java
│ └── com
│ └── javatpoint
│ └── SpringHibernateMappingExampleApplicationTests.java
└── README.md
````


## Setup Instructions

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-repository-url.git
   cd SpringHibernateMappingExample
    ````
2.  **Configure database:**
        Open hibernate.cfg.xml and configure the database properties.

3.  **Add dependencies to pom.xml:**
        Add Hibernate and H2 Database dependencies.

## Usage

    Populate the database with sample data using StoreData.java.
    Retrieve and display data using FetchData.java.

## Contributing

Contributions are welcome! Fork the repository and submit a pull request.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

