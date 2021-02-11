    // Autoexec configuration file
    // By Sandokan
    // Last update 25-01-2021
    
    // Binds
    bind l "say GL & HF"
    bind o "say Buena suerte hf"
    bind p kill
    bind "h" "toggle gameinstructor_enable"
    bind i "say twitch.tv/kufisandokan"
    
    // Bind foto
    bind "F5" "jpeg"
    
    // Aceleration and position
    cl_showpos 1
    
    // Bind Saltos
    //bind mwheelup +jump;
    //bind mwheeldown +jump;
    //bind space +jump
    
    // Bind configuración del mouse
    bind mwheelup +jump
    bind mwheeldown "slot3"
    bind "MOUSE5" "slot1"
    bind "MOUSE4" "slot4"
    
    // Bind slots primeros granadas
    //bind 1 "slot6"
    //bind 2 "slot7"
    //bind 3 "slot8"
    //bind 4 "slot10"
    //bind 5 "slot5"
    //bind 6 "slot9"
    
    // Bind armas numeros normal
    bind 1 "slot1"
    bind 2 "slot2"
    bind 3 "slot3"
    bind 4 "slot4"
    bind 5 "slot5"
    bind 6 "slot6"
    bind 7 "slot7"
    bind 8 "slot8"
    bind 9 "slot9"
    
    
    
    Bind t +spray_menu // Spray menu
    
    // Bind granadas no usado
    //bind "MOUSE5" "slot4"
    
    // Bind jumpthrow
    alias "+jumpthrow" "+jump;-attack"; alias "-jumpthrow" "-jump"; bind "alt" "+jumpthrow"
    
    
    // Fastswitch
    alias "+knife" "slot3"
    alias "-knife" "lastinv"
    bind "q" "+knife"
    
    
    // Local server tick rate 
    tickrate 128 
    
    // Set rates according to your internet connection 
    rate 786432 
    
    // Radar settings
    cl_radar_scale 0.5
    cl_radar_rotate 1
    cl_radar_always_centered 0
    cl_radar_icon_scale_min 0.4
    
    // All the essential settings 
    fps_max 0 
    con_enable 1 
    gameinstructor_enable 0 
    cl_disablefreezecam 1 
    cl_disablehtmlmotd 1 
    cl_autowepswitch 0 
    cl_forcepreload 0 
    cl_join_advertise 2 
    lobby_default_privacy_bits2 1 
    bind w +forward; r_cleardecals 
    unbind i; cl_showloadout 1
    
    // Hud 
    hud_showtargetid 1 // Shows enemy name on screen
    cl_hud_bomb_under_radar 1 
    cl_hud_playercount_showcount 0 
    cl_hud_healthammo_style "0" // show HP and ammo without bars and bullet icons
    cl_hud_playercount_pos "0" // Position for the playercount on screen
    cl_hud_playercount_showcount "1" // forces show all players in the player count
    cl_hud_color 3 // Changes UI Color for HUD HP, Ammo, Money etc
    cl_hud_background_alpha "0.5" // Adjust HUD background alpha for colored elements
    cl_hud_bomb_under_radar "1" // shows bomb icon under radar instead of inventory 
    
    cl_cmdrate 128 
    cl_updaterate 128 
    cl_interp 0.007813 
    cl_interp_ratio 1 
    cl_lagcompensation 1 
    cl_predict 1 
    cl_predictweapons 1 
    
    // Mouse config
    m_rawinput 1
    m_customaccel 0 
    m_mousespeed 0
    sensitivity "0.99"
    zoom_sensitivity_ratio_mouse "0.818933027098955175"
    
    // Graphics / Models Options
    viewmodel_fov "68"
    viewmodel_offset_x "2"
    viewmodel_offset_y "2"
    viewmodel_offset_z "-2"
    cl_viewmodel_shift_left_amt "0"
    cl_viewmodel_shift_right_amt "0"
    cl_bob_lower_amt "0"
    cl_bobamt_lat "0"
    cl_bobamt_vert "0"
    cl_bobcycle "2"
    
    // Show equipment team
    cl_teamid_overhead_always 1
    +cl_show_team_equipment
    
    // Enable netgraph stats under scoreboard 
    net_graph 1 
    net_graphpos 1
    net_graphproportionalfont 0 
    
    // Switch all music off except 10s round end warning 
    snd_musicvolume "0" 
    snd_deathcamera_volume 0 
    snd_mapobjective_volume 0 
    snd_menumusic_volume 0 
    snd_roundend_volume 0 
    snd_roundstart_volume 0 
    snd_tensecondwarning_volume 0.1 
    
    // Switch Hand weapon
    cl_righthand 0
    
    // Crosshair details
    cl_crosshairstyle 4 // Tipo de crosshair
    cl_crosshair_t 0 // Crosshair con rallita top
    cl_crosshairgap_useweaponvalue 0 // Croshair don't change with weapon
    cl_crosshaircolor 1 // Crosshair verde
    cl_crosshairsize 2 // Tamaño del crosshair
    cl_crosshairthickness 1 // Grossor del crosshair
    cl_crosshairgap -2 // Distancia entre las lineas del crosshair desde el centro
    cl_crosshairdot 0 // Sin punto en medio
    
    
    
    // EOF
    host_writeconfig
    
    echo "Sandokan CFG loaded"
