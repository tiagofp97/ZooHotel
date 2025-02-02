Veterinary Hotel Management Application
This project implements a Veterinary Hotel Management Application as part of the Object-Oriented Programming coursework. The system is designed to manage a veterinary hotel with entities such as animals, caretakers, veterinarians, habitats, and trees, providing functionality for animal satisfaction tracking, habitat management, employee satisfaction, and vaccination tracking.

Project Overview
The application offers the following key functionalities:

Animal Management: Registration, satisfaction calculation, and habitat transfers.
Employee Management: Registration, responsibility assignment, satisfaction calculation, and management of caretakers and veterinarians.
Habitat Management: Registration, area management, habitat influence on species, tree planting, and habitat satisfaction impact.
Vaccination Tracking: Registration of vaccines, administration of vaccinations with health tracking, and identification of vaccination errors.
Seasonal Cycle Progression: Adjusts habitat characteristics based on seasonal changes impacting tree and animal conditions.
Data Persistence: Allows state saving and loading for the entire application session.
Application Structure
This project follows a layered architecture:

Domain Layer (package hva.core): Manages the core entities and business logic.
Application Layer (package hva.app): Handles user interactions through a menu-driven interface provided by the po-uilib framework.
Features
Animal Management
Register Animal: Add new animals and associate them with species and habitats.
View Animals: List all animals with their details and health history.
Calculate Satisfaction: Compute the satisfaction of animals based on habitat conditions and species compatibility.
Employee Management
Register Employee: Add new caretakers and veterinarians.
Assign Responsibilities: Manage caretakers' habitats and veterinarians' authorized species.
Calculate Satisfaction: Measure employee satisfaction based on workload and species management.
Habitat Management
Manage Habitat Properties: Register new habitats, update area, and set species-specific influences.
Plant Trees: Add trees to habitats and manage tree conditions affected by seasonal cycles.
Vaccination Management
Register Vaccine: Define vaccines and their compatible species.
Administer Vaccinations: Track vaccinations with health impact assessment on animals.
User Interface
Interactive Menus: A menu-based interface allows easy navigation and command execution for managing entities.
