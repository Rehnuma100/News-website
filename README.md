# News Website Project

## Description
This project is a dynamic News Website that fetches and displays real-time news articles using the NewsAPI. Users can search for news, browse through different categories, and click on articles to read the full content on the original source.

## Features
- Fetches news dynamically from NewsAPI
- Category-based navigation (IPL, Finance, Politics)
- Search functionality for specific news topics
- Responsive and modern UI
- Clickable news cards to view full articles
- Reload button to refresh the news feed

## Technologies Used
- HTML, CSS (Bootstrap, custom styles)
- JavaScript (Fetch API, DOM Manipulation)
- NewsAPI (for fetching real-time news data)

## File Structure
```
/ (root)
│── index.html  # Main HTML structure
│── style.css   # Styles for the website
│── script.js   # JavaScript for fetching and displaying news
│── logo.png    # Website logo
```

## Setup and Usage
### Prerequisites
- A browser (Chrome, Firefox, Edge, etc.)
- Internet connection (to fetch news from API)

### Steps to Run
1. Download or clone the project.
2. Open `index.html` in a browser.
3. Browse news categories or search for specific news topics.
4. Click on a news card to read the full article.

## API Integration
This project uses the **NewsAPI** to fetch news. The API key is stored in `script.js`:
```js
const API_KEY = "fe6359533d1c4e67a66cfe5e961d8015";
const url = "https://newsapi.org/v2/everything?q=";
```
### Changing API Key
If you want to use your own API key, replace the existing key in `script.js`:
```js
const API_KEY = "your_api_key_here";
```

## Future Improvements
- Add pagination for more news articles
- Improve UI with better styling and animations
- Add user authentication for personalized news feeds
- Enable dark mode for better readability

## License
This project is open-source and free to use.

