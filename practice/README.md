# How to use

1. Copy the .cfg file to your CS:GO directory, on folder `csgo/cfg`. For example:

    ```bash
    C:\Program Files\Steam\steamapps\common\Counter-Strike Global Offensive\csgo\cfg
    ```

2. Open the game and choose any map you like

3. On Console, type `exec` and the name of cfg file. For example:

    ```bash
    exec treino
    ```

4. Enjoy!

## Easy copy

### treino

```bash
sv_cheats 1;
sv_regeneration_force_on 1;
mp_limitteams 0;
mp_autoteambalance 0;
mp_roundtime 60;
mp_roundtime_defuse 60;
mp_maxmoney 60000;
mp_startmoney 60000;
mp_freezetime 0;
mp_buytime 9999;
mp_buy_anywhere 1;
sv_infinite_ammo 1;
ammo_grenade_limit_total 5;
bot_kick;
mp_warmup_end;
sv_grenade_trajectory 1;
sv_grenade_trajectory_time 10;
sv_showimpacts 1;
sv_showimpacts_time 10;
```

### withBots

```bash
mp_limitteams 0;
mp_autoteambalance 0;
mp_buytime 9999;
mp_buy_anywhere 1;
sv_infinite_ammo 1;
bot_allow_grenades 0;
```
