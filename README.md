# Freshman Simulator - High School Journey

An interactive web application that simulates a student's high school journey from freshman to senior year. Build a balanced path to college by managing GPA, resume, and health through course selection, extracurricular activities, and life events.

## Features

- **Step-by-step semester planning**: Select core classes, electives, and clubs
- **Event simulation**: Experience random events that affect your stats
- **Health tracking**: Monitor GPA, resume, sleep, mental health, and social health
- **Badge system**: Earn achievements based on your performance
- **Personalized advice**: Get tailored suggestions based on your goals

## Deployment on Railway

This app is configured for easy deployment on Railway:

1. Connect your GitHub repository to Railway
2. Railway will automatically detect the Node.js project
3. The app will start using the command defined in `package.json`
4. Your app will be available at the Railway-provided URL

### Environment Variables

- `PORT`: Automatically set by Railway (defaults to 3000 locally)

### Local Development

```bash
# Install dependencies
npm install

# Start the server
npm start

# Visit http://localhost:3000
```

## Tech Stack

- **Frontend**: HTML, CSS (Tailwind CDN), Vanilla JavaScript
- **Backend**: Node.js with Express
- **Deployment**: Railway

## Customization

- Add your logo to `/static/images/Logo_Black.png` (currently commented out in HTML)
- Modify game parameters in the HTML file's JavaScript section
- Adjust styling in the embedded CSS

## License

MIT
