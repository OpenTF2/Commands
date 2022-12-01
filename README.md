
# Commands

*Add these to your  `autoexe.cfg`  to* <br>
*have them permanently in your game.*

<br>

## Slow Walk

*Add this to toggle slow walking.*

<br>

```cfg
alias SlowWalk SlowWalk_On
alias SlowWalk_On  "alias SlowWalk SlowWalk_Off;+movedown"
alias SlowWalk_Off "alias SlowWalk SlowWalk_On ;-movedown"
bind l SlowWalk
```

<br>
<br>

## Xmas Snow Flakes

*Use these bindings to constantly emit snowflakes.*

<br>

```cfg
bind mouse1 "+attack;+use_action_slot_item"
bind space "+jump;+use_action_slot_item"
bind s "+moveright;+use_action_slot_item"
bind a "+moveleft;+use_action_slot_item"
bind w "+forward;+use_action_slot_item"
bind d "+back;+use_action_slot_item"
```

<br>
