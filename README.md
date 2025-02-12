
```markdown
# React Google Calendar Integration

A simple React component to fetch and display events from **Google Calendar**.

## 🚀 Features
- Fetches public events from a Google Calendar.
- Displays events in a clean and customizable UI.
- Supports authentication for private calendars.
- Lightweight and easy to integrate.

## 📦 Installation

```sh
yarn add react-google-calendar
```

or using npm:

```sh
npm install react-google-calendar
```

## 🔧 Setup

1. **Enable Google Calendar API**
   - Go to the [Google Cloud Console](https://console.cloud.google.com/).
   - Create a new project or select an existing one.
   - Enable the **Google Calendar API**.
   - Create OAuth 2.0 credentials and get your **Client ID** and **API Key**.

2. **Set up OAuth consent**
   - Configure the OAuth screen for your application.
   - Add `http://localhost:3000` (or your deployment URL) to **Authorized JavaScript origins**.

3. **Add API Keys to `.env`**
   - Create a `.env` file in your project root:

   ```sh
   REACT_APP_GOOGLE_API_KEY=your_api_key
   REACT_APP_GOOGLE_CLIENT_ID=your_client_id
   ```

## ScreenShoot 
link: https://google-calendar-clone.netlify.app/
![image](https://github.com/user-attachments/assets/9ea6e289-a0ff-433a-bcc0-a1baf7dd2192)
![image](https://github.com/user-attachments/assets/927ecbe7-9940-4fc2-8231-7b21c43018f4)
![image](https://github.com/user-attachments/assets/50390f05-a497-4529-a1a5-efebf140c62a)





## 🎨 Customization
- Modify the UI to fit your design.
- Fetch events from a specific calendar using `calendarId: "your_calendar_id"`.
- Customize event filtering and sorting.

## ⚡️ Contributing
Contributions are welcome! Feel free to submit issues and pull requests.

## 📄 License
This project is licensed under the **MIT License**.

---

Happy coding! 🎉
```

This README covers:
- Installation using **Yarn**  
- Setting up Google Calendar API  
- Authentication and fetching events  
- A working **React example**  
- Customization options  

Let me know if you need any modifications! 🚀
