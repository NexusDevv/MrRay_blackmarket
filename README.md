[README.md](https://github.com/user-attachments/files/23262528/README.md)
# MrRay Blackmarket

**Advanced Multi-Functional Black Market NUI for QBox Framework**

Developed by **Nexus-development** by **MrRay**

---

## Features

🎯 **Modern UI Design**
- Glassmorphism interface with smooth animations
- Responsive design with Tailwind CSS
- Professional gradient effects and transitions

🖼️ **Authentic Weapon Images**
- Integration with ox_inventory for official GTA V weapon images
- Smart fallback system for custom images
- Automatic image loading for all standard weapons

⚡ **Advanced Functionality**
- Multi-category item organization (Weapons, Melee, Ammo, Attachments)
- Quantity selection for ammunition
- Real-time price formatting
- Job-based access control

🔧 **Technical Excellence**
- QBox Framework compatibility
- ox_lib integration
- Optimized NUI performance
- Clean, maintainable code structure

---

## Installation

1. **Dependencies**: Ensure you have `ox_lib` and `ox_inventory` installed
2. **Extract**: Place the `MrRay_blackmarket` folder in your resources directory
3. **Configure**: Edit `config.lua` to customize items, prices, and locations
4. **Start**: Add `ensure MrRay_blackmarket` to your server.cfg

---

## Configuration

### Basic Setup
```lua
-- Command to open the market
Config.OpenCommand = 'blackmarket'

-- Pedestrian location and model
Config.Ped = {
    model = 's_m_y_dealer_01',
    coords = vector4(-844.25, -32.33, 44.35, 121.88)
}
```

### Adding Items
```lua
Config.Weapons = {
    { item = 'weapon_pistol', label = 'Pistol', price = 20000 },
    -- Add more weapons...
}
```

---

## Commands

- `/blackmarket` - Opens the black market interface (configurable)

---

## Job Access

The blackmarket requires specific job access. Configure job permissions in your framework settings.

---

## Support

For support, updates, or custom development:

**Contact**: MrRay  
**Organization**: Nexus-development (https://discord.gg/nFZ4J9wr)


---

## License

© 2024 **Nexus-development** by **MrRay**. All rights reserved.

This resource is developed and maintained by Nexus-development. Unauthorized redistribution or modification without permission is prohibited.

---

*Thank you for using MrRay Blackmarket! 🚀*
