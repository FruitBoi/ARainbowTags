# ARainbowTags
EXILED port of RainbowTags, [originally](https://github.com/sirmeepington/RainbowTag/) created by [@SirMeepington](https://github.com/sirmeepington). Makes server badges go through a spectrum of colours in SCP:SL. 

This mod makes use of [EXILED](https://gitlab.com/Galaxy119/EXILED) for [SCP:SL](https://scpslgame.com/)

## Configuration

```yaml
#Should the plugin be enabled?
rainbowtags_enable: true
#Time between tag changes in seconds.
rainbowtags_taginterval: 0.5 
#Should we use a custom color sequence?
rainbowtags_usecustomsequence: false 
#Color sequence to use. Must set UseCustomSequence to true.
rainbowtags_colorsequence: pink, red, brown, silver, light_green 
#List of groups to enable RainbowTags for.
rainbowtags_activegroups: [owner, admin, moderator] 
```

**Valid Colours**:
* pink
* red
* brown
* silver
* light_green
* crimson
* cyan
* aqua
* deep_pink
* tomato
* yellow
* magenta
* blue_green
* orange
* lime
* green
* emerald
* carmine
* nickel
* mint
* army_green
* pumpkin


#### FAQ

If you get issues about `TAG FAIL`, you've either used a invalid / prohibited color. If you're certain you're not using a prohibited color, restart the server.
