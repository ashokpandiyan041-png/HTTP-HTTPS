# HTTP-HTTPS
# 🌐 Web Communication Protocols Documentation

A simple documentation project that explains the fundamentals of **HTTP** and **HTTPS**, their features, security benefits, differences, and commonly used HTTP request methods.

## 📖 Overview

HTTP and HTTPS are communication protocols used to exchange data between a client (browser) and a server. While HTTP transfers data in plain text, HTTPS secures communication using SSL/TLS encryption.



## 🌐 What is HTTP?

**HTTP (HyperText Transfer Protocol)** is a protocol used for communication between a web browser and a web server.

### Features

- Client-server architecture
- Request-response communication model
- Stateless protocol
- Supports data transfer over the web
- Platform independent
- Lightweight and fast communication

### Why HTTP is Used

- Establishes communication between client and server
- Transfers web resources such as HTML pages, images, and files
- Enables data exchange in web applications

### Common Use Cases

- Accessing websites
- Downloading files
- Calling APIs
- Submitting forms

### Limitation

HTTP transfers data in plain text, making it vulnerable to security threats and data interception.



## 🔒 What is HTTPS?

**HTTPS (HyperText Transfer Protocol Secure)** is the secure version of HTTP. It uses SSL/TLS encryption to protect data during transmission.

### Features

- Data encryption
- Secure communication
- Website authentication
- Data integrity protection
- Enhanced privacy and security
- Better SEO ranking

### Why HTTPS is Used

- Secures user data
- Prevents unauthorized access
- Verifies website authenticity
- Improves trust and website security

### Common Use Cases

- Online banking
- E-commerce websites
- Login systems
- Payment gateways
- Secure web applications

### Advantage

HTTPS encrypts data, ensuring secure and reliable communication.



## ⚖️ HTTP vs HTTPS

| Feature | HTTP | HTTPS |
|----------|----------|----------|
| Security | ❌ Not Secure | ✅ Secure |
| Encryption | ❌ No | ✅ SSL/TLS |
| Data Transfer | Plain Text | Encrypted Data |
| Port Number | 80 | 443 |
| Authentication | ❌ No | ✅ Yes |
| SEO Ranking | Lower | Higher |
| Browser Indicator | Not Secure | 🔒 Secure |

---

## 📡 HTTP Request Methods

### GET

Retrieves data from the server.

```http
GET /users
```

**Use Case:** Fetching user information.

### POST

Creates a new resource on the server.

```http
POST /users
```

**Use Case:** User registration or form submission.

### PUT

Updates an existing resource completely.

```http
PUT /users/1
```

**Use Case:** Updating a user profile.

### PATCH

Updates specific fields of an existing resource.

```http
PATCH /users/1
```

**Use Case:** Updating an email or phone number.

### DELETE

Removes a resource from the server.

```http
DELETE /users/1
```

**Use Case:** Deleting a user account.

### HEAD

Retrieves only response headers without the response body.

```http
HEAD /users
```

**Use Case:** Checking resource availability.

### OPTIONS

Retrieves the supported HTTP methods for a resource.

```http
OPTIONS /users
```

**Use Case:** Discovering available API operationS


## 🎯 Learning Outcomes

After exploring this repository, you will be able to:

- Understand HTTP and HTTPS fundamentals.
- Compare HTTP and HTTPS security features.
- Learn how secure web communication works.
- Understand common HTTP request methods.
- Apply best practices for secure web applications.



## 🛠️ Technologies Covered

- HTTP
- HTTPS
- SSL/TLS
- REST APIs
- Web Communication Protocols



## 🔗 Connect With Me

- LinkedIn: [Pandiyan R](https://www.linkedin.com/in/pandiyan-r/)



## 📄 License

This project is available for educational and learning purposes.
