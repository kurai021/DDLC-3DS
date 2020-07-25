<div align="center">
  <img src="https://github.com/LukeZGD/DDLC-LOVE-Assets/raw/master/icon.png"/>
  <h1>DDLC-3DS</h1>
  <h3>Will you write the way into her heart?</h3>
</div>

**DDLC-3DS** is a Doki Doki Literature Club port for the **Nintendo 3DS (old and new)** Programmed in Lua, running under LovePotion and based in [LukeZGD's original work](https://github.com/LukeZGD/DDLC-LOVE) (go to thank him).

**This port is unofficial and is not affiliated with Team Salvato. Please support the official game. You can download Doki Doki Literature Club at: http://ddlc.moe**

## Some notes:
- Only the **latest [Luma3DS](https://github.com/AuroraWright/Luma3DS)** is supported.
- Make sure that `dspfirm.cdc` is dumped for audio to work (use [DSP1](https://github.com/zoogie/DSP1/releases))

## Usage:
- **.3dsx** - Put the `.3dsx` to the `3ds` folder to the root of your SD card. You can now run DDLC-LOVE from [The Homebrew Launcher](https://github.com/fincs/new-hbmenu)
- **.cia** - Install the `.cia` file from the [releases](https://github.com/LukeZGD/DDLC-LOVE/releases) using [FBI](https://github.com/Steveice10/FBI). You can now run DDLC-LOVE from the home menu

## Locations of save files:

- You can reset the save data and start over by deleting the save file folder. This is also mentioned in the help menu. The location is `sdmc:/3ds/data/LovePotion/DDLC-LOVE/`


## Building:
  1. Run `make 3dsx` for a .3dsx build or `make cia` for a .cia build.

### Credits:
- **LukeZGD** - [DDLC-Love](https://github.com/LukeZGD/DDLC-LOVE)
- **TurtleP** - [LovePotion](https://github.com/TurtleP/LovePotion)
- **GlowTranslations** - [Spanish translation](https://tinyurl.com/ddlcglow)
