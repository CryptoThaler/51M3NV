# 51M3NV: Space Weather Intelligence & Monitoring Environment

[![Live Demo](https://img.shields.io/badge/Live%20Demo-51M3NV-00e5a0?style=flat-square&logo=github-pages)](./SPACE%20WEATHER%204CAST.html)
[![HTML5](https://img.shields.io/badge/HTML5-E34C26?style=flat-square&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Chart.js](https://img.shields.io/badge/Chart.js-FF6384?style=flat-square&logo=chartdotjs&logoColor=white)](https://www.chartjs.org/)
[![NOAA API](https://img.shields.io/badge/NOAA%20SWPC-2196F3?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3B%3D%20%3Csvg%20width%3D%2724%27%20height%3D%2724%27%20viewBox%3D%270%200%2024%2024%27%20fill%3D%27white%27%3E%3Ccircle%20cx%3D%2712%27%20cy%3D%2712%27%20r%3D%2710%27%20stroke%3D%27%232196F3%27%20stroke-width%3D%272%27%2F%3E%3C%2Fsvg%3E)](https://services.swpc.noaa.gov)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)](./LICENSE)
[![Maintainer](https://img.shields.io/badge/Maintainer-CryptoThaler-blue?style=flat-square)](https://github.com/CryptoThaler)

## 🚀 [▶️ LAUNCH DASHBOARD](https://cdn.jsdelivr.net/gh/CryptoThaler/51M3NV@main/SPACE%20WEATHER%204CAST.html)
**Click above to open the Space Weather 4Cast dashboard instantly in your browser.**

---

## 🌐 Overview

**51M3NV** is a real-time environmental data forecasting dashboard that transforms complex space weather information into an intuitive, professional monitoring interface. Built with vanilla JavaScript and powered by NOAA's Space Weather Prediction Center (SWPC) APIs, 51M3NV delivers critical solar activity intelligence directly to your browser—with zero dependencies and zero setup overhead.

### Who This Is For

- **Space Weather Researchers & Scientists** - Real-time data access with historical context
- - **Amateur Radio Operators** - Ionospheric condition forecasts affecting HF propagation
  - - **Satellite Operators & Engineers** - Geomagnetic storm warnings and solar radiation alerts
    - - **Technology Professionals** - Understanding infrastructure impacts during space weather events
      - - **Open-Source Contributors** - Clean, well-documented JavaScript codebase ready for extension
       
        - ---

        ## ✨ Key Features

        ### 🔴 Real-Time Monitoring
        - **Kp Index Tracking** - 3-hourly geomagnetic activity forecasts with 3-day outlook
        - - **NOAA Space Weather Scales** - Real-time classification of Radio Blackout (R), Solar Radiation (S), and Geomagnetic Storm (G) events
          - - **Aurora Hemispheric Power (OVATION)** - Live auroral energy input measurements with trend analysis
            - - **D-Region Absorption (D-RAP)** - HF propagation impact assessment for radio communications
             
              - ### 📊 Advanced Forecasting
              - - **3-Day Narrative Forecast** - SWPC official text forecasts with event probabilities
                - - **27-Day Space Weather Outlook** - Extended Ap index and F10.7 solar flux predictions
                  - - **45-Day Extended Forecasting** - Long-range Ap and F10.7 cm flux trends
                    - - **Solar Flare & Radiation Probabilities** - R1-R5 radio blackout and S1-S5 radiation storm likelihoods
                     
                      - ### 🎨 Professional Interface
                      - - **Dark Mode Dashboard** - Optimized for extended monitoring sessions and eye comfort
                        - - **Responsive Grid Layout** - Adapts seamlessly to desktop, tablet, and large-display environments
                          - - **Color-Coded Severity Indicators** - NOAA-aligned warning levels for instant event recognition
                            - - **Live UTC Clock** - Automatic synchronization with forecast issuance times
                             
                              - ### 📈 Data Visualization
                              - - **Interactive Charts** - Chart.js-powered visualizations with real-time updates
                                - - **Aurora Power Trends** - Northern and Southern Hemisphere comparisons
                                  - - **27-Day & 45-Day Forecasts** - Dual-axis plotting for Kp/Ap and F10.7 indices
                                    - - **Probability Bars** - Visual representation of event likelihoods
                                     
                                      - ### ⚡ Technical Excellence
                                      - - **100% Client-Side** - No server required; runs entirely in the browser
                                        - - **Vanilla JavaScript** - Zero npm dependencies, zero build process
                                          - - **Direct API Integration** - Real-time data from NOAA SWPC services
                                            - - **Professional Typography** - JetBrains Mono for data readability, Space Grotesk for headers
                                              - - **Responsive Design** - Desktop, tablet, and multi-monitor support
                                               
                                                - ---

                                                ## 🚀 Quick Start

                                                ### Option 1: Live Deployment (Recommended)
                                                Simply open `SPACE WEATHER 4CAST.html` in your browser:

                                                ```bash
                                                # Clone the repository
                                                git clone https://github.com/CryptoThaler/51M3NV.git
                                                cd 51M3NV

                                                # Open in your default browser (macOS/Linux)
                                                open SPACE\ WEATHER\ 4CAST.html

                                                # Or on Windows
                                                start "SPACE WEATHER 4CAST.html"
                                                ```

                                                > [!TIP]
                                                > > For the best experience, use **Google Chrome** or **Chromium-based browsers** (Edge, Brave). Firefox and Safari are also fully supported.
                                                > >
                                                > > ### Option 2: GitHub Pages
                                                > > If hosted via GitHub Pages, access directly at:
                                                > > ```
                                                > > https://cryptothaler.github.io/51M3NV/SPACE%20WEATHER%204CAST.html
                                                > > ```
                                                > >
                                                > > ### Option 3: Local Server (Optional)
                                                > > For development or enhanced security policies:
                                                > >
                                                > > ```bash
                                                > > # Python 3.x
                                                > > python3 -m http.server 8000
                                                > >
                                                > > # Then visit: http://localhost:8000
                                                > > ```
                                                > >
                                                > > > [!NOTE]
                                                > > > > The NOAA SWPC API is public and CORS-enabled. If you encounter CORS errors, your browser's security policies may require serving via HTTPS or localhost. Use Option 3 above.
                                                > > > >
                                                > > > > ---
                                                > > > >
                                                > > > > ## 📁 Project Structure
                                                > > > >
                                                > > > > ```
                                                > > > > 51M3NV/
                                                > > > > │
                                                > > > > ├── SPACE WEATHER 4CAST.html    # Standalone application (all-in-one)
                                                > > > > │   ├── HTML5 markup
                                                > > > > │   ├── Embedded CSS (dark theme)
                                                > > > > │   ├── Vanilla JavaScript (Chart.js integration)
                                                > > > > │   └── NOAA SWPC API integration
                                                > > > > │
                                                > > > > └── README.md                     # Documentation (this file)
                                                > > > > ```
                                                > > > >
                                                > > > > **Note**: This is a single-file application. All HTML, CSS, and JavaScript are combined for zero-dependency deployment.
                                                > > > >
                                                > > > > ---
                                                > > > >
                                                > > > > ## 🔌 Tech Stack & Dependencies
                                                > > > >
                                                > > > > | Technology | Purpose | Version | Notes |
                                                > > > > |------------|---------|---------|-------|
                                                > > > > | **HTML5** | Structure & Markup | Latest | Semantic HTML, viewport meta tags |
                                                > > > > | **CSS3** | Styling & Dark Theme | Latest | CSS Grid, Flexbox, CSS Variables |
                                                > > > > | **JavaScript (ES6+)** | Logic & Interactivity | Latest | Async/await, Fetch API, DOM manipulation |
                                                > > > > | **Chart.js** | Data Visualization | 4.4.1 | CDN-hosted, CORS-compatible |
                                                > > > > | **Google Fonts** | Typography | Latest | JetBrains Mono, Space Grotesk |
                                                > > > > | **NOAA SWPC API** | Real-time Data | Live | https://services.swpc.noaa.gov |
                                                > > > >
                                                > > > > ### External CDN Resources
                                                > > > > ```html
                                                > > > > <!-- Chart.js for visualization -->
                                                > > > > <script src="https://cdnjs.cloudflare.com/ajax/libs/Chart.js/4.4.1/chart.umd.min.js"></script>
                                                > > > >
                                                > > > > <!-- Google Fonts for typography -->
                                                > > > > <link href="https://fonts.googleapis.com/css2?family=JetBrains+Mono:wght@400;500;600;700&family=Space+Grotesk:wght@400;500;600;700&display=swap" rel="stylesheet">
                                                > > > > ```
                                                > > > >
                                                > > > > ---
                                                > > > >
                                                > > > > ## 📊 Data Source & Attribution
                                                > > > >
                                                > > > > ### Primary Data Provider
                                                > > > > **NOAA Space Weather Prediction Center (SWPC)**
                                                > > > >
                                                > > > > - **URL**: https://services.swpc.noaa.gov
                                                > > > > - - **Data Products**: Real-time and forecast space weather data
                                                > > > >   - - **Update Frequency**: Every 30 minutes (forecasts), continuous (observations)
                                                > > > >     - - **Accessibility**: Public APIs, no authentication required
                                                > > > >      
                                                > > > >       - ### API Endpoints Used
                                                > > > >      
                                                > > > >       - | Endpoint | Data Type | Update Frequency |
                                                > > > >       - |----------|-----------|------------------|
                                                > > > >       - | `/products/noaa-scales.json` | Current space weather scales | 30 min |
                                                > > > > | `/text/3-day-forecast.txt` | 3-day narrative forecast | 6 times daily |
                                                > > > > | `/text/aurora-nowcast-hemi-power.txt` | Aurora hemispheric power | 30 min |
                                                > > > > | `/text/drap_global_frequencies.txt` | D-Region absorption | 1 hour |
                                                > > > > | `/text/27-day-outlook.txt` | Extended 27-day outlook | Daily |
                                                > > > > | `/json/45-day-forecast.json` | 45-day predictions | Daily |
                                                > > > >
                                                > > > > ### Citation
                                                > > > > ```bibtex
                                                > > > > @organization{NOAA_SWPC,
                                                > > > >   title={Space Weather Prediction Center Real-time Data Services},
                                                > > > >   author={NOAA/NWS/NCEP/SWPC},
                                                > > > >   year={2026},
                                                > > > >   url={https://www.swpc.noaa.gov},
                                                > > > >   address={Boulder, Colorado}
                                                > > > > }
                                                > > > > ```
                                                > > > >
                                                > > > > ---
                                                > > > >
                                                > > > > ## 🌐 Browser Compatibility
                                                > > > >
                                                > > > > | Browser | Status | Notes |
                                                > > > > |---------|--------|-------|
                                                > > > > | **Chrome/Chromium 90+** | ✅ Fully Supported | Recommended |
                                                > > > > | **Firefox 88+** | ✅ Fully Supported | Excellent performance |
                                                > > > > | **Safari 14+** | ✅ Fully Supported | iOS & macOS |
                                                > > > > | **Edge 90+** | ✅ Fully Supported | Chromium-based |
                                                > > > > | **Opera 76+** | ✅ Fully Supported | Chromium-based |
                                                > > > >
                                                > > > > **Requirements**: ES6+ JavaScript support, CSS Grid, Fetch API, Local Storage
                                                > > > >
                                                > > > > ---
                                                > > > >
                                                > > > > ## ⚙️ Configuration & Customization
                                                > > > >
                                                > > > > ### Modifying Update Intervals
                                                > > > > Edit the JavaScript section to adjust data refresh rates:
                                                > > > >
                                                > > > > ```javascript
                                                > > > > // Default: Updates every time the page loads
                                                > > > > // To add auto-refresh: Uncomment and modify
                                                > > > > // setInterval(() => location.reload(), 300000); // Refresh every 5 minutes
                                                > > > > ```
                                                > > > >
                                                > > > > ### Changing Dark Theme Colors
                                                > > > > All colors use CSS variables in the `:root` selector:
                                                > > > >
                                                > > > > ```css
                                                > > > > :root {
                                                > > > >   --bg: #0a0c10;           /* Primary background */
                                                > > > >   --acc: #00e5a0;          /* Accent (green) */
                                                > > > >   --warn: #ff6b35;         /* Warning (orange) */
                                                > > > >   --crit: #ff3355;         /* Critical (red) */
                                                > > > >   --tx: #e2e4e9;           /* Text color */
                                                > > > >   /* ... more variables */
                                                > > > > }
                                                > > > > ```
                                                > > > >
                                                > > > > ---
                                                > > > >
                                                > > > > ## 🤝 Contributing
                                                > > > >
                                                > > > > We welcome contributions from the community! Whether you're fixing bugs, adding features, or improving documentation:
                                                > > > >
                                                > > > > 1. **Fork** the repository
                                                > > > > 2. 2. **Create a feature branch**: `git checkout -b feature/amazing-feature`
                                                > > > >    3. 3. **Commit your changes**: `git commit -m 'Add amazing feature'`
                                                > > > >       4. 4. **Push to branch**: `git push origin feature/amazing-feature`
                                                > > > >          5. 5. **Open a Pull Request**
                                                > > > >            
                                                > > > >             6. ### Contribution Ideas
                                                > > > >             7. - Additional space weather data sources
                                                > > > >                - - Mobile-optimized layouts
                                                > > > >                  - - Historical data archiving
                                                > > > >                    - - Alert/notification system
                                                > > > >                      - - Data export (CSV, JSON)
                                                > > > >                        - - Internationalization (i18n)
                                                > > > >                         
                                                > > > >                          - ---
                                                > > > >
                                                > > > > ## 📋 Known Limitations
                                                > > > >
                                                > > > > - 🌐 **Internet Required**: Dashboard needs live internet for NOAA API access
                                                > > > > - - ⏱️ **API Rate Limits**: NOAA SWPC enforces fair-use rate limiting
                                                > > > >   - - 📱 **Mobile Layout**: Optimized for landscape/desktop; portrait mode supported but not ideal
                                                > > > >     - - 🔐 **No Authentication**: Uses public NOAA APIs; not suitable for private data scenarios
                                                > > > >       - - 🕐 **Data Latency**: Real-time data has inherent 30-minute to 1-hour delay from observations
                                                > > > >        
                                                > > > >         - ---
                                                > > > >
                                                > > > > ## 🗺️ Roadmap
                                                > > > >
                                                > > > > ### v1.1 (Q2 2026)
                                                > > > > - [ ] Historical data archive (30-day rolling window)
                                                > > > > - [ ] - [ ] Custom alert thresholds
                                                > > > > - [ ] - [ ] CSV/JSON data export
                                                > > > > - [ ] - [ ] Mobile app (React Native)
                                                > > > >
                                                > > > > - [ ] ### v2.0 (Q4 2026)
                                                > > > > - [ ] - [ ] Multi-language support (Spanish, French, German, Japanese)
                                                > > > > - [ ] - [ ] Advanced filtering & comparison tools
                                                > > > > - [ ] - [ ] User preferences & saved layouts
                                                > > > > - [ ] - [ ] Community data submissions
                                                > > > >
                                                > > > > - [ ] ---
                                                > > > >
                                                > > > > - [ ] ## 📝 License
                                                > > > >
                                                > > > > - [ ] This project is released under the **MIT License**. See the [LICENSE](./LICENSE) file for details.
                                                > > > >
                                                > > > > - [ ] **Important**: This dashboard is an independent interface to publicly available NOAA data. All space weather data remains the intellectual property of NOAA/NWS/NCEP/SWPC. This project is not affiliated with or endorsed by NOAA.
                                                > > > >
                                                > > > > - [ ] ---
                                                > > > >
                                                > > > > - [ ] ## 🙋 Support & Community
                                                > > > >
                                                > > > > - [ ] - **Found a Bug?** [Open an Issue](https://github.com/CryptoThaler/51M3NV/issues)
                                                > > > > - [ ] - **Have a Feature Request?** [Start a Discussion](https://github.com/CryptoThaler/51M3NV/discussions)
                                                > > > > - [ ] - **Want to Chat?** Check out the community discussions tab
                                                > > > >
                                                > > > > - [ ] ### Resource Links
                                                > > > > - [ ] - 📖 [NOAA SWPC Documentation](https://www.swpc.noaa.gov/products)
                                                > > > > - [ ] - 📚 [Space Weather Overview (NOAA)](https://www.swpc.noaa.gov/phenomena/space-weather)
                                                > > > > - [ ] - 🎓 [Chart.js Documentation](https://www.chartjs.org/docs/latest/)
                                                > > > > - [ ] - 🔗 [GitHub Pages Hosting Guide](https://pages.github.com/)
                                                > > > >
                                                > > > > - [ ] ---
                                                > > > >
                                                > > > > - [ ] ## 👨‍💻 About the Author
                                                > > > >
                                                > > > > - [ ] **51M3NV** was created as an independent proof of concept demonstrating how complex scientific data can be made accessible through professional, transparent browser-native interfaces.
                                                > > > >
                                                > > > > - [ ] - **Creator**: [CryptoThaler](https://github.com/CryptoThaler)
                                                > > > > - [ ] - **Project Status**: Active Development
                                                > > > > - [ ] - **Last Updated**: April 2026
                                                > > > >
                                                > > > > - [ ] ---
                                                > > > >
                                                > > > > - [ ] ## ⭐ Show Your Support
                                                > > > >
                                                > > > > - [ ] If 51M3NV has been useful for your research, work, or curiosity, please consider giving it a star ⭐ on GitHub. It helps visibility and motivates continued development!
                                                > > > >
                                                > > > > - [ ] ```
                                                > > > > - [ ] git clone https://github.com/CryptoThaler/51M3NV.git
                                                > > > > - [ ] cd 51M3NV
                                                > > > > - [ ] # Open SPACE WEATHER 4CAST.html and enjoy!
                                                > > > > - [ ] ```
                                                > > > >
                                                > > > > - [ ] ---
                                                > > > >
                                                > > > > - [ ] **Made with ☄️ for space weather enthusiasts, everywhere.**
