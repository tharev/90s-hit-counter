# 90s-hit-counter
🔢 Nostalgic 90s-style hit counter with modern features - Bring back the glory days of web 1.0!# 🔢 90s Hit Counter

![90s Hit Counter Banner](https://img.shields.io/badge/90s-Hit%20Counter-purple?style=for-the-badge)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Retro](https://img.shields.io/badge/Style-Retro-ff00ff?style=for-the-badge)

> **🎮 Welcome to the World Wide Web!** Relive the golden age of the internet with this nostalgic 90s-style hit counter. Remember when every website proudly displayed their visitor count? Now you can bring back that retro charm with modern features!

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
