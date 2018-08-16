# CsgoConfig-Autoexec #


///////////////////////// Launch Options /////////////////////////  
-steam -console -novid -nojoy -freq 144 -console -high -tickrate 128 -heapsize 4194304 -nod3d9ex -noaafonts -high +exec autoexec -lv -language pirate +rate 786432 

///////////////////////// Video Settings /////////////////////////  
In-game res : 1024x768  
In-game Hertz : 144


///////////////////////// Mouse Settings /////////////////////////  
Windows Sens : 6/11  
Mouse DPI : 400  
Mouse HZ : 1000  
In-game Sens : 2.0  



bind "MOUSE4" "use weapon_flashbang"
bind "MOUSE5" "use weapon_hegrenade"
bind "MWHEELUP" "invprev"

bind "MWHEELDOWN" "+jump"

volume "0.5"

bind "F2" "exec CrossTLG.cfg"
bind "F3" "exec CrossDevice.cfg"
bind "F4" "exec CrossElec.cfg"
bind "F5" "exec CrossZywo.cfg"
bind "F6" "exec CrossColdzera.cfg"
bind "F7" "exec CrossM.cfg"
bind "F8" "exec CrossStewie.cfg"
bind "F9" "exec CrossX.cfg"



cl_cmdrate "128"
cl_updaterate "128"
rate "786432"
fps_max "300"

cl_interp "1"
cl_interp_ratio "2"

alias "+jumpthrow" "+jump;-attack"
alias "-jumpthrow" "-jump"
bind "mouse5" "+jumpthrow"
bind "v" "+voicerecord"
bind "k" "viewmodel_fov 68;viewmodel_offset_x 2.5;viewmodel_offset_y 0;viewmodel_offset_z -1.5"
bind "l" "viewmodel_fov 60;viewmodel_offset_x 1;viewmodel_offset_y 1;viewmodel_offset_z -1"
bind "o" "viewmodel_fov 68;viewmodel_offset_x 2;viewmodel_offset_y 2;viewmodel_offset_z -2"
bind "p" "viewmodel_fov 68;viewmodel_offset_x 2.5;viewmodel_offset_y 1;viewmodel_offset_z -1.5"

bind "a" "+moveleft;r_cleardecals"

bind "d" "+moveright;r_cleardecals"

bind "h" "incrementvar volume 0 0.5 0.5"

cl_teamid_overhead_always 1
cl_teamid_overhead_maxdist 9999
m_rawinput 0
m_mousespeed 1
m_customaccel 3


bind "MOUSE4" "cl_righthand 1"

bind "MOUSE5" "cl_righthand 0"

+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

// Viewmodel

viewmodel_fov "68"
viewmodel_offset_x "-2"
viewmodel_offset_y "2"
viewmodel_offset_z "-2"
cl_bobcycle "0.98"
cl_bob_lower_amt "0"
cl_viewmodel_shift_left_amt "0"
cl_viewmodel_shift_right_amt "0"
cl_bobamt_lat "0"
cl_bobamt_vert "0"

sensitivity "2"



//NETCODE / INTERPOLATION SETTINGS

rate "786432"
cl_cmdrate "128"
cl_updaterate "128"
cl_interp "1"
cl_interp_ratio "2"
cl_resend "1.5"
cl_resend_timeout "3"
cl_interpolate "1"
net_maxroutable 1200
cl_smooth "0"



cl_crosshair_drawoutline "0"
cl_crosshaircolor "1"
cl_crosshairdot "0"
cl_crosshairgap "-3"
cl_crosshairgap_useweaponvalue "0"
cl_crosshairsize "1"
cl_crosshairstyle "4"
cl_crosshairthickness "1"
cl_crosshairusealpha "1"
snd_use_hrtf "0"

fps_max "999"
fps_max_menu "999"
cl_forcepreload "1"
cl_disablehtmlmotd "1"
cl_phys_props_enable "0"
cl_downloadfilter "nosounds"
muzzleflash_light "0"
fog_enable "0"
net_allow_multicast "0"
r_drawtracers_firstperson "1"
r_dynamic "0" 
r_eyemove "0"
r_eyegloss "0"
r_cheapwaterend "1"
r_cheapwaterstart "1"
r_rootlod "2"
r_renderoverlayfragment "0"
r_3dsky "0"
r_3dnow "0"
r_sse2 "1"
muzzleflash_light "0"
sys_antialiasing "0"
sys_aspectratio "-1"
sys_refldetail "0"
mat_hdr_enabled "0"
mat_bloomamount_rate "0.05f"
mat_bumpbasis "0"
mat_debugalttab "0"
mat_debug_bloom "0"
mat_debug_postprocessing_effects "0"
mat_disable_bloom "1"
mat_fastnobump "1"
mat_force_bloom "0"
mat_hdr_enabled "0"
mat_leafvis "0"
mat_loadtextures "1"
mat_norendering "0"
mat_show_texture_memory_usage "0"
mat_softwareskin "0"
mat_surfaceid "0"
mat_surfacemat "0"
mat_yuv "0"
mat_queue_mode "2"
mat_vignette_enable "0"
mat_picmip "0"
net_graph "0"
net_graphpos "1"
net_graphproportionalfont "0"

mat_savechanges

//MISCELLANEOUS

r_drawtracers_firstperson 0
cl_autowepswitch "0"
hud_showtargetid "1"
cl_autohelp "0"
cl_showhelp "0"
gameinstructor_enable "0"
lobby_voice_chat_enabled "0"
cl_disablefreezecam "1"
joystick "0"
joystick_force_disabled "1"
joystick_force_disabled_set "1"
cl_loadout_colorweaponnames "1"
hud_showtargetid "1"
cl_righthand "1"
mm_dedicated_search_maxping "50"
sv_forcepreload "1"
mp_decals "50"

//CONSOLE SETTINGS

con_enable "1"
developer "1"
con_filter_text "Damage given"
con_filter_text_out "Player:"
con_filter_enable "2"

//SOUND SETTINGS

snd_mixahead "0.05"
snd_headphone_pan_exponent "2"
snd_musicvolume "0"
