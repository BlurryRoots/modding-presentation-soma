
frictional games
	indie studio from sweden

list of games
	first 3d engine developed for 2d engine code base in competition in 2006
		tech demo - publisher deal
		would later become penumbra

tech
	have always used their own tech
	hpl1 open sourced in 2010
	code base for penumbra games open sourced in 2010
		http://www.frictionalgames.com/site/node/102

penumbra
	no proper modding tools

amnesia
	very successful
	heavily modded
	ca. 450 mods (at moddb)

soma
	SOMA - Modding
	modding not quite as extensive
	ca. 15 (at moddb)
	next slide is already modding

modding
	tools - overview
		level editor
			build level, set light, configure trigger
		material editor
			create material from texture, tells lighting system how to tread material
		model editor
			model as scene
			lights, joints, animation control, particals
		particle editor
			create particle effects
	overview
		entry.hpc
			main infos like name and author
		resources.cfg
			define directories
		main_init.cfg
			define entry map and save game locations
		map (.hpm) + script (.hps)
			config file holding map infos, like entities
			map script, housing map wide logic
	tools - demo
		material editor
		model editor
		particle editor
	level editor - demo
		00_basics
			show basic operations
			quick look at tools bar
			show map reloading
		01_door
			click panel
				under connections write "door_1"
			rotate spawn point so player sees door
			create panel on other side
				under connections write "lamp_long_hallway_*"
		02_final
			click panel
				under basic callbacks
					connections state changed - triggers lamps
		01_01_upsilon_awake
			briefly show how real levels look like




misc notes

install soma
start some
	this generates dev config under “My Documents/My Games/Soma/Dev_user_settings.cfg”
	have a look at https://wiki.frictionalgames.com/hpl3/game/setup

materials are under static_objects