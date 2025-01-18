# Mark2Notion

Mark2Notion is a browser extension and web app that allows users to seamlessly save bookmarks directly to their Notion workspace. With an intuitive interface and powerful integration with the Notion API, it simplifies organizing and managing links, ensuring everything is stored in one place.

## Features

- **Save Bookmarks Instantly:** Capture URLs, titles, and descriptions with a single click.
- **Custom Tags and Notes:** Add tags and notes to bookmarks for easy organization.
- **Notion Integration:** Directly save bookmarks to a specific Notion database.
- **Cross-Browser Support:** Available as a browser extension for Chrome, Firefox, and more.
- **Responsive Web App:** Access the bookmarking tool on any device via a modern web app.
- **Secure OAuth Authentication:** Connect and authenticate securely with Notion.

## Tech Stack

### Frontend
- **React.js:** For building the user interface.
- **HTML5 & CSS3:** To structure and style the application.
- **JavaScript:** Core logic and browser extension functionality.

### Backend
- **Node.js:** Backend server to handle API requests and user authentication.
- **Express.js:** Framework for routing and server logic.
- **Notion API:** To interact with the Notion workspace for saving bookmarks.

### Additional Tools and Platforms
- **Browser APIs:** To capture and process active tab data for browser extensions.
- **OAuth 2.0:** For secure user authentication with Notion.
- **Firebase or MongoDB (Optional):** To store user preferences and settings (if required).
- **Netlify/Vercel:** For deploying the frontend application.
- **Heroku/AWS:** For backend hosting (optional).

## Installation

### Browser Extension
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/mark2notion.git
   ```
2. Navigate to the `extension` folder:
   ```bash
   cd mark2notion/extension
   ```
3. Load the extension in your browser:
   - For Chrome: Go to `chrome://extensions`, enable developer mode, and load the unpacked folder.
   - For Firefox: Go to `about:debugging`, click "This Firefox," and load the temporary add-on.

### Web App
1. Install dependencies:
   ```bash
   cd mark2notion/web
   npm install
   ```
2. Start the development server:
   ```bash
   npm start
   ```
3. Open your browser and navigate to:
   ```
   http://localhost:3000
   ```

### Backend
1. Install dependencies:
   ```bash
   cd mark2notion/backend
   npm install
   ```
2. Add your Notion integration token and database ID to the `.env` file:
   ```env
   NOTION_TOKEN=your_notion_token
   NOTION_DATABASE_ID=your_database_id
   ```
3. Start the server:
   ```bash
   npm start
   ```

## Usage

1. **Connect Your Notion Account:**
   - Use the OAuth authentication flow to connect Mark2Notion to your Notion workspace.
   
2. **Add Bookmarks:**
   - Use the browser extension or web app to save URLs, titles, and tags to your Notion database.
   
3. **Manage Your Bookmarks:**
   - View and organize bookmarks directly within your Notion workspace.

## Project Structure

```
mark2notion/
├── backend/           # Backend server code
├── web/               # Frontend React.js code
├── extension/         # Browser extension code
├── README.md          # Project documentation
├── .env.example       # Sample environment variables
└── package.json       # Dependency management
```

## Future Enhancements

- **Bookmark Analytics:** Visualize frequently visited or most saved bookmarks.
- **Multi-User Support:** Allow multiple accounts to manage bookmarks independently.
- **Customizable Templates:** Provide options to customize how bookmarks are saved in Notion.
- **Search and Filter:** Add powerful search and filtering features for quick access.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your changes. Ensure code quality and add documentation for new features.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any questions or support, feel free to contact:
- **Email:** your.email@example.com
- **GitHub:** [yourusername](https://github.com/yourusername)
- **Website:** [yourwebsite.com](https://yourwebsite.com)
