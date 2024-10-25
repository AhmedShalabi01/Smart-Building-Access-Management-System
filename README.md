# Smart Building Access Management System using Digital Keys

#### Collaborators: [Ahmed Salah Shalabi](https://github.com/AhmedShalabi01) and [Jalal Assaly](https://github.com/Jalal-Assaly)

## Project Overview
This project, titled **Smart Building Access Management System using Digital Keys**, was developed as my graduation project at the **Faculty of Engineering, Computer Systems Department**. It focuses on enhancing building security and access control using digital key technology, ensuring that only authorized individuals have entry to restricted areas.

This repository contains subsystems of the IoT physical access control system. Programmed using Java 17, Spring Boot, and MongoDB for the backend and mobile application. Furthemore, the Embeded system was developed using C, C++. Finally, the frontend was developed using HTML, CSS, TypeScript and Angular Framework. 

## Illustrative Video
[Watch the video](https://drive.google.com/file/d/1fbGVf5QVrfla25-C9wlf16yCCj4XdmEq/view?usp=sharing)

# Backend Microservices

### [User Credentials API](https://github.com/Jalal-Assaly/user-credentials-api)
This microservice handles user credentials management service with basic CRUD operations. It provides endpoints for managing user credentials securely.

### [Company Data Gateway API](https://github.com/Jalal-Assaly/company-data-gateway-api)
The Company Data Gateway API serves as an interface for accessing and managing company-specific data within the physical access control system.

### [Visitor Management API](https://github.com/Jalal-Assaly/visitor-management-api)
This microservice performs and facilitates the management of visitors, including registration, check-in, and check-out functionalities.

### [Attributes Management API](https://github.com/AhmedShalabi01/attributes-management-api)
The Attributes Management API allows the management of various attributes associated with users and access points within the system.

### [User Login Registration API](https://github.com/AhmedShalabi01/user-login-registration-api)
This microservice handles user registration and login processes, providing endpoints for user account management.

### [Access Policy Management API](https://github.com/AhmedShalabi01/access-policy-management-api)
The Access Policy Management API is responsible for defining, managing and enforcing access control policies within the system.

### [CoAP Server API](https://github.com/Jalal-Assaly/coap-server-api)
This microservice implements a CoAP server using the Californium(Cf) library, providing an interface for communication with CoAP-enabled devices.

### [CoAP Client API](https://github.com/Jalal-Assaly/coap-client-emulator)
The CoAP Client Emulator allows communication with CoAP servers from within the system. Used to test the CoAP implementation of the CoAP server API.

### [Access Control API](https://github.com/Jalal-Assaly/access-control-api)
This microservice implements the core access control functionalities, including granting or denying access based on predefined access policies.

### [Admin Server API](https://github.com/Jalal-Assaly/admin-server-api)
The Admin Server API provides administrative functionalities for managing and monitoring the backend system performance. Uses Codecentric's Spring Admin Server dependency based upon Spring Actuator to reveal information endpoints such as the system's health, metrics, http traces and more.



# Mobile Application
### [PACS Mobile Application](https://github.com/AhmedShalabi01/pacs-mobile-application)
This application handles user login and registration processes, and manages access to the location by exchanging a digital key with the access point microcontroller using NFC technology.



# Embedded System
### [PACS Embedded System](https://github.com/Jalal-Assaly/pacs-embedded-client)
The embedded system is responsible for controlling the ESP32 microcontroller to interface with the NFC reader and various other components.



# FrontEnd 
### [FrontEnd System](https://github.com/Jalal-Assaly/pacs-ui.git)
The frontend is used for system management, monitoring, and logging.
