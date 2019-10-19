# TeleDark
Pokemon Go Telegram sticker pack for PokeAlarm/PoracleJS

# How To Use

**PokeAlarm** (Pokemon/Eggs/Raids only / dev-branch only atm)

Use '[sticker_url](https://pa.readthedocs.io/en/master/configuration/alarms/telegram.html#advanced-config)' 

`https://raw.githubusercontent.com/darkelement1987/TeleDark/master/PogoAssets/pokemon_icon_<mon_id_3>_<form_id_2>.webp`

`Example alarms.json`


```json
  "telegram_halloween":{
    "active":true,
    "type":"telegram",
    "bot_token":"111111111:AAAAAAAAAAAAAAAAAAA",
    "chat_id":"-111111111111",
    "startup_message":false,
    "monsters":{
        "sticker_url":"https://raw.githubusercontent.com/darkelement1987/TeleDark/master/PogoAssets/pokemon_icon_<mon_id_3>_<form_id_2>.webp",
        "message":"*A wild <mon_name> (#<mon_id_3>) has appeared!*\nIV: <iv>% / CP: <cp> / LVL: <mon_lvl>\nStats: (Att: <atk> / Def: <def> / Sta: <sta>)\n<address_eu> until <24h_time> (<time_left>).",
        "map":true
    }```

**PoracleJS** (Supports Pokemon / Raids / Eggs / Quests)

In your .env use:

`TLG_STICKER=https://raw.githubusercontent.com/darkelement1987/TeleDark/master/PogoAssets/`

# Credits 
ZeChrales, LucianoNeo, mizu-github, Ken Sugimori, 123FLO321, Furtif, PoracleJS & PokeAlarm team

# Disclaimer
There might be some forms missing in /PogoAssets/ but it should be 99.9% up to date.
Make Issue / PR to add or fix stuff please :-)
