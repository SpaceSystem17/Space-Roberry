**Script Description**

🎯 **Space Robbery** is a script designed to create an immersive store robbery experience for your FiveM servers. With seamless event and notification management, it features dynamic mechanics such as player interactions, police alerts, cooldown timers, and customizable rewards.

---

### **Key Features**

🔒 **Robbery Mechanics**
- Players can initiate a store robbery by pressing a specific key (`E`), provided they are armed.
- Each store requires a minimum number of police officers online to start the robbery, promoting coordinated and realistic gameplay.
- Safe-cracking animations enhance immersion during the robbery.

⏳ **Timer and Distance**
- Robberies include a customizable timer that shows how much time is left to complete the action.
- If a player strays too far from the store, the robbery is automatically canceled.

👮 **Police Notifications**
- A notification system alerts on-duty police officers when a robbery begins.
- A blip is added to the map, helping officers locate the robbed store.

💰 **Customizable Rewards**
- Players receive dirty money (`black_money`) upon successfully completing a robbery.
- Rewards and difficulty levels for each store can be configured to balance gameplay.

📡 **Cooldown System**
- Stores cannot be robbed again until the cooldown period is over, preventing abuse and maintaining server balance.

---

### **Configuration and Customization**
📁 **Configuration File (config.lua):**
- **Store Locations:** Fully customizable positions using `vector3`.
- **Rewards:** Each store can have unique rewards.
- **Cooldown:** Set the waiting time before a store can be robbed again.
- **Maximum Distance:** Define the maximum distance a player can travel before the robbery is canceled.
- **Required Police Officers:** Configurable for each store.

---

### **Discord Integration**
📩 **Event Logging**
- All major events are logged and sent to a Discord webhook, including:
  - Robbery started.
  - Robbery canceled due to distance.
  - Successful robbery completion.
- Logs include details such as the store name, player involved, and reward received.

---

### **Prerequisites**
- **ESX Framework:** Required for economic and player management systems.
- **ox_lib:** Used for advanced notifications, zones, and UI elements.

---

### **Commands and Interface**
- **Text UI:** Clear messages guide players during interactions (e.g., "Press **E** to start the robbery").
- **Visual Markers:** Indicators for robbery locations and zones.
- **Notifications:** Visual and audio alerts powered by `ox_lib`.

---

With **Space Robbery**, your server gains dynamic and engaging gameplay. Perfect for encouraging cooperation and challenges between players and police officers! 🚨🔫
