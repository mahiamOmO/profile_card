# Profile Card - Glass LinkedIn Badge

A stunning, interactive 3D profile card with a glassmorphism design and animated Three.js background. Display your professional profile with a modern, eye-catching UI.

## Features

✨ **Glass Morphism Design** - Modern frosted glass effect with blur and transparency
- Gradient glass background with subtle glow effects
- Semi-transparent borders and backdrop blur
- Smooth shadow layering for depth

🎨 **Immersive 3D Scene** - Powered by Three.js
- Auto-rotating environment with interactive controls
- Dynamic particle effects
- Floating animated side chips
- Glowing ring background element
- Realistic lighting with hemisphere and directional lights

📱 **Responsive Layout**
- Centered card UI that adapts to screen size
- Mobile-friendly design
- Smooth animations and transitions

🎭 **Interactive Elements**
- Custom avatar with gradient border and glow
- Connect button with gradient background
- GitHub icon button with hover effects
- Social stats and connection metrics
- Animated pulse indicator for followers

🎬 **Smooth Animations**
- Auto-rotating 3D scene
- Floating card movement
- Chip animations
- Ring rotation
- Responsive to viewport changes

## Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Glassmorphism styles, gradients, and animations
- **Three.js** - 3D scene rendering and graphics
- **Vanilla JavaScript** - Scene management and interactions

## Customization

### Update Profile Information
Edit the following in `profile.html`:
- **Avatar**: Replace `profile_image.png` with your image
- **Name**: Change "Mahia Akter Momo"
- **Role**: Update "AI Data Annotation & Quality Intern @Agency Handy"
- **Followers**: Modify follower count
- **Stats**: Update connections and profile views
- **Links**: Replace LinkedIn and GitHub URLs

### Customize Colors
Modify CSS variables in `:root`:
```css
:root {
  --accent: #4fc3f7;      /* Primary accent color */
  --accent2: #7c4dff;     /* Secondary accent color */
  --text: #eaf2ff;        /* Text color */
  --bg: #05070f;          /* Background color */
  --bg2: #0f172a;         /* Secondary background */
}
```

### Adjust 3D Scene
- **Camera angle**: Modify `card.rotation.x` and `card.rotation.y`
- **Animation speed**: Change `autoRotateSpeed` value
- **Particle count**: Adjust the `count` variable in particle generation
- **Lighting**: Modify light positions and intensities

## Usage

1. Clone or download this repository
2. Open `profile.html` in your web browser
3. Customize profile information and colors as needed
4. Replace `profile_image.png` with your profile photo

## Browser Compatibility

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Requires WebGL support for 3D rendering

## File Structure

```
profile_card/
├── profile.html      # Main profile card component
├── profile_image.png # Profile avatar image
└── README.md         # This file
```

## License

This project is open source and available for personal and professional use.

## Author

Created by [Mahia Akter Momo](https://github.com/mahiamOmO)

---

⭐ Feel free to star this repo if you find it useful!
