
_^ - These functions require AllowUnsafeScripting to be enabled in ddraw.ini_

0x8156 - `int   read_byte(int address)`\
0x8157 - `int   read_short(int address)`\
0x8158 - `int   read_int(int address)`\
0x8159 - `string read_string(int address)`

^ 0x81cf - `void  write_byte(int address, int value)`\
^ 0x81d0 - `void  write_short(int address, int value)`\
^ 0x81d1 - `void  write_int(int address, int value)`\
^ 0x821b - `void  write_string(int address, string value)`

^ 0x81d2 - `void  call_offset_v0(int address)`\
^ 0x81d3 - `void  call_offset_v1(int address, int arg1)`\
^ 0x81d4 - `void  call_offset_v2(int address, int arg1, int arg2)`\
^ 0x81d5 - `void  call_offset_v3(int address, int arg1, int arg2, int arg3)`\
^ 0x81d6 - `void  call_offset_v4(int address, int arg1, int arg2, int arg3, int arg4)`\
^ 0x81d7 - `int   call_offset_r0(int address)`\
^ 0x81d8 - `int   call_offset_r1(int address, int arg1)`\
^ 0x81d9 - `int   call_offset_r2(int address, int arg1, int arg2)`\
^ 0x81da - `int   call_offset_r3(int address, int arg1, int arg2, int arg3)`\
^ 0x81db - `int   call_offset_r4(int address, int arg1, int arg2, int arg3, int arg4)`

0x815a - `void set_pc_base_stat(int StatID, int value)`\
0x815b - `void set_pc_extra_stat(int StatID, int value)`\
0x815c - `int  get_pc_base_stat(int StatID)`\
0x815d - `int  get_pc_extra_stat(int StatID)`

0x815e - `void set_critter_base_stat(object, int StatID, int value)`\
0x815f - `void set_critter_extra_stat(object, int StatID, int value)`\
0x8160 - `int  get_critter_base_stat(object, int StatID)`\
0x8161 - `int  get_critter_extra_stat(object, int StatID)`\
0x8242 - `void set_critter_skill_points(int critter, int skill, int value)`\
0x8243 - `int  get_critter_skill_points(int critter, int skill)`\
0x8244 - `void set_available_skill_points(int value)`\
0x8245 - `int  get_available_skill_points()`\
0x8246 - `void mod_skill_points_per_level(int value)`

0x81b4 - `void set_stat_max(int stat, int value)`\
0x81b5 - `void set_stat_min(int stat, int value)`\
0x81b7 - `void set_pc_stat_max(int stat, int value)`\
0x81b8 - `void set_pc_stat_min(int stat, int value)`\
0x81b9 - `void set_npc_stat_max(int stat, int value)`\
0x81ba - `void set_npc_stat_min(int stat, int value)`

0x816b - `int  input_funcs_available()`\
0x816c - `int  key_pressed(int dxScancode)`\
0x8162 - `void tap_key(int dxScancode)`\
0x821c - `int  get_mouse_x()`\
0x821d - `int  get_mouse_y()`\
0x821e - `int  get_mouse_buttons()`\
0x821f - `int  get_window_under_mouse()`

0x8163 - `int get_year()`

0x8164 - `bool game_loaded()`

0x8165 - `bool graphics_funcs_available()`\
0x8166 - `int  load_shader(string path)`\
0x8167 - `void free_shader(int ID)`\
0x8168 - `void activate_shader(int ID)`\
0x8169 - `void deactivate_shader(int ID)`\
0x816d - `void set_shader_int(int ID, string param, int value)`\
0x816e - `void set_shader_float(int ID, string param, float value)`\
0x816f - `void set_shader_vector(int ID, string param, float f1, float f2, float f3, float f4)`\
0x81ad - `int get_shader_version()`\
0x81ae - `void set_shader_mode(int mode)`\
0x81b0 - `void force_graphics_refresh(bool enabled)`\
0x81b1 - `int get_shader_texture(int ID, int texture)`\
0x81b2 - `void set_shader_texture(int ID, string param, int texID)`

0x816a - `void set_global_script_repeat(int frames)`\
0x819b - `void set_global_script_type(int type)`\
0x819c - `int available_global_script_types()`

0x8170 - `bool in_world_map()`

0x8171 - `void force_encounter(int map)`\
0x8229 - `void force_encounter_with_flags(int map, int flags)`\
0x822a - `void set_map_time_multi(float multi)`

0x8172 - `void set_world_map_pos(int x, int y)`\
0x8173 - `int get_world_map_x_pos()`\
0x8174 - `int get_world_map_y_pos()`

