
# Airline Reservation System - Java Swing Application

This is a desktop-based **Airline Reservation System** application built using **Java Swing** for GUI and **NetBeans IDE** project structure.

## Features

- ✈️ User login and authentication
- 🛫 Add new flights
- 👥 Add and search for customers
- 🎟️ Ticket booking and ticket reporting
- 👤 User account creation
- 🖥️ Java Swing Forms based User Interface

## Tech Stack

- **Language:** Java
- **GUI Framework:** Java Swing
- **IDE:** NetBeans
- **Build Tool:** Ant (`build.xml`)
- **Project Management:** NetBeans `nbproject` structure

## Project Structure

```
build/
 └── classes/
      ├── addCustomer.class
      ├── addflight.class
      ├── Login.class
      ├── Main.class
      ├── searchCustomer.class
      ├── ticket.class
      ├── ticketreport.class
      ├── userCreation.class
      └── (associated .form and inner classes)

nbproject/
 ├── private/
 │    ├── config.properties
 │    ├── private.properties
 │    └── private.xml
 ├── build-impl.xml
 ├── genfiles.properties
 ├── project.properties
 └── project.xml

src/
 ├── addCustomer.java
 ├── addflight.java
 ├── Login.java
 ├── Main.java
 ├── searchCustomer.java
 ├── ticket.java
 ├── ticketreport.java
 ├── userCreation.java
 └── (associated .form files)

build.xml
manifest.mf
```

## How to Run

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/airline-reservation-system.git
   ```

2. **Open in NetBeans IDE.**

3. **Build the project** using `build.xml` (Ant build script) or directly from NetBeans.

4. **Run the project** from NetBeans or by executing the compiled classes.


## Folder Highlights

- `src/` — Main Java source files and GUI Form files.
- `build/` — Compiled `.class` files for execution.
- `nbproject/` — NetBeans specific project files and private configs.

## Future Enhancements

- 📄 Add database integration for persistent flight and ticket data
- 🔒 Improve user authentication with password encryption
- 📊 Generate advanced reporting features

## License

This project is licensed under the [MIT License](LICENSE).
