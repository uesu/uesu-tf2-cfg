# uesu-cfg

my tf2 config; mostly vanilla

`note`: i use a regular keyboard and a standard optical mouse

<h3>what uesu config contains
</h3>

* class configs
* some useful scripts
* custom hud (bxhud)
* mastercomfig

<h3>install:
</h3>

- install [git](https://gitforwindows.org/) and open `git bash`
    - copy and paste `git clone https://github.com/uesu/cfg test`
    
[alternate download](https://github.com/uesu/cfg/releases) if you don't want to install [git](https://gitforwindows.org/)

`note`: locate the folder where you saved it by simply searching for the name of the `test` folder

* place the `user` folder to `tf/cfg` and `custom` folder to `tf/custom`

<h3>
update:
</h3>

to update, simply run `update.sh`

<h3>
faq:
</h3>

`note`: add `//` if you don't want to use the command, remove `//` if you want to use it

hud:

- unzip bxhud
    - place bxhud on `tf/custom`

fonts:

- if you have font problems: 
  - install all fonts on 
`bXHud / resource / fonts`

mouse and sensitivity:

- if you want to change the raw input and sensitivity
  - just go to the class configs = (e.g) spy.cfg

crouch jump:

- crouch jump is enabled on all class
  - if you don't want to use crouch jump = add `//` before the script
    - then remove `//` on `bind space +jump` and `bind ctrl +duck` from gameoverrides.cfg

`note`: if you want to deactivate crouch jump (example = scout) and use crouch jump on soldier or demoman, simply add `//` before the crouch jump script on scout and remove `//` on `bind space +jump` and `bind ctrl +duck` from gameoverrides.cfg

null-movement:

- if you only want to use the script on; example = scout
    - remove the `null-movement script` from gameoverrides.cfg (if you put it on gameoverrides.cfg it will enable null-movement for all class and i think it should be enabled on all class but if you want to use it on a specific class then) copy it and paste it to scout.cfg
        
`note`: enable the `default w-a-s-d` for null-movement in gameoverrides.cfg

quick-class switch:

- hold shift and press 1-9

quick-switch loadout:

- use the numeric keypad
    - 7 (kp_home) loadout a, 8 (kp_uparrow) loadout b, 9 (kp_pgup) loadout c and 4 (kp_leftarrow) loadout d 

load_itempreset 0 is loadout a

load_itempreset 1 is loadout b

load_itempreset 2 is loadout c

load_itempreset 3 is loadout d

resolution:

- find `mat_setvideomode 1280 768 0` on autoexec.cfg
  - change `1280 768` to your preferred resolution; example = `1920 1080`
 
medic:

`sayteam`:

  - on `tf/cfg/user/medic` folder
    - you can change the highlighted text to whatever you want
    
cmd say_team "`using kritz!`"

alias uber_used "cmd say_team `>>kritz used<<`"

alias uber_ready "cmd say_team `>>kritz ready<<`"

`note`: execute when changing medigun to change the `sayteam`

loadout a = medigun

loadout b = kritzkrieg

loadout c = quickfix

loadout d = vaccinator

      bind KP_HOME"exec user/medic/ubercharge.cfg"
      bind KP_UPARROW"exec user/medic/kritzkrieg.cfg"
      bind KP_PGUP"exec user/medic/quickfix.cfg" 
      bind KP_LEFTARROW"exec user/medic/vaccinator.cfg" 
      
medic callout / radar: press `e`
       
fake uber: press `g`

mask uber: press `f`
  
`note`: you can change what key you want to bind instead of `e, g, and f` or any keybinds that i set. just make sure to reset it to gameoverrides.cfg

engineer:

`quick build and destroy script`:

- hold shift and press 1-4 to build and press 1-4 to destroy

[more competitive medic scripts](https://gist.github.com/marcinof/2981918)

* scripts, mods, and hud i used and the source of these:

performance and customization config:

[mastercomfig](https://mastercomfig.com)

scripts:

[null cancelling movement script](https://github.com/mastercomfig/mastercomfig/releases/latest/download/mastercomfig-null-cancelling-movement-addon.vpk)

[quick build and destroy script](https://www.reddit.com/r/tf2/comments/94volb/quick_build_and_destroy_script/)

[competitive medic scripts](https://github.com/mastercoms/configs/tree/master/games/tf2/cfg/user)

[quick switch loadout](https://www.reddit.com/r/Tf2Scripts/comments/1ol0z0/help_how_do_i_bind_a_key_to_change_loadout/)

[crouch jump script](https://gamebanana.com/scripts/7982)

[quick class switch](https://gamebanana.com/scripts/3908)

[flat mouse](https://github.com/mastercomfig/mastercomfig/releases/latest/download/mastercomfig-flat-mouse-addon.vpk)

mods:

[no explosion smoke script](https://www.teamfortress.tv/25647/no-explosion-smoke-script)

[undertale soul healsign](https://gamebanana.com/effects/5460)

[original left hand fix](https://gamebanana.com/skins/165167)

[lugermorph fix](https://gamebanana.com/skins/160583)

hud:

[bxhud](https://github.com/Hypnootize/BX-Hud)
