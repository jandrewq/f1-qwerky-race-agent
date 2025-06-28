# 🏁 F1 Qwerky Race Agent

**Real-time AI-powered F1 race companion with VOICE COMMENTARY using cutting-edge Mojo and live telemetry data**

![F1 AI System](https://img.shields.io/badge/F1-AI%20System-red) ![Mojo](https://img.shields.io/badge/Language-Mojo-blue) ![Live Data](https://img.shields.io/badge/Data-Live%20F1%20API-green) ![Voice](https://img.shields.io/badge/Voice-ElevenLabs%20AI-purple) ![Status](https://img.shields.io/badge/Status-Voice%20Commentary%20LIVE-brightgreen)

## 🚀 What This Does

Transform your F1 viewing experience with an AI race engineer that **TALKS TO YOU** with:

- **🎙️ LIVE VOICE COMMENTARY** - AI speaks race analysis with multiple personalities
- **🧠 Real F1 data processing** - Live driver info, teams, and session data  
- **🎭 Multiple AI voices** - Professional British, Entertaining American, Savage Australian
- **📡 Real-time integration** - Connected to OpenF1 API with live 2025 season data
- **⚡ Lightning-fast processing** - Built with Mojo for sub-second responses
- **🎯 Interactive voice controls** - Change personalities, focus drivers, adjust commentary

## 🎙️ Voice Commentary System - NEW!

**Three distinct AI commentator personalities:**

### **🎙️ Professional Mode (British Accent)**
*"Verstappen maintains the lead with consistent sector times and optimal tire management strategies."*

### **🎪 Entertaining Mode (American Accent)**  
*"OH MY GOODNESS! What an absolutely incredible overtake by Hamilton into turn one!"*

### **🔥 Savage Mode (Australian Accent)**
*"Well, that pit stop was about as smooth as a three-legged kangaroo on roller skates!"*

## 🔥 Live Features - WORKING!

**Voice + Data Integration:**
- ✅ **Real-time voice synthesis** with ElevenLabs AI
- ✅ **Live F1 data** processed and spoken instantly
- ✅ **Commentary controls** - volume, personality switching, focus modes
- ✅ **Interactive commands** - "Focus on Hamilton", "Switch to Savage mode"
- ✅ **Race weekend ready** - Works during Practice, Qualifying, and Race

**Currently processing real 2025 F1 season data including:**
- ✅ Max Verstappen (#1) - Red Bull Racing
- ✅ Lewis Hamilton (#44) - Ferrari (Historic move!)
- ✅ Lando Norris (#4) - McLaren  
- ✅ Gabriel Bortoleto (#5) - Kick Sauber (Rookie!)
- ✅ All 20 current F1 drivers with live team data

## 🛠️ Advanced Tech Stack

- **[Mojo](https://docs.modular.com/mojo/)** - High-performance AI language by Modular
- **[ElevenLabs AI](https://elevenlabs.io/)** - Professional voice synthesis with multiple accents
- **OpenF1 API** - Real-time F1 telemetry and driver data (LIVE)
- **Python Requests** - HTTP integration for live data fetching
- **Interactive Web Dashboard** - Voice-controlled race analysis interface
- **Magic Environment** - Optimized AI development and deployment

## 🚀 Quick Start

### Prerequisites
- macOS (tested on Apple Silicon)
- [Modular Magic installed](https://docs.modular.com/magic/)
- [ElevenLabs Account](https://elevenlabs.io/) (free tier available)
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

# Run the F1 AI agent backend
magic run mojo src/f1_race_agent.mojo

# Open voice-enabled web interface
open dashboard/index.html
\`\`\`

### Voice Setup
1. **Get ElevenLabs API key** from [elevenlabs.io](https://elevenlabs.io/)
2. **Enter API key** in the dashboard setup section
3. **Choose your preferred commentary personality**
4. **Start voice commentary** and enjoy!

## 📊 Example Live Output with Voice

\`\`\`
🏁 F1 Qwerky Race Agent - LIVE DATA + VOICE
📡 Fetching REAL F1 data from OpenF1 API...
📊 API Response Status: 200
✅ SUCCESS: Real F1 data received!
🎙️ Voice commentary: "Twenty drivers confirmed on track for this session"

🏁 LIVE F1 DRIVER DATA + VOICE ANALYSIS:
🏎️ 1 - M VERSTAPPEN
   📍 Team: Red Bull Racing
   🎙️ "Verstappen takes pole position with a dominant performance"

🧠 [AI VOICE INSIGHT] "Hamilton's move to Ferrari is the biggest story of 2025!"
\`\`\`

## 🎮 Interactive Voice Features

**Real-time voice commands:**
- **"Focus on [Driver]"** - Dedicated commentary on specific drivers
- **"Switch to Savage mode"** - Change AI personality instantly  
- **"Technical analysis"** - Deep-dive engineering commentary
- **"Race prediction"** - AI forecasts with voice explanation
- **Volume control** - Adjust commentary levels
- **Pause/Resume** - Control commentary flow

## 🏎️ Race Weekend Experience

**Perfect for:**
- **Friday Practice** - Test system with live data + voice
- **Saturday Qualifying** - Exciting lap-by-lap voice analysis
- **Sunday Race** - Full commentary experience with personality switching

**Dynamic commentary adapts to race action:**
- Calm analysis during routine laps
- Excited commentary during battles
- Technical breakdowns during pit stops
- Savage roasting when drivers make mistakes

## 🎯 System Architecture

\`\`\`
🏎️ Live F1 Data → 📡 OpenF1 API → 🧠 Mojo AI Engine → 🎙️ Voice Synthesis → 👂 You
                                    ↑                      ↑
                              Qwerky AI Integration    ElevenLabs AI Voices
\`\`\`

## 🤖 Ready for Custom AI Integration

**Qwerky AI integration points prepared:**
- ✅ Real F1 data pipeline established
- ✅ Voice personality framework built  
- ✅ Commentary timing and flow controls
- ✅ Input/output formatting ready
- ✅ Error handling and fallbacks implemented

## 🏆 Technical Achievements

- ✅ **Real-time F1 API integration** with live data processing
- ✅ **Multi-personality voice synthesis** using ElevenLabs AI
- ✅ **High-performance Mojo processing** for sub-second responses
- ✅ **Interactive voice controls** with personality switching
- ✅ **Professional commentary timing** and flow management
- ✅ **Modular AI integration architecture** ready for custom models
- ✅ **Race weekend deployment ready** with voice + data

## 🎪 Demo Features

**Try these even without a live race:**
- 🎙️ **Voice personality testing** - Hear different commentary styles
- 📊 **Data connection verification** - Test F1 API integration  
- 🎮 **Interactive controls** - Focus modes, voice switching
- 🧪 **Commentary simulation** - Experience race weekend atmosphere

## 🎵 Audio Experience

**Professional broadcast quality:**
- **Crystal clear voice synthesis** using ElevenLabs AI
- **Multiple accent options** for diverse commentary experience
- **Dynamic volume control** for optimal listening
- **Intelligent commentary pacing** - no overwhelming chatter
- **Context-aware personality switching** based on race events

## 🤝 Contributing

This system welcomes contributions for:
- **Additional voice personalities** and accents
- **Custom AI model integration** (Qwerky AI ready!)
- **Enhanced F1 data sources** and analysis
- **Commentary timing improvements**
- **Multi-language voice support**

## 📜 License

MIT License - Build your own voice-enabled F1 AI projects!

## 🎉 Acknowledgments

- **Modular** for the incredible Mojo language and MAX platform
- **ElevenLabs** for professional AI voice synthesis technology
- **OpenF1** for providing free, real-time F1 data access
- **Qwerky AI** for inspiring better race analysis tools

---

**⚡ Experience the future of AI-powered F1 analysis with LIVE VOICE COMMENTARY!**

*Built with cutting-edge Mojo • Powered by live F1 data • Enhanced with ElevenLabs AI voices • Ready for race weekends*

## 🏁 Race Weekend Ready!

**Your AI commentator is standing by for Practice, Qualifying, and Race sessions!**
