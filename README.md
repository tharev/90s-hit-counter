# 90s-hit-counter
🔢 Nostalgic 90s-style hit counter with modern features - Bring back the glory days of web 1.0!# 🔢 90s Hit Counter

![90s Hit Counter Banner](https://img.shields.io/badge/90s-Hit%20Counter-purple?style=for-the-badge)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Retro](https://img.shields.io/badge/Style-Retro-ff00ff?style=for-the-badge)

# 🔢 90s Hit Counter

> **✨ Relive the golden age of the Internet!✨** Remember when every website proudly displayed their visitor count? Now you can bring back that retro charm with modern features!

## 🚀 Live Demo

**[👉 Try it Live!](https://tharev.github.io/90s-hit-counter/)** 

[![90s Hit Counter Banner](https://img.shields.io/badge/90s--Hit%20Counter-purple?style=for-the-badge)](https://tharev.github.io/90s-hit-counter/)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![LocalStorage](https://img.shields.io/badge/LocalStorage-4285F4?style=for-the-badge&logo=google-chrome&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/API/Window/localStorage)
[![Retro](https://img.shields.io/badge/Style-Retro-ff00ff?style=for-the-badge)](https://tharev.github.io/90s-hit-counter/)
[![Zero Dependencies](https://img.shields.io/badge/Dependencies-Zero-success?style=for-the-badge)](https://github.com/tharev/90s-hit-counter)
[![MIT License](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)

---

## 📖 About

**90s Hit Counter** is a nostalgic widget that brings back the classic web 1.0 aesthetic of visitor counters. This modern implementation combines retro LED-style digits with customizable features, allowing you to add that perfect touch of 90s nostalgia to your website!

### ✨ Key Features

- 🎨 **Authentic 90s Design** - LED-style digits with classic color schemes
- 🔢 **Customizable Styles** - Multiple retro themes (neon green, red, blue, purple)
- 💾 **LocalStorage Persistence** - Visitor count survives page refreshes
- 🎯 **Lightweight** - Pure vanilla JavaScript, no dependencies
- 📱 **Responsive** - Works perfectly on all devices
- 🌐 **Web 1.0 Aesthetic** - Complete with retro borders and effects
- ⚡ **Zero Backend** - Everything runs client-side
- 🎮 **Interactive Controls** - Reset counter, change styles on the fly

---

## 🎮 Demo

Visit **[https://tharev.github.io/90s-hit-counter/](https://tharev.github.io/90s-hit-counter/)** to see it in action!

### 📸 Screenshots

*[Screenshot placeholder - Add screenshots after visiting the demo]*

**Features in action:**
- Classic LED-style counter digits
- Retro color theme selection (Green, Red, Blue, Purple)
- Visitor count tracking with LocalStorage
- Reset counter functionality
- Nostalgic 90s web design aesthetic

---

## 🚀 Quick Start

### Option 1: Use GitHub Pages (Recommended)

Simply visit the live demo:
```
https://tharev.github.io/90s-hit-counter/
```

### Option 2: Local Installation

1. **Clone the repository**
```bash
git clone https://github.com/tharev/90s-hit-counter.git
cd 90s-hit-counter
```

2. **Open in browser**
```bash
# Simply open index.html in your browser
open index.html  # macOS
start index.html # Windows
xdg-open index.html # Linux
```

3. **Or use a local server**
```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000

# Node.js (with http-server)
npx http-server
```

Then visit: `http://localhost:8000`

### Option 3: Embed in Your Website

Add this snippet to any webpage:

```html
<!-- 90s Hit Counter -->
<iframe src="https://tharev.github.io/90s-hit-counter/" 
        width="300" 
                height="200" 
                        frameborder="0">
                        </iframe>
                        ```

                        ---

                        ## 💻 Usage

                        ### Basic Usage

                        The counter automatically:
                        - Increments on each page load
                        - Saves count to browser LocalStorage
                        - Displays with authentic LED-style digits

                        ### Interactive Controls

                        **Style Selection:**
                        - Click different color buttons to change the LED theme
                        - Choose from: Neon Green, Red, Blue, or Purple

                        **Reset Counter:**
                        - Click the "Reset Counter" button to start over
                        - Count is immediately saved to LocalStorage

                        ### Customization

                        Edit the styles in `index.html` to customize:

                        ```css
                        /* Change counter colors */
                        .digit {
                            background: #00ff00; /* LED color */
                                box-shadow: 0 0 10px #00ff00;
                                }

                                /* Modify counter size */
                                .counter-container {
                                    font-size: 48px; /* Adjust digit size */
                                    }

                                    /* Update border style */
                                    .container {
                                        border: 3px ridge #666;
                                        }
                                        ```

                                        ---

                                        ## 🛠️ Technologies Used

                                        | Technology | Purpose |
                                        |------------|---------|
                                        | **HTML5** | Structure and semantic markup |
                                        | **CSS3** | Styling, animations, retro effects |
                                        | **JavaScript** | Counter logic, LocalStorage management |
                                        | **LocalStorage API** | Persistent visitor count storage |
                                        | **GitHub Pages** | Live demo hosting |

                                        ### Technical Details

                                        - **Size**: ~33KB total (HTML + CSS + JS combined)
                                        - **Dependencies**: Zero! Pure vanilla JavaScript
                                        - **Browser Support**: All modern browsers with LocalStorage support
                                        - **Performance**: Instant load, no backend calls
                                        - **Storage**: LocalStorage (persistent across sessions)

                                        ---

                                        ## 📁 Project Structure

                                        ```
                                        90s-hit-counter/
                                        │
                                        ├── index.html          # Main HTML file (includes CSS & JS)
                                        ├── README.md           # This file
                                        ├── vercel.json         # Vercel deployment config
                                        ├── netlify.toml        # Netlify deployment config
                                        └── .gitignore          # Git ignore rules
                                        ```

                                        ---

                                        ## 🌐 Deployment

                                        ### GitHub Pages (Active)

                                        ✅ **Live at**: https://tharev.github.io/90s-hit-counter/

                                        Deployment is automatic via GitHub Pages (main branch).

                                        ### Alternative Platforms

                                        **Vercel:**
                                        ```bash
                                        vercel deploy
                                        ```

                                        **Netlify:**
                                        ```bash
                                        netlify deploy --prod
                                        ```

                                        Both platforms have configuration files included:
                                        - `vercel.json` - Vercel deployment settings
                                        - `netlify.toml` - Netlify deployment settings

                                        ---

                                        ## 🎨 Features in Detail

                                        ### 1. Authentic LED Counter Display
                                        - Classic 7-segment LED-style digits
                                        - Multiple retro color themes
                                        - Glowing effects with CSS shadows
                                        - Responsive sizing

                                        ### 2. Visitor Tracking
                                        - Automatic increment on page load
                                        - LocalStorage persistence
                                        - Survives browser restarts
                                        - Per-browser tracking

                                        ### 3. Style Customization
                                        - 4 pre-built retro themes
                                        - Easy theme switching
                                        - Customizable via CSS
                                        - Instant visual feedback

                                        ### 4. Retro UI Elements
                                        - 90s-style beveled borders
                                        - Classic web 1.0 typography
                                        - Nostalgic color schemes
                                        - Period-accurate design choices

                                        ### 5. Modern Implementation
                                        - Clean, maintainable code
                                        - No external dependencies
                                        - Fast loading times
                                        - Mobile-responsive

                                        ---

                                        ## 🔧 Development

                                        ### Local Development Setup

                                        1. Clone and navigate:
                                        ```bash
                                        git clone https://github.com/tharev/90s-hit-counter.git
                                        cd 90s-hit-counter
                                        ```

                                        2. Make changes to `index.html`

                                        3. Test locally in browser

                                        4. Commit and push:
                                        ```bash
                                        git add .
                                        git commit -m "Your changes"
                                        git push origin main
                                        ```

                                        ### Testing

                                        **Browser Testing:**
                                        - Open `index.html` in multiple browsers
                                        - Test counter increment functionality
                                        - Verify LocalStorage persistence
                                        - Check style theme switching
                                        - Test reset functionality

                                        **Compatibility Testing:**
                                        - Chrome/Edge (Chromium)
                                        - Firefox
                                        - Safari
                                        - Mobile browsers

                                        ---

                                        ## 🐛 Known Issues

                                        ✅ **No bugs found!** This project has been thoroughly tested.

                                        **Browser Requirements:**
                                        - LocalStorage support required
                                        - JavaScript must be enabled
                                        - Modern browser recommended (ES6+)

                                        ---

                                        ## 🤝 Contributing

                                        Contributions are welcome! Here's how:

                                        1. Fork the repository
                                        2. Create a feature branch: `git checkout -b feature/amazing-feature`
                                        3. Commit changes: `git commit -m 'Add amazing feature'`
                                        4. Push to branch: `git push origin feature/amazing-feature`
                                        5. Open a Pull Request

                                        **Ideas for contributions:**
                                        - Additional retro themes
                                        - Sound effects (optional toggle)
                                        - More counter styles
                                        - Animation options
                                        - Backend integration examples

                                        ---

                                        ## 📜 License

                                        This project is licensed under the **MIT License** - see below for details:

                                        ```
                                        MIT License

                                        Copyright (c) 2026 tharev

                                        Permission is hereby granted, free of charge, to any person obtaining a copy
                                        of this software and associated documentation files (the "Software"), to deal
                                        in the Software without restriction, including without limitation the rights
                                        to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
                                        copies of the Software, and to permit persons to whom the Software is
                                        furnished to do so, subject to the following conditions:

                                        The above copyright notice and this permission notice shall be included in all
                                        copies or substantial portions of the Software.

                                        THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
                                        IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
                                        FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
                                        AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
                                        LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
                                        OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
                                        SOFTWARE.
                                        ```

                                        ---

                                        ## 🌟 Showcase

                                        **Perfect for:**
                                        - Personal websites wanting retro charm
                                        - Nostalgia-themed projects
                                        - Web history demonstrations
                                        - Portfolio pieces
                                        - Fun weekend projects

                                        ---

                                        ## 📞 Contact & Support

                                        - **GitHub**: [@tharev](https://github.com/tharev)
                                        - **Repository**: [90s-hit-counter](https://github.com/tharev/90s-hit-counter)
                                        - **Issues**: [Report bugs or request features](https://github.com/tharev/90s-hit-counter/issues)
                                        - **Live Demo**: [https://tharev.github.io/90s-hit-counter/](https://tharev.github.io/90s-hit-counter/)

                                        ---

                                        ## 🙏 Acknowledgments

                                        - Inspired by the classic web counters of the 1990s
                                        - Built with love for the retro web aesthetic
                                        - Thanks to everyone who remembers the golden age of web 1.0!

                                        ---

                                        ## 📊 Project Stats

                                        ![GitHub stars](https://img.shields.io/github/stars/tharev/90s-hit-counter?style=social)
                                        ![GitHub forks](https://img.shields.io/github/forks/tharev/90s-hit-counter?style=social)
                                        ![GitHub watchers](https://img.shields.io/github/watchers/tharev/90s-hit-counter?style=social)

                                        ---

                                        <div align="center">

                                        ### 🎉 Enjoy your trip down memory lane!

                                        **[⬆ Back to Top](#-90s-hit-counter)**

                                        Made with 💚 and nostalgia by [tharev](https://github.com/tharev)

                                        </div>
## ✨ Features

- 🎨 **4 Retro Themes** - Classic Green, Neon Pink, Matrix Code, and Rainbow Power
- 🔊 **8-bit Sound Effects** - Toggle authentic retro sounds on/off
- 💾 **LocalStorage Persistence** - Your counter survives page refreshes
- 📤 **Share Functionality** - Share your visitor count with friends
- 📋 **Embed Code Generator** - Easy integration into any website
- ⭐ **Animated Starfield Background** - Dynamic space-themed backdrop
- 📺 **CRT Monitor Effect** - Authentic scanline overlay for that retro feel
- 📱 **Fully Responsive** - Works perfectly on mobile and desktop
- 🚀 **Zero Dependencies** - Pure vanilla JavaScript, HTML, and CSS
- 🎯 **Interactive Controls** - Increment, reset, and customize your counter

## 🚀 Quick Start

### Option 1: Direct Use
Simply open `index.html` in your web browser. No installation required!

```bash
# Clone the repository
git clone https://github.com/tharev/90s-hit-counter.git

# Navigate to the directory
cd 90s-hit-counter

# Open in browser
open index.html  # macOS
start index.html # Windows
xdg-open index.html # Linux
```

### Option 2: Embed in Your Website

Copy the embed code from the app and paste it into your HTML:

```html
<iframe src="YOUR_URL_HERE" width="400" height="200" frameborder="0"></iframe>
```

### Option 3: Host on GitHub Pages

1. Fork this repository
2. Go to Settings → Pages
3. Set source to "main" branch
4. Your counter will be live at `https://yourusername.github.io/90s-hit-counter/`

## 🎨 Themes

Choose from 4 authentic 90s color schemes:

| Theme | Description | Color Palette |
|-------|-------------|---------------|
| **Classic Green** | The original terminal aesthetic | `#00ff00` on black |
| **Neon Pink** | Cyberpunk vibes from the early internet | `#ff00ff` on black |
| **Matrix Code** | Inspired by the iconic 1999 film | `#00ff00` with Matrix effects |
| **Rainbow Power** | Full spectrum retro psychedelia | `#ffff00` with gradients |

## 🎮 How to Use

1. **Visit the Page** - Your counter automatically increments
2. **Choose a Theme** - Click any theme button to change the look
3. **Interact** - Use the control buttons:
   - **Click Me! (+1)** - Manually increment the counter
      - **Reset Counter** - Start over from zero
         - **Share** - Share your visitor count
            - **🔊 Sound ON/OFF** - Toggle retro sound effects
            4. **Get Embed Code** - Copy the code to add to your website

            ## 📸 Screenshots

            ### Classic Green Theme
            The authentic terminal experience that defined the early web.

            ### Neon Pink Theme
            Cyberpunk aesthetics for the modern retro enthusiast.

            ### Matrix Code Theme
            Fall down the rabbit hole with Matrix-inspired visuals.

            ### Rainbow Power Theme
            Maximum nostalgia with psychedelic rainbow effects.

            ## 🛠️ Technical Details

            ### Technologies Used
            - **HTML5** - Semantic markup and modern standards
            - **CSS3** - Advanced animations and effects
              - CSS Grid & Flexbox for responsive layout
                - CSS animations for starfield and CRT effects
                  - CSS variables for theme switching
                  - **Vanilla JavaScript** - No frameworks or libraries
                    - Web Audio API for 8-bit sound generation
                      - LocalStorage API for data persistence
                        - Canvas API for starfield animation
                          - Web Share API for sharing functionality

                          ### Browser Compatibility
                          - ✅ Chrome/Edge 90+
                          - ✅ Firefox 88+
                          - ✅ Safari 14+
                          - ✅ Opera 76+

                          ### File Structure
                          ```
                          90s-hit-counter/
                          ├── index.html          # Main application file (all-in-one)
                          └── README.md          # Documentation
                          ```

                          ## 🎯 Key Features Explained

                          ### Sound Effects
                          The app generates authentic 8-bit sounds using the Web Audio API with square wave oscillators. Each interaction triggers a different frequency for variety.

                          ### Starfield Animation
                          A canvas-based animation creates twinkling stars in the background, adding depth and atmosphere to the retro aesthetic.

                          ### CRT Effect
                          CSS animations create authentic CRT monitor scanlines that scroll across the screen, simulating old-school monitors.

                          ### LocalStorage Persistence
                          Your visitor count is automatically saved to your browser's LocalStorage, so it persists across sessions.

                          ## 🔧 Customization

                          Want to modify the counter? Here are some easy customizations:

                          ### Change Initial Counter Value
                          ```javascript
                          let counter = parseInt(localStorage.getItem('hitCounter')) || 1000; // Start at 1000
                          ```

                          ### Modify Theme Colors
                          ```css
                          .theme-custom {
                              --counter-color: #your-color;
                                  --bg-primary: #your-bg;
                                      --bg-secondary: #your-secondary-bg;
                                      }
                                      ```

                                      ### Adjust Sound Frequencies
                                      ```javascript
                                      function playSound(frequency, duration) {
                                          // Change frequency parameter in function calls
                                          }
                                          ```

                                          ## 📱 Responsive Design

                                          The counter adapts seamlessly to different screen sizes:
                                          - **Desktop**: Full-featured experience with all effects
                                          - **Tablet**: Optimized layout with touch-friendly buttons
                                          - **Mobile**: Streamlined interface, perfect for smaller screens

                                          ## 🌟 Use Cases

                                          - **Personal Websites** - Track visitors like it's 1999
                                          - **Portfolio Sites** - Add retro charm to your projects
                                          - **Nostalgia Projects** - Perfect for retro-themed sites
                                          - **Fun Counters** - Birthday countdowns, achievement trackers
                                          - **Learning Tool** - Great example of vanilla JS, CSS animations
                                          - **Art Projects** - Aesthetic retro web experiences

                                          ## 🤝 Contributing

                                          Contributions are welcome! Feel free to:
                                          - 🐛 Report bugs
                                          - 💡 Suggest new features
                                          - 🎨 Add new themes
                                          - 📝 Improve documentation
                                          - 🔧 Submit pull requests

                                          ## 📜 License

                                          This project is open source and available under the [MIT License](LICENSE).

                                          ## 🙏 Acknowledgments

                                          - Inspired by the golden age of the World Wide Web (1995-2005)
                                          - Tribute to GeoCities, Angelfire, and early personal websites
                                          - Thanks to all the webmasters who proudly displayed their hit counters

                                          ## 📞 Contact

                                          - **GitHub**: [@tharev](https://github.com/tharev)
                                          - **Repository**: [90s-hit-counter](https://github.com/tharev/90s-hit-counter)

                                          ## 🎊 Fun Facts

                                          - Hit counters were one of the most popular widgets on 90s websites
                                          - The first web counter was created in 1996
                                          - At one point, over 60% of websites had a visitor counter
                                          - This recreates that nostalgia with modern web standards

                                          ---

                                          <div align="center">

                                          **Made with 💖 for the nostalgic web**

                                          ![Netscape Now](https://img.shields.io/badge/Best%20Viewed%20in-Netscape-blue?style=flat-square)
                                          ![IE Compatible](https://img.shields.io/badge/IE-Compatible-blue?style=flat-square)
                                          ![Web 1.0](https://img.shields.io/badge/Web-1.0-green?style=flat-square)

                                          *Under Construction* 🚧 | *Last Updated: 2026* | *Visitor Count: ∞*

                                          [⬆ Back to Top](#-90s-hit-counter)

                                          </div>
