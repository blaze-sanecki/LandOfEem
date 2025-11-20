# Land Of Eem - Roll20 Character Sheet
<img src="https://raw.githubusercontent.com/blaze-sanecki/LandOfEem/main/images/logo-flat.png" alt="Land of Eem Logo" width="228">

## Features

- **Custom design** matching the Land of Eem aesthetic
- **Tab navigation** for organized character management
- **Interactive rolls** with advantage/disadvantage support
- **Auto-Recalculation** of abilities and stats when changing related attributes
- **Roll modifier validation** (total modifier clamped to -3 and +3)
- **Full Multi-language support** with English and Polish already implemented

## Instructions

### Interactive Elements

#### Character Header
- **Name & Pronouns, Folk, Homeland**: Simple text inputs for basic character information
- **Class**: Text input with suggested values. Can reset Courage and Dread to class defaults when changed (a prompt will be displayed)
- **Level (LV) and Experience (XP)**: Number-only inputs

#### Tab Navigation
- **Attributes**: Attributes, stats, abilities, proficiencies, deficiencies, status, heroic titles
- **Inventory**: Equipment, crafting materials, coins, and rations
- **Background**: Ideals, flaws, personal quest, relationships, and backstory
- **Journal**: General notes section

#### Attributes Tab

**Making a Roll**
- Click on attribute, ability or stat name label to make a roll. Rollable elements will be underlined when you hover them.
- Popup dialog will appear and let you apply Advantage or Disadvantage
- Popup dialog will let you adjust the modifier (**IMPORTANT**: entered value needs to start with a "+" or a "-")
- Calculated final modifier is clamped to -3 and +3 range and the roll result is displayed in the chat.
- You can still see the uncapped modifier when you hover over the roll result in the chat if needed.

## Development

### Technologies Used
- HTML5 with Roll20 sheet worker API
- CSS3 with custom properties and polygon clip-paths
- JavaScript (ES6+) for interactive functionality
- SVG for some of the visual elements

## Credits

**Character Sheet Created by**: Blaze Sanecki  
**Land of Eem Created By**: Ben Costa & James Parks  
**Official Land of Eem Website**: [landofeem.com](https://landofeem.com/)

This is an unofficial fan-made sheet created with the official blessing of the Land of Eem creators.

## License

This character sheet is a fan work created for use with The Land of Eem tabletop RPG. All Land of Eem intellectual property belongs to Ben Costa & James Parks.

## Version

Current Version: 1.0.0
