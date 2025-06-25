# 🏁 F1 Qwerky Race Agent

**Real-time AI-powered F1 race companion using cutting-edge Mojo and LIVE telemetry data**

![F1 AI System](https://img.shields.io/badge/F1-AI%20System-red) ![Mojo](https://img.shields.io/badge/Language-Mojo-blue) ![Live Data](https://img.shields.io/badge/Data-Live%20F1%20API-green) ![Status](https://img.shields.io/badge/Status-Live%20Data%20Integrated-brightgreen)

## 🚀 What This Does

Transform your F1 viewing experience with an AI race engineer that:

- **🧠 Processes LIVE F1 data** - Real driver info, teams, and session data
- **🎮 Multiple AI personalities** - Professional analysis, entertaining commentary, or savage roasting mode  
- **📡 Real-time integration** - Connected to OpenF1 API with live 2025 season data
- **⚡ Lightning-fast processing** - Built with Mojo for sub-second responses
- **🎯 Ready for custom AI** - Integration points prepared for Qwerky AI model

## 🔥 Live Data Integration - WORKING!

**Currently processing real 2025 F1 season data including:**
- ✅ Max Verstappen (#1) - Red Bull Racing
- ✅ Lando Norris (#4) - McLaren  
- ✅ Gabriel Bortoleto (#5) - Kick Sauber (Rookie!)
- ✅ Lewis Hamilton (#44) - Ferrari (Historic move!)
- ✅ All 20 current F1 drivers with live team data

## 🎪 AI Personalities (Ready for Qwerky Integration)

### Professional Mode 📊
*"Verstappen is maintaining consistent sector times with optimal tire management"*

### Entertaining Mode 🎉  
*"Leclerc is driving like he's got a pizza delivery deadline! 🍕"*

### Savage Mode 🔥
*"That pit stop was so slow, they could have rebuilt the entire car!"*

## 🛠️ Tech Stack

- **[Mojo](https://docs.modular.com/mojo/)** - High-performance AI language by Modular
- **OpenF1 API** - Real-time F1 telemetry and driver data (LIVE)
- **Python Requests** - HTTP integration for live data fetching
- **Interactive Web Dashboard** - Real-time analysis interface
- **Magic Environment** - Optimized development and deployment

## 🏎️ Live Data Features

**Real F1 data integration includes:**
- ✅ Live driver lineup (all 20 drivers)
- ✅ Current team assignments 
- ✅ Real session data and meeting keys
- ✅ Driver numbers and broadcast names
- ✅ Team colors and information
- ✅ 2025 season roster with rookie drivers

## 🚀 Quick Start

### Prerequisites
- macOS (tested on Apple Silicon)
- [Modular Magic installed](https://docs.modular.com/magic/)
- Internet connection for live F1 data

### Installation

\`\`\`bash
# Clone the repository
git clone https://github.com/jandrewq/f1-qwerky-race-agent.git
cd f1-qwerky-race-agent

# Set up Magic environment
magic shell

# Install required dependencies
magic add requests

# Run the F1 AI agent
magic run mojo src/f1_race_agent.mojo

# Open web interface
open dashboard/index.html
\`\`\`

## 📊 Example Live Output

\`\`\`
🏁 F1 Qwerky Race Agent - LIVE DATA EDITION
📡 Fetching REAL F1 data from OpenF1 API...
📊 API Response Status: 200
✅ SUCCESS: Real F1 data received!
🏎️ Number of drivers in session: 20

🏁 LIVE F1 DRIVER DATA:
🏎️ 1 - M VERSTAPPEN
   📍 Team: Red Bull Racing
🏎️ 4 - L NORRIS  
   📍 Team: McLaren
🏎️ 44 - L HAMILTON
   📍 Team: Ferrari

🧠 [AI INSIGHT] Hamilton's move to Ferrari is the story of 2025!
\`\`\`

## 🤖 Qwerky AI Integration Ready

**Integration points prepared for custom AI model:**
- Real F1 data pipeline established
- Personality switching framework built
- Input/output formatting ready
- Error handling and fallbacks implemented

## 🎯 System Architecture

\`\`\`
🏎️ Live F1 Data → 📡 OpenF1 API → 🧠 Mojo AI Engine → 💬 Web Interface → 👤 You
                                    ↑
                              Qwerky AI Integration Point
\`\`\`

## 📅 Live Data Availability

**System processes real data during:**
- F1 race weekends (Practice, Qualifying, Race)
- Testing sessions and demonstrations
- 2025 season events with live driver lineups

**When no live session:** Falls back to demonstration mode with simulated insights

## 🎮 Interactive Features

- **Focus on specific drivers** during races
- **Switch AI personalities** based on race situation
- **Real-time data processing** during live sessions
- **Professional race analysis** with live telemetry

## 🏆 Technical Achievements

- ✅ Real-time F1 API integration
- ✅ Mojo high-performance processing  
- ✅ Live data parsing and analysis
- ✅ Interactive web dashboard
- ✅ Modular AI integration architecture
- ✅ Professional development practices

## 🤝 Contributing

Contributions welcome! This system is designed for:
- Custom AI model integration
- Additional F1 data sources
- Enhanced analysis features
- Multi-language support

## 📜 License

MIT License - Build your own F1 AI projects!

## 🎉 Acknowledgments

- **Modular** for the incredible Mojo language and MAX platform
- **OpenF1** for providing free, real-time F1 data access
- **F1 Community** for inspiring better race analysis tools

---

**⚡ Experience the future of AI-powered F1 analysis with real data integration!**

*Built with cutting-edge Mojo • Powered by live F1 data • Ready for custom AI integration*
