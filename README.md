# 8-Week Dynamic Strength & Size Program

A comprehensive, research-backed 8-week workout program with automated progress tracking, dynamic weight calculations, and performance analytics.

## 🏋️ Features

### Program Design
- **8-Week Periodized Program**: Foundation → Intensification → Peak → Deload → Testing
- **Dynamic Weight Calculations**: Enter your 1RM and get precise weight recommendations
- **7-Day Training Schedule**: 5 lifting days + 2 cardio/recovery days
- **Research-Backed**: Evidence-based rep ranges, periodization, and recovery protocols

### Progress Tracking
- **📊 Visual Analytics**: Interactive charts tracking strength, cardio, and volume
- **📈 1RM Progress**: Historical tracking of all major lifts
- **💓 Cardio Performance**: Split times and heart rate analysis
- **📅 Completion Tracking**: Mark workouts complete with dates
- **📥 Data Export/Import**: Backup and restore your progress data

### Smart Features
- **Heart Rate Zones**: Automatic calculation based on max HR
- **Plate Math**: Rounds weights to your available plates
- **Accessory Calculations**: Auto-calculates weights for isolation exercises
- **Progress Summaries**: Key metrics and program completion stats

## 🚀 Quick Start

### Option 1: Use GitHub Pages (Recommended)

1. **Fork this repository**
2. **Enable GitHub Pages**:
   - Go to Settings → Pages
   - Source: Deploy from a branch
   - Branch: main / (root)
3. **Access your app**: `https://[username].github.io/[repository-name]`

### Option 2: Local Development

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/your-repo-name.git
   cd your-repo-name
   ```

2. **Open locally**:
   - Simply open `index.html` in your browser
   - Or use a local server: `python -m http.server 8000`

## 📋 How to Use

### Initial Setup
1. **Enter Your 1RMs**: Input current max lifts in the calculator section
2. **Set Heart Rate**: Enter your max heart rate for cardio zones
3. **Choose Plate Increments**: Select your available plate weights

### Training
1. **Follow the Program**: Navigate through weeks 1-8 using the week selector
2. **Track Completion**: Check off completed workouts and log dates
3. **Log Cardio**: Record splits, heart rate, and distance for cardio sessions
4. **Update 1RMs**: Use the progress tracking section to log new PRs

### Progress Monitoring
1. **Click "📊 Progress"** to view your analytics dashboard
2. **Export Data**: Backup your progress as JSON files
3. **Import Data**: Restore from previous backups
4. **Track Trends**: Monitor strength gains, completion rates, and cardio improvements

## 🏃‍♂️ Program Structure

### Weeks 1-2: Foundation Phase
- **Focus**: Movement patterns, form, moderate intensity
- **Intensity**: 70-80% 1RM
- **Volume**: Higher rep ranges, technique emphasis

### Weeks 3-4: Intensification Phase
- **Focus**: Strength building, power development
- **Intensity**: 75-85% 1RM
- **Volume**: Moderate reps, increased load

### Weeks 5-6: Peak Strength Phase
- **Focus**: Maximum strength, neural adaptation
- **Intensity**: 80-90% 1RM
- **Volume**: Lower reps, heavy singles/doubles

### Week 7: Deload Phase
- **Focus**: Recovery and supercompensation
- **Intensity**: 60-70% 1RM
- **Volume**: Reduced, technique work

### Week 8: Testing Phase
- **Focus**: New 1RM attempts, PR testing
- **Intensity**: Max effort attempts
- **Volume**: Minimal, test-focused

## 📊 Tracking Features

### Strength Progress Chart
- Line graph of 1RM progress over time
- Tracks Squat, Bench, Deadlift, OHP
- Historical trend analysis

### Completion Rate
- Doughnut chart showing program completion
- Tracks all 48+ workouts across 8 weeks
- Motivational progress visualization

### Cardio Performance
- Dual-axis chart tracking splits and heart rate
- Identifies aerobic improvements
- Zone-based training guidance

### Volume Analysis
- Weekly training volume estimates
- Tracks progressive overload
- Identifies optimal loading patterns

## 🔧 Technical Details

### Data Storage
- **Local Storage**: All data stored in browser localStorage
- **No Server Required**: Fully client-side application
- **Privacy First**: Your data never leaves your device

### Browser Compatibility
- Modern browsers with ES6+ support
- Chart.js for visualizations
- Responsive design for mobile/tablet

### Data Format
Export files contain:
```json
{
  "workoutData": {
    "squat": 315,
    "bench": 225,
    "completions": {...},
    "cardioLogs": {...}
  },
  "rmHistory": {
    "dates": [...],
    "squat": [...],
    "bench": [...]
  },
  "exportDate": "2024-01-01T00:00:00.000Z"
}
```

## 📚 Research Background

This program incorporates evidence-based principles from:
- **Periodization**: Bompa & Buzzichelli periodization models
- **Volume Landmarks**: Israetel's MRV concepts
- **Intensity Prescription**: Prilepin's chart adaptations
- **Recovery Protocols**: Supercompensation theory
- **Cardio Integration**: Concurrent training research

## 🤝 Contributing

Contributions welcome! Areas for enhancement:
- Additional exercise variations
- Advanced analytics features
- Mobile app development
- Integration with fitness trackers
- Exercise form videos/tutorials

## 📱 Mobile Usage

Fully responsive design optimized for:
- ✅ Gym use on phone/tablet
- ✅ Quick workout logging
- ✅ Real-time weight calculations
- ✅ Progress tracking on-the-go

## 🔒 Privacy & Data

- **Local Storage Only**: No data transmitted to servers
- **Export/Import**: Full control over your data
- **No Tracking**: No analytics or user tracking
- **Offline Capable**: Works without internet after initial load

## 📈 Performance Expectations

Typical results after 8 weeks:
- **Strength**: 5-15% increase in 1RMs
- **Size**: 2-5 lbs muscle gain (with proper nutrition)
- **Work Capacity**: Improved training volume tolerance
- **Technique**: Enhanced movement quality and consistency

## 🆘 Troubleshooting

### Data Lost?
- Check browser localStorage
- Import from exported backup files

### Weights Not Calculating?
- Ensure 1RM values are entered
- Check plate rounding settings

### Charts Not Loading?
- Refresh page
- Clear browser cache
- Ensure Chart.js loads properly

## 📄 License

Open source - feel free to modify and distribute!

---

**Ready to get stronger? Start your 8-week journey today! 💪** 