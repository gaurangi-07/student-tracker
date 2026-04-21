# EduPulse | Student Engagement Analysis Dashboard

EduPulse is a modern, data-driven dashboard designed to track and analyze student engagement in academic settings. By aggregating participation scores, quiz performance, and sentiment analysis, it provides educators with actionable insights to identify at-risk students and improve learning outcomes.

## 🚀 Features

- **Dynamic Analytics**: Real-time KPI tracking for average engagement, total students, and at-risk alerts.
- **Visual Insights**: Automated data visualization using Chart.js, including:
  - Engagement distribution (High/Medium/Low)
  - Participation vs. Quiz performance scatter analysis
  - Sentiment breakdown from student feedback
- **Student Roster Management**: Search, filter, and track individual student performance metrics.
- **At-Risk Detection**: Rule-based alert system flags students with critically low scores or declining trends.
- **Data Export**: One-click CSV export for offline analysis and reporting.
- **Responsive Design**: Glassmorphism-inspired UI that works seamlessly across desktop and mobile.

## 🛠️ Tech Stack

- **Frontend**: HTML5, Vanilla JavaScript (ES6+), CSS3
- **Data Visualization**: Chart.js
- **Icons**: Lucide Icons
- **Typography**: Inter & Outfit (Google Fonts)
- **Deployment Ready**: Static structure optimized for GitHub Pages or Vite.

## 📊 Scoring Formula

The system uses a weighted model to calculate the overall Engagement Score:
- **Participation**: 40%
- **Quiz Performance**: 40%
- **Sentiment Analysis**: 20%

`Score = (Participation × 0.4) + (Quiz × 0.4) + (Sentiment × 0.2)`

## 🚦 Status Categories

- **High Engagement**: ≥ 75%
- **Medium Engagement**: 50% - 74%
- **Low Engagement**: < 50%

## 🏁 Getting Started

1. Clone the repository.
2. Open `index.html` in your browser OR run `npm run dev` to start the development server.
3. Explore the dashboard or add new student data via the sidebar.
