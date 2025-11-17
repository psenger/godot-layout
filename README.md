# Godot Layout

A Godot Engine 4.5 demonstration project showcasing various UI layout techniques and container systems.

## Overview

This project serves as a reference and learning resource for implementing different UI layouts in Godot. It demonstrates how to use anchors, containers, and various UI control nodes to create responsive and well-structured user interfaces.

## Features

### Layout Examples

The project includes multiple scene files, each demonstrating specific layout patterns:

- **centerleft.tscn**: Left-aligned UI positioned at the vertical center
- **centercenter.tscn**: Centered UI elements in the middle of the screen
- **centerright.tscn**: Right-aligned UI positioned at the vertical center
- **centerbottom.tscn**: Bottom-aligned UI elements

### Container Demonstrations

- **handvbox.tscn**: A comprehensive example featuring:
  - VBoxContainer and HBoxContainer usage
  - MarginContainer for spacing
  - CenterContainer for alignment
  - ScrollContainer for scrollable content
  - Custom themes and styled buttons
  - Game menu UI patterns (title, buttons, checkboxes)

### Additional Components

- **healthbar.tscn**: Minimal health bar component
- **parentchild.tscn**: Parent-child node relationship examples
- **theme.tres**: Custom theme resource for consistent UI styling
- **main.tscn**: Main scene that integrates all layout examples

## Technical Details

- **Engine Version**: Godot 4.5
- **Rendering Mode**: Forward Plus
- **Window Size**: 1920 x 740
- **Display Mode**: Windowed (mode=1)
- **Texture Filtering**: Pixel-perfect (nearest neighbor)

## Getting Started

1. Clone or download this repository
2. Open the project in Godot 4.5 or later
3. Run the main scene (main.tscn) to see the layout examples
4. Explore individual scene files to study specific layout techniques

## Project Structure

```
godot-layout/
├── main.tscn              # Main scene
├── centerleft.tscn        # Left-aligned layout
├── centercenter.tscn      # Center-aligned layout
├── centerright.tscn       # Right-aligned layout
├── centerbottom.tscn      # Bottom-aligned layout
├── handvbox.tscn          # Complex container example
├── healthbar.tscn         # Health bar component
├── parentchild.tscn       # Parent-child demo
├── theme.tres             # Custom UI theme
├── project.godot          # Project configuration
└── icon.svg               # Project icon
```

## Learning Resources

Each scene file can be opened in the Godot editor to examine:
- Node hierarchy and structure
- Anchor and offset settings
- Container configurations
- Theme overrides and styling
- Layout behavior and responsiveness

## Use Cases

This project is useful for:
- Learning Godot UI/UX design patterns
- Understanding container-based layouts
- Implementing responsive game menus
- Creating pixel-perfect UI elements
- Studying anchor-based positioning

## License

This is a demonstration project intended for educational purposes.
