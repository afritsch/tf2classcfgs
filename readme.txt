This are my Team Fortress 2 class cfgs.

I like to keep it simple, so don't expect too fancy bindings. I tried to make
the bindings mostly non-intrusive so you can play like always, just with
additional functionality. I avoid the wait command, so those configs should
work on competitive servers, too.

There is are some unused snippets in the configs, I did not test those where
commented, I just wanted to have them for reference or future usage.

If you have any suggetions, improvements, bugs or questions, add me on Steam:
http://steamcommunity.com/id/sonomabob

Most bindings are for mice with at least 5 buttons and mostly change mouse keys.

Disclaimer: USE ON YOUR OWN RISK.


Features:
- Toggle hud minmode on semicolon/ö
- Shows additionally to scores netgraph when holding tab
- Network settings can be changed on console with commands netgood, netbad
- All classes (except specifically changed): panicmelee on holding mouse3, then
  switch back to last weapon
- Spy: autosap when holding mouse5, when releasing switch back to last weapon
- Heavy: toggle machinemode (duck+attack) with mouse5, useful for MvM and
  close to dispensers, toogle autospin on mouse2 (deactivated)
- Engineer: quick build+destroy on keys 1-4 when holding alt, toggle autorepair
  on mouse5, then switch back to last weapon
- Sniper: sensitivity change when holding alt (increase for my case), quick
  jarate/SMG on mouse5, then switch back to last weapon
- Soldier: Announce enemy medic kill on mouse5, easy rocketjump on mouse2
  (deactivated)
- Pyro: toggle autofire on mouse5, works with switching weapons
- Scout: mouse1-3 direct switch+attack for all three weapons (note: sandman
  doesn't work)
- Medic: alt fake ubercharge, mouse5 team announce ubercharge is ready,
  backspace suicide, mouse2 use and announce used ubercharge, tapping crtl
  shows teammate locations
- Demoman: toggle autoshoot on mouse5, works with switching weapons


Notes:
- engineer quick build is problematic with the second sentry in MvM, use normal
  build menu for it
- sandman doesn't work for the scout bindings, either involve a "exec clear"
  on console or deactivate the binding for mouse2


Files:
- clear.cfg: clears bindings to defaults
- autoexec.cfg: does only clear bindings atm
- demoman.cfg, engineer.cfg, heavyweapons.cfg, medic.cfg, pyro.cfg, scout.cfg,
  sniper.cfg, soldier.cfg, spy.cfg


Sources used:
- Scripts on tf2wiki.net: http://tf2wiki.net/wiki/Pyro_scripts
- tcm_byte's config for medic: http://en.twitch.tv/tcm_byte (scroll down for the
  download-link)
- Chris' config: http://chrisdown.name/tf2/
- TF2mate: http://clugu.com/tf2mate/


How to use:
Copy all configs into "<steamfolder>\steamapps\common\Team Fortress 2\tf\cfg\".
Steamfolder is usually "c:\Program Files (x86)\Steam".


Additional infos:
- Some of my other settings:
  tf_dingaling_pitchmindmg "80"
  tf_dingaling_pitchmaxdmg "120"
  viewmodel_fov "90"
- My hitsound is a custom one
- I use chris' settings for bad connections (it's still better than defaults)
- My HUD is the eve hud: http://code.google.com/p/eve-tf2hud/


FAQ:

Q:Why don't you bind mouse4?
A: I use "bind mouse4 voicemenu 0 1" for saying thanks


TODO:
- Crtl-key unused. Any ideas?
