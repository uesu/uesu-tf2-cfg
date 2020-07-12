# uesu-cfg

my `cfg` is pretty much `vanilla` and it doesn't have too many configurations, scripts or binds. it only has the important ones that i really feel like i need. feel free to look inside the `class.cfg = soldier.cfg, demoman.cfg` and `autoexec.cfg` to see what is written and after that, you can `remove, edit or add` more within the `.cfg` files.


<h3>install:
</h3>

- install [git](https://gitforwindows.org/) and open `git bash`
    - copy and paste `git clone https://github.com/uesu/cfg (insert folder name)`
        * example: `git clone https://github.com/uesu/cfg test`

`note`: simply search for the name you named the folder to locate it

[alternate download](https://github.com/uesu/cfg/archive/master.zip) if you don't want to install [git](https://gitforwindows.org/)

* place the `user` folder to `tf/cfg` and `custom` folder to `tf/custom`

<h3>
update:
</h3>

* to update, simply run `update.sh`

`note`: remove `bxhud` if you don't use a hud, or if you don't want bxhud. if you want to use `bxhud`, unpack `bxhud.rar` and place the folder in `tf/custom`

<h3>faq:
</h3>

* `note`: if you do not want to use it, add `//` slashes before the `command, script, bind or alias` and remove `//` slashes if you want to use it

 `fonts`:

- if you have font problems: 
  - install all fonts on 
`bXHud / resource / fonts`

`mouse and sensitivity`:

- if you want to change the raw input and sensitivity
  - just go to the `class.cfg`: 
    - `spy.cfg, scout.cfg, demoman.cfg`
    
      the default sensitivity value: `3.000000`

`crouch jump`:

- crouch jump is enabled on all class
  - if you don't want to use crouch jump = add `//` before the script
    - then remove `//` slashes on `bind space +jump` and `bind ctrl +duck` from `gameoverrides.cfg`

* `note`: if you want to deactivate crouch jump (example = `scout`) and use crouch jump on `soldier` or `demoman`, simply add `//` before the script on `scout` and remove `//` slashes on `bind space +jump` and `bind ctrl +duck` from `gameoverrides.cfg`

`null-movement`:

- if you only want to use the script on; example = `scout`
    - remove the `null-movement script` on `gameoverrides.cfg` (if you put it on `gameoverrides.cfg` it will enable null-movement for all class and i think it should be enabled on all class but if you want to use it on a specific class then) copy it and paste it to `scout.cfg`
        
* `note`: enable the `default keybind` for null-movement in `gameoverrides.cfg`

`resolution`:

- find `mat_setvideomode 1024 768 0` on `autoexec.cfg`
  - change `1024 768` to your preferred resolution; example = `1280 720`
 
`medic`:

* `sayteam`:

  - on `tf/cfg/user/medic` folder
    - you can change the highlighted text to whatever you want
    
cmd say_team "`using kritz!`"

alias uber_used "cmd say_team `>>kritz used<<`"

alias uber_ready "cmd say_team `>>kritz ready<<`"

* `note`: execute when changing medigun to change the `sayteam`

      bind KP_HOME"exec user/medic/ubercharge.cfg" // loadout a = medigun
      bind KP_UPARROW"exec user/medic/kritzkrieg.cfg" // loadout b = kritzkrieg
      bind KP_PGUP"exec user/medic/quickfix.cfg" // loadout c = quickfix
      bind KP_LEFTARROW"exec user/medic/vaccinator.cfg" // loadout d = vaccinator
      
* `medic callout / radar`:

`note`: this will only work on medic, it won't conflict with other classes

      press "e"

all members of the team show their position `showing a health bubble at the top of their heads`
        
* `fake uber`:

      press "g"

* `mask uber`:

      press "f"
  
`note`: you can change what key you want to bind instead of `e, g, and f`. just make sure you reset it to `gameoverrides.cfg`

[more competitive medic scripts](https://gist.github.com/marcinof/2981918)

* scripts i used and the source of these:

[null cancelling movement script](https://github.com/mastercomfig/mastercomfig/releases/latest/download/mastercomfig-null-cancelling-movement-addon.vpk)

[quick build and destroy script](https://www.reddit.com/r/tf2/comments/94volb/quick_build_and_destroy_script/)

[competitive medic scripts](https://github.com/mastercoms/configs/tree/master/games/tf2/cfg/user)

[quick switch loadout](https://www.reddit.com/r/Tf2Scripts/comments/1ol0z0/help_how_do_i_bind_a_key_to_change_loadout/)

[crouch jump script](https://gamebanana.com/scripts/7982)

[quick class switch](https://gamebanana.com/scripts/3908)

[flat mouse](https://github.com/mastercomfig/mastercomfig/releases/latest/download/mastercomfig-flat-mouse-addon.vpk)
