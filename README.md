# NewsBite - News App

NewsBite is a web application that delivers concise news summaries in 60 words or less, inspired by apps like Inshorts. Get your daily dose of news in a quick, easy-to-digest format.

## Features
- Short news summaries
- Multiple news categories (Business, Technology, Sports, Entertainment, etc.)
- Real-time news updates
- Lazy Loading (Infinite Scroll)
- Dark/Light theme support
- Bookmark favorite news articles
- Share news via social media
- Offline reading capability

## Screenshots
![Demo Image 2](demo_images/inshorts-demo-1.jpg)
![Demo Image 2](demo_images/inshorts-demo-2.jpg)


## Installation
Follow these steps to set up NewsBite locally:

1. Clone the repository:
```bash
git clone https://github.com/anirudh9260/NewsBite-React.git

```

2. Install dependencies:
```bash
cd NewsBite-React
npm install
```

3. Create a .env file in the root directory (Get a new api key from newsapi.org and paste it here):
```bash
REACT_APP_NEWS_API=your_api_key_here
```

4. Run the app:
```bash
npm start
```

## Project Structure
```bash
NewsBite/
├── src/
│   ├── components/    # Reusable UI components
│   ├── services/      # API calls and business logic
│   ├── redux/         # State management
│   └── assets/        # Images, fonts, etc.
├── backend/           # Server-side code
├── images/            # Demo images
└── docs/             # Documentatio
```


## Roadmap
- Add user authentication
- Implement personalized news recommendations
- Add multiple language support
- Integrate breaking news alerts
- Add voice reading feature

## License
This project is licensed under the MIT License - see the  file for details.

## Contact
For any queries, reach out to:
Email: anirudh.88@live.in