0x8175 - `void set_dm_model(string name)`\
0x8176 - `void set_df_model(string name)`\
0x8177 - `void set_movie_path(string filename, int movieid)`

0x8178 - `void set_perk_image(int perkID, int value)`\
0x8179 - `void set_perk_ranks(int perkID, int value)`\
0x817a - `void set_perk_level(int perkID, int value)`\
0x817b - `void set_perk_stat(int perkID, int value)`\
0x817c - `void set_perk_stat_mag(int perkID, int value)`\
0x817d - `void set_perk_skill1(int perkID, int value)`\
0x817e - `void set_perk_skill1_mag(int perkID, int value)`\
0x817f - `void set_perk_type(int perkID, int value)`\
0x8180 - `void set_perk_skill2(int perkID, int value)`\
0x8181 - `void set_perk_skill2_mag(int perkID, int value)`\
0x8182 - `void set_perk_str(int perkID, int value)`\
0x8183 - `void set_perk_per(int perkID, int value)`\
0x8184 - `void set_perk_end(int perkID, int value)`\
0x8185 - `void set_perk_chr(int perkID, int value)`\
0x8196 - `void set_perk_int(int perkID, int value)`\
0x8187 - `void set_perk_agl(int perkID, int value)`\
0x8188 - `void set_perk_lck(int perkID, int value)`\
0x8189 - `void set_perk_name(int perkID, string value)`\
0x818a - `void set_perk_desc(int perkID, string value)`\
0x8247 - `void set_perk_freq(int value)`

0x818b - `void set_pipboy_available(int available)`

0x818c - `int get_kill_counter(int critterType)`\
0x818d - `void mod_kill_counter(int critterType, int amount)`

0x818e - `int get_perk_owed()`\
0x818f - `void set_perk_owed(int value)`\
0x8190 - `int get_perk_available(int perk)`

0x8191 - `int get_critter_current_ap(object critter)`\
0x8192 - `void set_critter_current_ap(object critter, int ap)`

0x8193 - `int  active_hand()`\
0x8194 - `void toggle_active_hand()`

0x8195 - `void set_weapon_knockback(object weapon, int type, int/float value)`\
0x8196 - `void set_target_knockback(object critter, int type, int/float value)`\
0x8197 - `void set_attacker_knockback(object critter, int type, int/float value)`\
0x8198 - `void remove_weapon_knockback(object weapon)`\
0x8199 - `void remove_target_knockback(object critter)`\
0x819a - `void remove_attacker_knockback(object critter)`

0x819d - `void  set_sfall_global(string/int varname, int/float value)`\
0x819e - `int   get_sfall_global_int(string/int varname)`\
0x819f - `float get_sfall_global_float(string/int varname)`\
0x822d - `int   create_array(int element_count, int flags)`\
0x822e - `void  set_array(int array, any element, any value)`\
0x822f - `any   get_array(int array, any element)`\
0x8230 - `void  free_array(int array)`\
0x8231 - `int   len_array(int array)`\
0x8232 - `void  resize_array(int array, int new_element_count)`\
0x8233 - `int   temp_array(int element_count, int flags)`\
0x8234 - `void  fix_array(int array)`\
0x8239 - `int   scan_array(int array, int/float var)`\
0x8256 - `int   array_key(int array, int index)`\
0x8257 - `int   arrayexpr(any key, any value)`\
0x8254 - `void  save_array(any key, int array)`\
0x8255 - `int   load_array(any key)`

0x81a0 - `void set_pickpocket_max(int percentage)`\
0x81a1 - `void set_hit_chance_max(int percentage)`\
0x81a2 - `void set_skill_max(int value)`\
0x81aa - `void set_xp_mod(int percentage)`\
0x81ab - `void set_perk_level_mod(int levels)`

0x81c5 - `void set_critter_hit_chance_mod(object, int max, int mod)`\
0x81c6 - `void set_base_hit_chance_mod(int max, int mod)`\
0x81c7 - `void set_critter_skill_mod(object, int max)`\
0x81c8 - `void set_base_skill_mod(int max)`\
0x81c9 - `void set_critter_pickpocket_mod(object, int max, int mod)`\
0x81ca - `void set_base_pickpocket_mod(int max, int mod)`

0x81a3 - `int  eax_available()`\
0x81a4 - `void set_eax_environment(int environment)`

0x81a5 - `void inc_npc_level(int pid/string name)`\
0x8241 - `int  get_npc_level(int pid/string name)`

0x81a6 - `int get_viewport_x()`\
0x81a7 - `int get_viewport_y()`\
0x81a8 - `void set_viewport_x(int view_x)`\
0x81a9 - `void set_viewport_y(int view_y)`

