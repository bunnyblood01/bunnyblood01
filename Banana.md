getgenv().Setting = {
    ["Team"] = "Marines", --Marines,Pirates
    ["Webhook"] = {
        ["Enabled"] = false,
        ["Url Webhook"] = "", --Your Url
    },
    ["Misc"] = {
        ["AutoBuyRandomandStoreFruit"] = true,
        ["AutoBuySurprise"] = false,
    },
    ["Click"] = {
        ["Enable"] = true,
        ["Click Gun"] = true,
        ["OnLowHealthDisable"] = false,
        ["LowHealth"] = 5000,
    },
    ["SafeZone"] = {
        ["Enable"] = true,
        ["LowHealth"] = 5000,
        ["MaxHealth"] = 8000,
        ["Teleport Y"] = 1000
    },
    ["Race V4"] = {
        ["Enable"] = true,
    },
    ["Invisible"] = true,
    ["White Screen"]  =false,
    ["GunMethod"] = true, --Support Only Melee And Gun,Not Invisible, Turn On Enabled Gun and Melee Please
    ["SpamSkill"] = true, -- Will use all skills as fast as possbile ignore holding skills
    ["Weapons"] = {
        ["Melee"] = {
            ["Enable"] = true,
            ["Delay"] = 2,
            ["Skills"] = {
                ["Z"] = {
                    ["Enable"] = true,
                    ["HoldTime"] = 0,
                },
               [ "X"] = {
                    ["Enable"] = true,
                    ["HoldTime"] = 0,
                },

                ["C"] = {
                    ["Enable"] = true,
                    ["HoldTime"] = 0,
                },
            },
        },
        ["Blox Fruit"] = {
            ["Enable"] = true,
            ["Delay"] = 3,
            ["Skills"] = {
                ["Z"] = {
                    ["Enable"] = false,
                    ["HoldTime"] = 2,
                },
                ["X"] = {
                    ["Enable"] = true,
                    ["HoldTime"] = 0,
                },

                ["C"] = {
                    ["Enable"] = false,
                    ["HoldTime"] = 0,
                },
                ["V"] = {
                    ["Enable"] = true,
                    ["HoldTime"] = 0,
                },
                ["F"] = {
                    ["Enable"] = false,
                    ["HoldTime"] = 0,
                },
            },
        },
        ["Gun"] = {
            ["Enable"] = true,
            ["Delay"] = 2,
            ["Skills"] = {
                ["Z"] = {
                    ["Enable"] = true,
                    ["HoldTime"] = 1,
                },
                ["X"] = {
                    ["Enable"] = true,
                    ["HoldTime"] = 0,
                },
            },
        },
        ["Sword"] = {
            ["Enable"] = true,
            ["Delay"] = 1,
            ["Skills"] = {
                ["Z"] = {
                    ["Enable"] = true,
                    ["HoldTime"] = 1,
                },
                ["X"] = {
                    ["Enable"] = true,
                    ["HoldTime"] = 0,
                },
            },
        },
    }
}
loadstring(game:HttpGet("https://raw.githubusercontent.com/obiiyeuem/vthangsitink/main/BountyShit.lua"))()
