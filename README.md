# Preston Slides

A Claude Code skill for creating professional HTML presentation slides in the Legacy Investing Show brand style.

## Installation

### Option 1: Install the packaged skill (Recommended)

```bash
claude skills install ./preston-slides.skill
```

### Option 2: Install from GitHub

```bash
claude skills install https://github.com/Deveshwy/preston-slides
```

### Option 3: Manual setup

Copy the `preston-slides` folder to your Claude skills directory:

```bash
cp -r preston-slides ~/.claude/skills/
```

## Usage

Once installed, invoke the skill in Claude Code:

```
/preston-slides
```

Or mention it naturally:

> "Create slides for a presentation about tax optimization strategies"

The skill will trigger on keywords like:
- "create slides"
- "make a presentation"
- "Preston slides"
- "Legacy slides"
- "pitch deck"

## What's Included

- **8 slide styles**: Hero, Stats Grid, Floating Cards, Horizontal Cards, Numbers Strip, Comparison, Airbnb Context, Brokerage Context
- **Brand guidelines**: Color palette, typography, design principles
- **HTML template**: Ready-to-use template at `preston-slides/assets/template.html`

## Color Palette

| Color | Hex | Usage |
|-------|-----|-------|
| Dark Green | `#0f4c3a` | Primary brand, headers |
| Light Green | `#1a7a5e` | Secondary accents |
| Gold | `#d4af37` | Highlights, CTAs |
| Off-White | `#fafafa` | Light backgrounds |
| Near-Black | `#1a1a1a` | Dark text |
| Red | `#c53030` | Negative comparisons |

## Typography

- **Headlines**: Playfair Display (serif)
- **Body**: Inter (sans-serif)