0x81ac - `int   get_ini_setting(string setting)`\
0x81eb - `string get_ini_string(string setting)`

0x81af - `int get_game_mode()`

0x81b3 - `int get_uptime()`

0x81b6 - `void set_car_current_town(int town)`

0x81bb - `void set_fake_perk(string name, int level, int image, string desc)`\
0x81bc - `void set_fake_trait(string name, int active, int image, string desc)`\
0x81bd - `void set_selectable_perk(string name, int active, int image, string desc)`\
0x81be - `void set_perkbox_title(string title)`\
0x81bf - `void hide_real_perks()`\
0x81c0 - `void show_real_perks()`\
0x81c1 - `int has_fake_perk(string name/int extraPerkID)`\
0x81c2 - `int has_fake_trait(string name)`\
0x81c3 - `void perk_add_mode(int type)`\
0x81c4 - `void clear_selectable_perks()`\
0x8225 - `void remove_trait(int traitID)`

0x81cb - `void set_pyromaniac_mod(int bonus)`\
0x81cc - `void apply_heaveho_fix()`\
0x81cd - `void set_swiftlearner_mod(int bonus)`\
0x81ce - `void set_hp_per_level_mod(int mod)`

0x81dc - `void show_iface_tag(int tag)`\
0x81dd - `void hide_iface_tag(int tag)`\
0x81de - `int  is_iface_tag_active(int tag)`

0x81df - `int  get_bodypart_hit_modifier(int bodypart)`\
0x81e0 - `void set_bodypart_hit_modifier(int bodypart, int value)`

0x81e1 - `void set_critical_table(int crittertype, int bodypart, int level, int valuetype, int value)`\
0x81e2 - `int  get_critical_table(int crittertype, int bodypart, int level, int valuetype)`\
0x81e3 - `void reset_critical_table(int crittertype, int bodypart, int level, int valuetype)`

0x81e4 - `int   get_sfall_arg()`\
0x823c - `array get_sfall_args()`\
0x823d - `void  set_sfall_arg(int argnum, int value)`\
0x81e5 - `void  set_sfall_return(int value)`\
0x81ea - `int   init_hook()`

0x81e6 - `void set_unspent_ap_bonus(int multiplier)`\
0x81e7 - `int  get_unspent_ap_bonus()`\
0x81e8 - `void set_unspent_ap_perk_bonus(int multiplier)`\
0x81e9 - `int  get_unspent_ap_perk_bonus()`

0x81ec - `float sqrt(float)`\
0x81ed - `int/float abs(int/float)`\
0x81ee - `float sin(float)`\
0x81ef - `float cos(float)`\
0x81f0 - `float tan(float)`\
0x81f1 - `float arctan(float x, float y)`\
0x8263 - `^` operator (exponentiation)\
0x8264 - `float log(float)`\
0x8265 - `float exponent(float)`\
0x8266 - `int ceil(float)`\
0x8267 - `int round(float)`

0x81f2 - `void set_palette(string path)`

0x81f3 - `void remove_script(object)`\
0x81f4 - `void set_script(object, int scriptid)`\
0x81f5 - `int get_script(object)`

0x81f6 - `int nb_create_char()`

0x81f7 - `int   fs_create(string path, int size)`\
0x81f8 - `int   fs_copy(string path, string source)`\
0x81f9 - `int   fs_find(string path)`\
0x81fa - `void  fs_write_byte(int id, int data)`\
0x81fb - `void  fs_write_short(int id, int data)`\
0x81fc - `void  fs_write_int(int id, int data)`\
0x81fd - `void  fs_write_float(int id, int data)`\
0x81fe - `void  fs_write_string(int id, string data)`\
0x8208 - `void  fs_write_bstring(int id, string data)`\
0x8209 - `int   fs_read_byte(int id)`\
0x820a - `int   fs_read_short(int id)`\
0x820b - `int   fs_read_int(int id)`\
0x820c - `float fs_read_float(int id)`\
0x81ff - `void  fs_delete(int id)`\
0x8200 - `int   fs_size(int id)`\
0x8201 - `int   fs_pos(int id)`\
0x8202 - `void  fs_seek(int id, int pos)`\
0x8203 - `void  fs_resize(int id, int size)`

0x8204 - `int  get_proto_data(int pid, int offset)`\
0x8205 - `void set_proto_data(int pid, int offset, int value)`

0x8206 - `void set_self(object)`\
0x8207 - `void register_hook(int hook)`

0x820d - `int   list_begin(int type)`\
0x820e - `int   list_next(int listid)`\
0x820f - `void  list_end(int listid)`\
0x8236 - `array list_as_array(int type)`

