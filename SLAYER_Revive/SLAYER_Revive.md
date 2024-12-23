# SLAYER_Revive

This is **Configuration** file
```JSON
{
  "PluginEnabled": true,
  "revive_DrawBeacon": true,        // Draw Beacon when reviving
  "revive_DrawReviveSign": true,    // Draw a revive sign(particle) over dead body of players
  "revive_ReviveLimit": 2,            // How many times a Player can revive in a Round
  "revive_cost_mode": 0,            // Cost mode of revive? (0=Disabled, 1=Health, 2=Money, 3=Both)
  "revive_cost_health": 10,            // How much Health is taken away from reviver after he revives his teammate?
  "revive_cost_money": 1000,        // How much Money is taken away from Reviver after he revive his teammate?
  "revive_RevivedHealth": 100,        // After getting revived, what will be the health of that Player?
  "revive_timer_delay": 5,            // How many seconds is needed to revive a teammate?
  "revive_delay": 15,                // How many seconds of delay should be between each revive? (0=No Delay)
  "revive_distance": 150,            // Maximum Distance from the dead body of the teammate for reviving?
  "ConfigVersion": 1
}
```

This is **lang** file `en` translation
```JSON
{
    "Chat.Prefix":                    "{Gold}[{DarkRed}★ {Green}SLAYER Revive {DarkRed}★{Gold}]",
    "Chat.GettingRevived":            "{lime}You are getting revived by {gold}{0}",
    "Chat.ReviveDelay":               "{lime}You will be able to Revive again after {gold}{0} {lime}seconds!",
    "Chat.NotEnoughRevive":           "{DarkRed}You can't {lime}Revive {DarkRed}more teammates in this Round!",
    "Chat.NotEnoughMoney":            "{DarkRed}You don't have enough {lime}Money {DarkRed}to Revive your teammate! {Green}Need {gold}{0}",
    "Chat.NotEnoughHealth":           "{DarkRed}You don't have enough {lime}Health {DarkRed}to Revive your teammate! {Green}Need {gold}{0}",
    "CenterHtml.Reviving":            "<font color='red'>.:| </font> <font class='fontSize-l' color='lime'>Reviving:</font> <font class='fontSize-l' color='gold'>{0}</font> <font color='red'>|:.</font><br>"
}
```

Video:
https://www.youtube.com/watch?v=1S3Znymv8JE
