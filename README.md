# 🍔 Animated CSS Hamburger

An interactive hamburger animation built with pure HTML and CSS. When hovered, each layer of the burger comes to life with unique animations.

## ✨ Features

- Pure CSS animations - no JavaScript required
- Interactive hover effects for each burger layer
- Sesame seed animations on the top bun
- Wiggling patty and tomato
- Moving lettuce texture
- Dancing pickles
- Dripping cheese effect
- Responsive design for various screen sizes

## 🎨 Styling

The burger uses CSS variables for easy color customization:
```css
:root {
  --tomato: #f03a17;
  --pickles: #13a10e;
  --bun: #eba300;
  --lettuce: #13a10e;
  --cheese: #ffc83d;
  --darker-cheese: #ffba0a;
  --patty: #8e562e;
}
```

## ## ⚙️ Getting Started

To view and interact with the animated burger button:

1. Download the project files.
2. Open the `index.html` file in Visual Studio Code.
3. Use the Live Server extension in VS Code to view the project in your web browser.


## 💻 Technologies Used

- HTML5
- CSS3 (with animations and keyframes)
- Google Fonts (Roboto)

## 🔍 How It Works

The hamburger is structured as a button containing spans for each burger component:
- Top and bottom bun layers
- Lettuce with radial gradient texture
- Tomato slice
- Pickle slices
- Cheese (with dripping animation)
- Beef patty

Each layer has unique hover effects using CSS transitions and keyframe animations:
- Sesame seeds rotate on the top bun
- Lettuce texture moves horizontally
- Tomato and patty wiggle
- Pickles slide side to side
- Cheese drips more prominently

## 📱 Responsive Design

The burger adjusts for smaller screens with a media query for screens under 600px width.

## 🎮 Usage

Feel free to incorporate this animated burger into your own projects! It works great as a:
- Fun interactive element
- Loading animation
- Menu button alternative
- Design showcase


## 🔄 Animations

The burger button features various CSS animations that activate on hover and click events. Here’s an overview:

- **Bun**: Animates with a rotation effect.
- **Lettuce**: Animates with a sliding effect.
- **Tomato**: Wriggles slightly.
- **Pickles**: Switch positions.
- **Cheese**: Rotates dynamically.
- **Patty**: Wriggles slightly.
