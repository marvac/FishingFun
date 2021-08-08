Set this macro on your cast key to automatically attach lures:

```
/run sfx=GetCVar("Sound_EnableSFX")
/console Sound_EnableSFX 0
/equip Big Iron Fishing Pole
/use Aquadynamic Fish Attractor
/use 16
/click StaticPopup1Button2
/cast [nochanneling] Fishing
/use 1
/run SetCVar("Sound_EnableSFX",sfx)
```

Set `Big Iron Fishing Pole` to the name of your pole and `Aquadynamic Fish Attractor` to the name of your lure.