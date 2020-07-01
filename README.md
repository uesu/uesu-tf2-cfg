# uesu-cfg

my `cfg` is pretty much `vanilla` and it doesn't have too many configurations, scripts or binds. it only has the important ones that i really feel like i need. feel free to look inside the `class.cfg = soldier, demoman.cfg` and `autoexec.cfg` to see what is written and after that, you can `remove, edit or add` more within the `.cfg` files.


<h3>install:
</h3>

* [download zip](https://github.com/uesu/cfg/archive/master.zip)

* unzip and place the `user` folder to `tf/cfg` and `custom` folder to `tf/custom`

`note`: remove `bxhud` if you don't use a hud, or if you don't want bxhud. If you want to use `bxhud`, unpack `bxhud.rar` and place the folder in `tf/custom`

<h3>faq:
</h3>

* `note`: if you do not want to use it, add `//` slashes before the `command, script, bind or alias` and remove `//` slashes if you want to use it

 `fonts`:

- if you have font problems: 
  - install all fonts on 
`bXHud / resource / fonts`

`sensitivity`:

- if you want to change the sensitivity of each class 
  - just go to the `class.cfg`: 
    - `spy.cfg, scout.cfg, demoman.cfg`
    
      the default sensitivity value: `3.000000`

`crouch jump`:

- crouch jump is enabled on all class
  - if you don't want to use crouch jump = add `//` before the script
    - then remove `//` slashes on `bind space +jump` and `bind ctrl +duck` from `gameoverrides.cfg`

* `note`: if you want to deactivate crouch jump (example = `scout`) and use crouch jump on `soldier` or `demoman`, simply add `//` before the script on `scout` and remove `//` slashes on `bind space +jump` and `bind ctrl +duck` from 'gameoverrides.cfg'

`resolution`:

- find `mat_setvideomode 720 480 0` on autoexec.cfg
  - change `720 480` to your preferred resolution; example = `1280 720`
 
`medic`:

* `sayteam`:

  - on `tf/cfg/user/medic` folder
    - you can change the highlighted text to whatever you want
    
cmd say_team "`using kritz!`"

alias uber_used "cmd say_team `>>kritz used<<`"

alias uber_ready "cmd say_team `>>kritz ready<<`"

* `note`: execute when changing medigun

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
