# 

```python
# !/usr/bin/env python3
# -*- coding: utf-8 -*-

"""
  .___            .__    .__  __                                    
  ________ __  __| _/______  _  _|  |__ |__|/  |_  ___________  ____  ______ ____  
 /  ___/  |  \/ __ |/  _ \ \/ \/ /  |  \|  \   __\/ __ \_  __ \/  _ \/  ___// __ \ 
 \___ \|  |  / /_/ (  <_> )     /|   Y  \  ||  | \  ___/|  | \(  <_> )___ \\  ___/ 
/____  >____/\____ |\____/ \/\_/ |___|  /__||__|  \___  >__|   \____/____  >\___  >
     \/           \/                  \/              \/                 \/     \/
"""

class SudoWhite:
    def __init__(self):
        self.username = "sudowhite"
        self.role = "Software Engineer & Tech Enthusiast"
        
        # System Information
        self.os = "Human OS x86_64 / Arch Linux"
        self.kernel = "Linux 6.12.0-sudowhite-core"
        self.shell = "zsh"
        self.wm_de = ["Hyprland", "Neovim"]
        
        # Stats
        self.uptime = "24 years, 7 months"
        self.memory_gb = {"used": 14.2, "total": 32.0}
        self.packages = {
            "active_repos": 73,
            "coffee_cups": 404
        }

    def get_tech_stack(self) -> list[str]:
        return [
            "Python", 
            "Go", 
            "Docker", 
            "Linux / Bash",
            "Git / GitHub Actions"
        ]

    def terminal_palette(self) -> str:
        return "🔴 🟢 🟡 🔵 🟣 🟤 ⚪"

if __name__ == "__main__":
    me = SudoWhite()
    print(f"Initializing connection to {me.username}...")
```
