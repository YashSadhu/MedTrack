# MedTrack - Medication Adherence & Analytics Platform

MedTrack is a comprehensive medication management platform designed to help patients maintain complex medication schedules and track their adherence over time.

## 🎯 Features

### 1. Regimen Setup
- Add medications with detailed information (name, dose, frequency)
- Category-based labeling (supplements, prescription, OTC, etc.)
- Start/End date tracking
- Special instructions support

### 2. Dose Logging
- One-tap "Mark Taken" functionality
- 4-hour late logging window with warnings
- Reward system for consistent logging
- Detailed logging history

### 3. Smart Reminders
- In-app notifications for upcoming doses
- Google Calendar integration
- Customizable reminder settings
- Multiple reminder methods

### 4. Analytics Dashboard
- Calendar heatmap visualization
- Weekly adherence percentage charts
- Most commonly missed medications analysis
- Trend analysis and insights

### 5. Export Capabilities
- PDF report generation
- CSV data export
- Doctor-friendly summaries
- Custom date range exports

## 🛠️ Tech Stack

- **Frontend**: Next.js with TypeScript
- **Styling**: Tailwind CSS
- **Backend**: Supabase
- **Authentication**: Supabase Auth
- **Deployment**: Vercel
- **Version Control**: GitHub

## 🚀 Getting Started

1. Clone the repository:
```bash
git clone https://github.com/YashSadhu/MedTrack.git
cd MedTrack
```

2. Install dependencies:
```bash
pnpm install
```

3. Set up environment variables:
```bash
cp .env.example .env.local
```

4. Run the development server:
```bash
pnpm dev
```

5. Open [http://localhost:3000](http://localhost:3000) in your browser.

## 📝 Environment Variables

Create a `.env.local` file with the following variables:

```env
NEXT_PUBLIC_SUPABASE_URL=your_supabase_url
NEXT_PUBLIC_SUPABASE_ANON_KEY=your_supabase_anon_key
```

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👥 Authors

- Yash Sadhu - Initial work

## 🙏 Acknowledgments

- Thanks to all contributors who have helped shape this project
- Special thanks to the open-source community for their invaluable tools and resources 