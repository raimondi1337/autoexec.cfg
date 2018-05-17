// Rates
rate "307200"
cl_cmdrate "128"
cl_updaterate "128"
cl_interp "0.0"
cl_interp_ratio "1"
cl_interpolate "1"
cl_lagcompensation "1"
net_client_steamdatagram_enable_override "1" // SDR beta

// Mouse
sensitivity "1.48"
zoom_sensitivity_ratio_mouse "1.0"
m_rawinput "1"
m_pitch "0.022"
m_customaccel "0"
m_mouseaccel1 "0"
m_mouseaccel2 "0"
m_mousespeed "0"
cl_scoreboard_mouse_enable_binding "+attack2"

// Video
mat_monitorgamma "1.6"
mat_queue_mode "-1" // auto detect multi-core rendering
fps_max "999"
fps_max_menu "145"
r_dynamic "0"
r_drawtracers_firstperson "0"

// Audio
volume "0.7"
voice_enable "1"
voice_scale "1" // receive volume
voice_mixer_volume "1" // mic volume
windows_speaker_config "1" // headphone audio output
snd_use_hrtf "1"
snd_mix_async "1"
snd_mixahead "0.02" // sound delay
snd_pitchquality "1"
snd_ducking_off "1"
snd_front_headphone_position "90"
snd_rear_headphone_position "90"
snd_headphone_pan_exponent "1.2"
snd_headphone_pan_radial_weight "1"
snd_mute_losefocus  "0" // mute game when alt-tabbed
dsp_enhance_stereo "0"
snd_musicvolume "0"
lobby_voice_chat_enabled "1" // voice chat in lobby
cl_mute_all_but_friends_and_party "0"
snd_async_flush

// HUD
hud_scaling "0.80"
hud_showtargetid "1"
cl_hud_background_alpha "0.100000"
cl_hud_bomb_under_radar "0"
cl_hud_color "1"
cl_hud_healthammo_style "1"
cl_hud_playercount_pos "0"
cl_hud_playercount_showcount "0"
cl_hud_radar_scale "0.950000"
cl_teamid_overhead_name_alpha "240"
cl_righthand "1"
cl_showloadout "1"
cl_showpos "0"
cl_showfps "0"
net_graph "1"
net_graphproportionalfont "0" // small netgraph font
// Radar
cl_radar_always_centered "0"
cl_radar_rotate "1"
cl_radar_scale "0.4"
cl_radar_icon_scale_min "0.4"
cl_radar_square_with_scoreboard "0"
// Reposition gun model to mimic source
viewmodel_presetpos "0"
viewmodel_fov "68"
viewmodel_offset_x "2.500000"
viewmodel_offset_y "0"
viewmodel_offset_z "-1.500000"
// Reduce gun shifting when crouching
cl_viewmodel_shift_left_amt "0.5"
cl_viewmodel_shift_right_amt "0.5"
// Reduce gun and scope shifting/bobbing when moving
cl_bobcycle "0.98"
cl_bob_lower_amt "5"
cl_bobamt_lat "0.1"
cl_bobamt_vert "0.1"

// Crosshair
cl_crosshairstyle 4
cl_crosshairsize 3
cl_crosshairthickness 0
cl_crosshairgap -2
cl_crosshair_drawoutline 1
cl_crosshair_outlinethickness 1
cl_crosshairdot 0
cl_crosshair_t 0
cl_crosshaircolor 1
cl_crosshaircolor_r 250
cl_crosshaircolor_g 0
cl_crosshaircolor_b 0
cl_crosshairalpha 155

// Misc
con_enable "1"
developer "0" // print console to screen
con_filter_enable "2"
con_filter_text "Damage "
ui_steam_overlay_notification_position "bottomright"
player_nevershow_communityservermessage "1"
mm_dedicated_search_maxping "80" // max ping for matchmaking games
mm_dedicated_force_servers ""
gameinstructor_enable "0"
option_duck_method "0"
option_speed_method "0"
cl_forcepreload "1"
cl_downloadfilter "nosound" // mapsonly pls volvo
cl_join_advertise "2" // let friends join your game
cl_disablehtmlmotd "0"
cl_autohelp "0"
cl_showhelp "0"
cl_disablefreezecam "1"
spec_replay_autostart "0"
cl_dm_buyrandomweapons "0"
cl_teammate_colors_show "1"
cl_autowepswitch "0" // auto weapon switch on pickup
cl_use_opens_buy_menu "1" // `e` opening buy menu
closeonbuy "0"
hud_takesshots "0" // scoreboard screenshot at end of match
cl_clanid "" // rip afterlife
password ""

host_writeconfig // write settings to config.cfg
echo ""
echo ""
echo "autoexec.cfg executed"
echo ""
echo ""
echo ""
