# 51M3NV

**Space Weather Intelligence & Monitoring Environment**

A real-time space weather monitoring and forecasting dashboard built on NOAA/SWPC data streams. 51M3NV is an independent proof of concept for browser-native space weather visualization, designed to make complex solar activity data accessible and actionable for researchers, professionals, and enthusiasts.

## Overview

Space weather—the dynamic conditions in the Earth's upper atmosphere and magnetosphere—drives critical phenomena including geomagnetic storms, solar radiation storms, and radio blackouts. These events have cascading effects on satellite operations, power grids, GPS networks, and telecommunications infrastructure.

51M3NV provides a unified interface for monitoring:

- **Geomagnetic Activity (Kp Index)** - Real-time and forecast Kp values with 3-hourly granularity
- - **Solar Flare & Radiation Storm Probabilities** - 3-day event probability forecasts
  - - **Aurora Hemispheric Power** - OVATION model data tracking auroral energy input
    - - **D-Region Absorption (D-RAP)** - HF propagation impact assessment
      - - **27-Day Space Weather Outlook** - Extended forecast with solar flux and geomagnetic indices
        - - **45-Day Predictions** - Ap index and F10.7 cm flux forecasting
          - - **NOAA Space Weather Scales** - Real-time classification of current event severity
           
            - ## Features
           
            - ✨ **Live Data Integration**
            - - Direct connection to NOAA Space Weather Prediction Center (SWPC) data APIs
              - - Automatic updates with real-time forecasts and observations
                - - UTC-synchronized data streaming
                 
                  - 🎨 **Professional Dashboard Interface**
                  - - Dark-mode optimized design for extended monitoring sessions
                    - - Responsive grid layout adapting to various screen sizes
                      - - Color-coded severity indicators aligned with NOAA scales
                       
                        - 📊 **Advanced Visualization**
                        - - Chart.js powered interactive charts and graphs
                          - - Real-time data plotting for Aurora Hemispheric Power
                            - - 27-day and 45-day forecast trend analysis
                             
                              - ⚡ **Monospace Typography**
                              - - JetBrains Mono font for precise data readability
                                - - Space Grotesk for header legibility
                                  - - Optimized for dense information presentation
                                   
                                    - ## Project Position
                                   
                                    - 51M3NV is an independent proof of concept demonstrating how data-intensive scientific applications can be translated into accessible, browser-native interfaces without compromising technical rigor or data integrity. The project emphasizes:
                                   
                                    - - **Direct Data Attribution** - All data sourced from NOAA/NWS/NCEP/SWPC
                                      - - **Transparent Methods** - Open-source dashboard code with explicit data provenance
                                        - - **Academic Clarity** - Complex phenomena presented with appropriate technical context
                                          - - **Public Accessibility** - No paywalls, logins, or registration requirements
                                           
                                            - ## Technical Stack
                                           
                                            - - **Frontend**: Vanilla JavaScript, HTML5, CSS3
                                              - - **Data Visualization**: Chart.js 4.4.1
                                                - - **Data Source**: NOAA SWPC Services API
                                                  - - **Fonts**: Google Fonts (JetBrains Mono, Space Grotesk)
                                                    - - **Hosting**: GitHub Pages compatible
                                                     
                                                      - ## File Structure
                                                     
                                                      - ```
                                                        51M3NV/
                                                        ├── SPACE WEATHER 4CAST.html    # Main application (standalone)
                                                        ├── README.md                     # This file
                                                        ```

                                                        ## Quick Start

                                                        1. Open SPACE WEATHER 4CAST.html in a modern web browser
                                                        2. 2. Dashboard will automatically fetch current data from NOAA SWPC
                                                           3. 3. Charts and tables update in real-time
                                                              4. 4. Monitor ongoing space weather events and 3-45 day forecasts
                                                                
                                                                 5. ## Data Sources & Attribution
                                                                
                                                                 6. **Primary Source**: NOAA Space Weather Prediction Center
                                                                 7. - **Base URL**: https://services.swpc.noaa.gov
                                                                    - - **Data Products**:
                                                                      -   - Real-time Kp index and geomagnetic scales
                                                                          -   - 3-day narrative forecast and event probabilities
                                                                              -   - Aurora hemispheric power (OVATION)
                                                                                  -   - D-Region absorption predictions
                                                                                      -   - 27-day outlook and extended forecasting
                                                                                       
                                                                                          - **Citation Reference**:
                                                                                          - ```
                                                                                            NOAA/NWS/NCEP/SWPC (Space Weather Prediction Center)
                                                                                            Real-time Space Weather Data and Forecasting Services
                                                                                            https://www.swpc.noaa.gov
                                                                                            Boulder, Colorado
                                                                                            ```

                                                                                            ## Browser Compatibility

                                                                                            - Chrome/Chromium (recommended)
                                                                                            - - Firefox
                                                                                              - - Safari
                                                                                                - - Edge
                                                                                                  - - Requires ES6+ JavaScript support
                                                                                                   
                                                                                                    - ## Why 51M3NV?
                                                                                                   
                                                                                                    - The project name reflects a mission to create **51** (research-grade) **M3** (multi-modal meteorology models) **NV** (near-real-time visualization) interfaces. It's a commitment to bringing sophisticated scientific workflows into transparent, public-facing tools.
                                                                                                   
                                                                                                    - ## Known Limitations
                                                                                                   
                                                                                                    - - Dashboard requires internet connectivity for live data
                                                                                                      - - NOAA API rate limits apply to concurrent requests
                                                                                                        - - Some older browsers may not support CSS Grid or ES6 features
                                                                                                          - - Mobile responsiveness optimized for portrait orientation
                                                                                                           
                                                                                                            - ## Future Enhancements
                                                                                                           
                                                                                                            - - Historical data archive and trend analysis
                                                                                                              - - Custom alert configuration
                                                                                                                - - Data export capabilities (CSV, JSON)
                                                                                                                  - - Multi-language interface
                                                                                                                    - - Mobile-optimized native applications
                                                                                                                     
                                                                                                                      - ## License & Attribution
                                                                                                                     
                                                                                                                      - This project is self-funded and shared as an independent proof of concept. All data visualizations and forecasts remain the intellectual property of NOAA/NWS/NCEP/SWPC. This dashboard is a presentation interface, not an official NOAA product.
                                                                                                                     
                                                                                                                      - ---
                                                                                                                      
                                                                                                                      **Last Updated**: April 2026
                                                                                                                      **Data Source**: NOAA SWPC Real-time Services
                                                                                                                      **Status**: Active Development & Monitoring
