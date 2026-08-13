# HerobrineAI-By-Lolgame52
Adaptive Horror Engine plugin for Minecraft Spigot/Paper 1.20.1+

═══════════════════════════════════════════════════════════════
  HerobrineAI: Adaptive Horror Engine
═══════════════════════════════════════════════════════════════

HerobrineAI is an advanced plugin for creating adaptive horror encounters with Herobrine. Unlike simple plugins that use signs and chat messages, this one uses artificial intelligence that learns from player behavior and adapts its tactics in real time.

📦 Requirements:
• Citizens (for NPC creation) – https://ci.citizensnpcs.co/job/citizens2/3208/artifact/dist/target/Citizens-2.0.32-b3208.jar
• Spigot/Paper/Purpur 1.20.1+

═══════════════════════════════════════════════════════════════
✨ KEY FEATURES
═══════════════════════════════════════════════════════════════

🧠 ADAPTIVE ARTIFICIAL INTELLIGENCE
-----------------------------------
• SQLite database for storing player behavior
• Three AI learning modes:
  - LOW: 55 seconds between decisions (slow learning)
  - MEDIUM: 35 seconds between decisions (balanced)
  - HIGH: 20 seconds between decisions (aggressive learning)
• Remembers each player's history
• Adapts encounter tactics based on player reactions

👁️ EIGHT ENCOUNTER TYPES
-------------------------
Each encounter has a configurable weight and trigger chance:

1. STALKING
   • Herobrine appears 12-25 blocks away
   • Silently stares at the player for up to 18 seconds
   • Disappears if the player looks away or approaches

2. ATTACK
   • 3-4 hits, each dealing 3 damage
   • Increased movement speed
   • Actively chases the target

3. SCREAM
   • Freezes the player's gaze on Herobrine
   • Creates a forced-watching effect
   • Accompanied by a sound effect

4. DOOR OPENING
   • Automatically opens doors when the player approaches
   • Creates a feeling of being watched

5. WINDOW APPEARANCE
   • Suddenly appears in building windows
   • Quickly vanishes when spotted

6. LIGHTNING
   • Strikes lightning without causing fire
   • Can strike near the player

7. REDSTONE TORCHES
   • Places redstone torches around the player
   • Creates an eerie atmosphere

8. LEAF CARVING
   • Removes leaves from trees, leaving dead trunks
   • Temporarily alters the landscape

🌍 WORLD CONTROL
-----------------
• Forces time to night
• Forces a thunderstorm
• Blocks sleeping in beds
• Creates a tense atmosphere

⚙️ COMMANDS
------------
/hb start <player>       - Start AI for a player
/hb stop <player>        - Stop AI for a player
/hb attack <player>      - Immediately attack a player
/hb scream <player>      - Scream at a player
/hb target <player> <time> - Make a player the target for a duration
/hb targetrandom <time>  - Random target for a duration
/hb playertext <player> <text> - Send a message from Herobrine to a player
/hb status               - Check AI status and current targets
/hb reload               - Reload configuration

🔒 SECURITY
-----------
• Does not load new chunks (works only in already loaded ones)
• Requires solid ground beneath the NPC
• Full damage cancellation to Herobrine himself
• Automatically removes all Herobrine NPCs when the plugin unloads
• Does not affect server performance

📋 CONFIGURATION (config.yml)
-----------------------------
Fully customizable parameters:
• AI mode (LOW/MEDIUM/HIGH)
• Weight and chance for each encounter type
• Stalking and attack distances
• Damage and number of hits
• Ability radii
• Sound effects and their volume
• World control (night, thunder, sleep)
• Russian language messages (messages.yml)

═══════════════════════════════════════════════════════════════
📦 BUILD INFORMATION
═══════════════════════════════════════════════════════════════

Version: 1.0.0
Build: FIXED-20260731
Author: lolgame52
Compatibility: Spigot/Paper/Purpur 1.20.1+

═══════════════════════════════════════════════════════════════

⚠️ NOT APPROVED OR ASSOCIATED WITH MOJANG OR MICROSOFT
