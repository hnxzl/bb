# 🎠 Card Carousel Implementation

## ✨ New Feature: Spotify-style Card Slider

Setelah intro selesai, website akan menampilkan **carousel card slider** yang cute & modern!

### 🎨 Design Features:

**Visual Style:**

- ✅ Glassmorphism cards (frosted glass effect)
- ✅ Pastel gradient background (animated)
- ✅ 3D perspective with card rotation
- ✅ Smooth transitions & animations
- ✅ Card number badge (01, 02, 03, 04)
- ✅ Gradient text headings

**Navigation:**

- ✅ **Next/Previous buttons** (arrows) - like Spotify
- ✅ **Dot indicators** (active dot with gradient)
- ✅ **Swipe support** for mobile (left/right)
- ✅ **Keyboard arrows** (←/→) for desktop
- ✅ **Click dots** to jump to specific card

### 🎯 Flow:

1. **Intro** (countdown + typing message)
2. Click anywhere to continue
3. **Carousel appears** with first card active
4. Navigate with:
   - Click **→** for next card
   - Click **←** for previous card
   - Click **dots** to jump
   - **Swipe left/right** on mobile
   - Press **arrow keys** on desktop

### 📱 Responsive:

- **Desktop**: Full 3D effect with perspective
- **Tablet**: Slightly smaller cards
- **Mobile**: Touch-optimized, smaller controls

### 🎨 Card States:

- **Active card**: Center, full opacity, scale 1, no rotation
- **Next card**: Right side, 50% opacity, scaled 0.8, rotated 20deg
- **Previous card**: Left side, 50% opacity, scaled 0.8, rotated -20deg

### 🎁 Card Contents:

Each card shows complete gift content:

- Card number badge (top-right)
- Gift title
- Description
- Photos (for Hadiah 2 & 4)
- Videos (portrait for Hadiah 1 & 2, landscape for Hadiah 3)
- Chat tabs (Hadiah 2)

### 💡 Features:

1. **Smooth transitions**: 0.6s cubic-bezier for buttery smooth animations
2. **Scroll within cards**: Content scrollable if too long
3. **Disabled state**: Prev button disabled on first card, Next disabled on last card
4. **Active indicators**: Current card shown via glowing dot
5. **Hover effects**: Buttons scale up on hover

### 🎨 Color Palette:

- Background: Animated pastel gradient (pink, yellow, purple)
- Cards: Translucent white with backdrop blur
- Buttons: Glassmorphism style
- Active dot: Magic gradient (matches theme)
- Text: Gradient (pink → purple)

### 🚀 Performance:

- CSS transforms (GPU-accelerated)
- Smooth 60fps animations
- Optimized transitions
- Lazy loading for images

---

**Made with 💕 by your AI assistant**