0x8210 - `int sfall_ver_major()`\
0x8211 - `int sfall_ver_minor()`\
0x8212 - `int sfall_ver_build()`

0x8213 - `void hero_select_win(int)`\
0x8214 - `void set_hero_race(int style)`\
0x8215 - `void set_hero_style(int style)`

0x8216 - `void set_critter_burst_disable(object critter, int disable)`

0x8217 - `int  get_weapon_ammo_pid(object weapon)`\
0x8218 - `void set_weapon_ammo_pid(object weapon, int pid)`\
0x8219 - `int  get_weapon_ammo_count(object weapon)`\
0x821a - `void set_weapon_ammo_count(object weapon, int count)`

0x8220 - `int get_screen_width()`\
0x8221 - `int get_screen_height()`

0x8222 - `void stop_game()`\
0x8223 - `void resume_game()`\
0x8224 - `void create_message_window(string message)`

0x8226 - `int get_light_level()`

0x8227 - `void refresh_pc_art()`

0x8228 - `int get_attack_type()`

0x822b - `int  play_sfall_sound(string file, int mode)`\
0x822c - `void stop_sfall_sound(int soundID)`

0x8235 - `array string_split(string string, string split)`\
0x8237 - `int   atoi(string string)`\
0x8238 - `float atof(string string)`\
0x824e - `string substr(string string, int start, int length)`\
0x824f - `int   strlen(string string)`\
0x8250 - `string sprintf(string format, any value)`\
0x8251 - `int   charcode(string string)`\
0x8253 - `int   typeof(any value)`

0x823a - `int get_tile_fid(int tile)`

0x823b - `int modified_ini()`

0x823e - `void force_aimed_shots(int pid)`\
0x823f - `void disable_aimed_shots(int pid)`

0x8240 - `void mark_movie_played(int id)`

0x8248 - `object get_last_target(object critter)`\
0x8249 - `object get_last_attacker(object critter)`\
0x824a - `void block_combat(int enable)`

0x824b - `int tile_under_cursor()`\
0x824c - `int gdialog_get_barter_mod()`\
0x824d - `void set_inven_ap_cost(int cost)`

0x825c - `void reg_anim_combat_check(int enable)`\
0x825a - `void reg_anim_destroy(object object)`\
0x825b - `void reg_anim_animate_and_hide(object object, int animID, int delay)`\
0x825d - `void reg_anim_light(object object, int radius, int delay)`\
0x825e - `void reg_anim_change_fid(object object, int FID, int delay)`\
0x825f - `void reg_anim_take_out(object object, int holdFrameID, int delay)`\
0x8260 - `void reg_anim_turn_towards(object object, int tile/targetObj, int delay)`

0x8261 - `int metarule2_explosions(object object)`

0x8262 - `void register_hook_proc(int hook, procedure proc)`

0x826b - `string message_str_game(int fileId, int messageId)`\
0x826c - `int sneak_success()`\
0x826d - `int tile_light(int elevation, int tileNum)`\
0x826e - `object obj_blocking_line(object objFrom, int tileTo, int blockingType)`\
0x826f - `object obj_blocking_tile(int tileNum, int elevation, int blockingType)`\
0x8270 - `array tile_get_objs(int tileNum, int elevation)`\
0x8271 - `array party_member_list(int includeHidden)`\
0x8272 - `array path_find_to(object objFrom, int tileTo, int blockingType)`\
0x8273 - `object create_spatial(int scriptID, int tile, int elevation, int radius)`\
0x8274 - `int art_exists(int artFID)`\
0x8275 - `int obj_is_carrying_obj(object invenObj, object itemObj)`

0x8276 - `any sfall_func0(string funcName)`\
0x8277 - `any sfall_func1(string funcName, arg1)`\
0x8278 - `any sfall_func2(string funcName, arg1, arg2)`\
0x8279 - `any sfall_func3(string funcName, arg1, arg2, arg3)`\
0x827a - `any sfall_func4(string funcName, arg1, arg2, arg3, arg4)`\
0x827b - `any sfall_func5(string funcName, arg1, arg2, arg3, arg4, arg5)`\
0x827c - `any sfall_func6(string funcName, arg1, arg2, arg3, arg4, arg5, arg6)`

0x827d - `void register_hook_proc_spec(int hook, procedure proc)`\
0x827e - `void reg_anim_callback(procedure proc)`

0x827f - `div` operator (unsigned integer division)

0x8280 - `any sfall_func7(string funcName, arg1, arg2, arg3, arg4, arg5, arg6, arg7)`\
0x8281 - `any sfall_func8(string funcName, arg1, arg2, arg3, arg4, arg5, arg6, arg7, arg8)`\
