Better documentation pending.

# Is this playable?
No, this is an 'engine' for creating game stuff.

# How do I run it?
Get Lua and do `lua moloch.lua`. Right now you also need LuaRocks and *at least* do `luarocks install yuescript`. There are other LuaRocks packages involved, which is a list that is currently rapidly changing. It'll be more well established here later.

# How do I poke around and modify it?
You need Lua. We use [Yuescript](https://yuescript.org) and previously we used [MoonScript](https://moonscript.org). Anything that can compile to Lua will work.

# There's no interface or menu or anything for configuring or otherwise setting up the game?
There's _gonna_ be! If you're looking for a 'game' or useful 'engine' right now, though, this ain't it just yet.

# YASDK would be impossible without
- [Yuescript](https://yuescript.org)
	- I can't stress enough just how fucking awesome Yuescript is.
- [MoonScript](https://moonscript.org)
	- I can't stress enough just how fucking awesome MoonScript is.
	- There would be no Yuescript without MoonScript.
- [BearLibTerminal](http://foo.wyrd.name/en:bearlibterminal)
	- YASDK would not exist without this.
- [MoonLibs](https://github.com/stetre/moonlibs)
  - These in particular:
    - [MoonSndFile - bindings to **libsndfile**](https://github.com/stetre/moonsndfile)
    - [MoonAL - bindings to **OpenAL**](https://github.com/stetre/moonal)
- [1bardesign's stuff](https://github.com/1bardesign)
	- `ferris` was the model for YASDK's ECS-like contraptions.
	- Some `batteries` were selectively pulled and rewritten.
- [rotLove](https://github.com/paulofmandown/rotLove)
	- A whole lot of what's in `class/` was ported from here and made, in my opinion, infinitely more portable.
	- rotLove is a port of `rot.js` for Love2D, so technically this credit is owed to `rot.js` as well. I've never opened `rot.js`, though.
- [FixedSys Excelsior](https://github.com/kika/fixedsys)
	- This is the font shipped with YASDK. It features a hell of a lot, is big enough for my poorly-protected vision, and still manages to stay fully on-point to the aesthetics of terminal games and _trve_ roguelikes.
- Loved ones
	- Friends
	- Family
	- Role models
		- You know who you are; I wouldn't be any serious depth into game development without you
	- Everyone else who supports and listens to my utterly deranged nonsense surrounding my projects
- My wife
	- Still a loved one; she just needed her own spot 
# Inspirations
- [Minetest](https://minetest.net)
- [UnRogue Engine](https://github.com/gilmore606/ure)
	- I would have taken to using this if I weren't wholly bent on using MoonScript for all my creations.
	- Seriously, check it out!
- [Dwarf Fortress](https://www.bay12games.com/dwarves)
- [The Ground Gives Way](https://thegroundgivesway.com)
- Space Station 13
	- ...conceptually. For a variety of reasons that differ wherever you happen to look, it's not great. It's got some great ideas, that said.
- Krigarheit
	- I wish I had something more concrete to link, but the guy behind this managed to do a lot of the same things I wanted to do first, the bastard!
- There's definitely more I don't remember

Licenses are all in LICENSE. Licenses of the libraries depended upon by *these* thirdparty libraries and so on and so forth can be found within those listed above, not here.
