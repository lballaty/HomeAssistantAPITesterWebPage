Here is the Markdown file you can use as a `README.md` for your GitHub repository:

```markdown
# Home Assistant API Tester

A web application designed for interacting with Home Assistant's APIs. The app allows you to configure, send requests, and visualize responses while managing API-related tasks such as fetching entities and relationships.

---

## Features

- **API Request Builder**
  - Configure API requests by selecting protocol, IP address, port, and endpoint.
  - Supports HTTP methods: `GET`, `POST`, `PUT`, and `DELETE`.
  - Optional JSON payload input for supported methods.

- **Token Management**
  - Input and manage long-lived access tokens.
  - Toggle visibility of tokens for ease of use.

- **Entity Management**
  - Fetch available entities from the `/api/states` endpoint.
  - Filter and select entities dynamically.
  - Auto-populate payloads for entity-specific requests.

- **Response Viewer**
  - View API responses in a formatted block.
  - Copy request and response details to the clipboard.

- **Theme and Settings Persistence**
  - Toggle between light and dark modes.
  - Save preferences (e.g., protocol, IP, port) to `localStorage`.

- **Entity-Device Relationship Explorer**
  - Fetch relationships between entities and devices using a specific API endpoint.

- **Help and Documentation**
  - Tooltip-based guidance on API fields (e.g., endpoints, methods, payloads).

---

## Getting Started

### Prerequisites

Ensure you have access to a Home Assistant instance and a valid long-lived access token.

### Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/home-assistant-api-tester.git
   ```
2. Navigate to the project directory:
   ```bash
   cd home-assistant-api-tester
   ```
3. Serve the `index.html` file using a local web server or host it on your preferred platform.

---

## Usage

### Configure API Request
1. **Protocol**: Select `http` or `https`.
2. **IP Address**: Enter the IP of your Home Assistant instance (e.g., `192.168.1.100`).
3. **Port**: Enter the port number (e.g., `8123`).
4. **Endpoint**: Choose a predefined endpoint or enter a custom endpoint.

### Send Request
- Select the HTTP method (`GET`, `POST`, `PUT`, `DELETE`).
- Optionally, enter a JSON payload.
- Click "Send Request" to execute.

### Fetch Entities
- Click "Fetch Entities" to retrieve the list of available entities.
- Use the search box to filter entities.
- Click on an entity to populate the payload.

### Explore Relationships
- Click "Fetch Relationships" to retrieve entity-device relationships.

### Response Handling
- View formatted responses in the "Response" section.
- Copy request/response details using the "Copy" buttons.

---

## Advanced Features

### Theme Toggle
- Click "Toggle Theme" to switch between light and dark modes.

### Settings Persistence
- Preferences (e.g., protocol, token, IP) are saved to `localStorage`.

### Help Modal
- Click the "?" next to fields to get guidance on their usage.

---

## Troubleshooting

- **Invalid Token**: Ensure you have entered a valid long-lived access token.
- **CORS Errors**: Configure your Home Assistant instance to allow cross-origin requests.
- **Connection Issues**: Verify the IP, port, and protocol match your Home Assistant instance.

---

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your changes.

---

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.
```

You can customize the sections as needed (e.g., replace `your-username` with your GitHub username). Let me know if you'd like additional tweaks!
