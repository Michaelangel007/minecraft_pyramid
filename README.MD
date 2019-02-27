# Minecraft Pyramid

Updated: Feb 27, 2019

Table of Contents

* [Introduction](https://github.com/Michaelangel007/minecraft_pyramid#introduction)
* [The Build](https://github.com/Michaelangel007/minecraft_pyramid#the-build)
* [Crops](https://github.com/Michaelangel007/minecraft_pyramid#crops)
* [Cactus XP Farm](https://github.com/Michaelangel007/minecraft_pyramid#cactus-xp-farm)
* [Sheep Farm](https://github.com/Michaelangel007/minecraft_pyramid#sheep-xp-farm)
* [Conclusion](https://github.com/Michaelangel007/minecraft_pyramid#conclusion)

# Introduction

The running gag with any serious Minecraft player is that they have 17+ projects being worked on simultaneously.

Well, I can finally scratch _one_ off my Minecraft Bucket List:

* [x] Build a Big-Ass Pyramid

This project also has a few other names:

* _"Engineering R Us"_
* _"This can't be good for my carpal tunnel."_

# The Build

This normal looking pyramid by day ...

* ![west_side_day.png](west_side_day.png)

... has a secret lurking by night:

* ![west_side_night.png](west_side_night.png)

I felt the creeper homage was appropiate. :-)

All joking aside it is located in our desert mining operation. Here is the view at night facign West when you first enter through the portal.

* ![portal_entrace_looking_left.png](portal_entrace_looking_left.png)

The pyramid is off to the right (North West) in the distance:

* ![portal_entrance_looking_right_east_side.png](portal_entrance_looking_right_east_side.png)

Moving along the path here is the view from the SE corner of the pyramid looking east to the portal entrace and north:

* ![south_east_corner_looking_north_and-east_to_portal_entrance.png](south_east_corner_looking_north_and-east_to_portal_entrance.png)

When we get to the East entrance here is the view at night looking south:

* ![night_east_side_facing_south_outside.png](night_east_side_facing_south_outside.png)

And looking up the East facing side with the "glowing" stairs.  I used "back-lighting" by placing torches on the inside which makes them "glow" at night.

* ![night_east_side_looking_up.png](night_east_side_looking_up.png)

Inside the pyramid facing East here is what the main entrance looks like. NOTE: I'm using Optifine + a custom shader which tints all light sources yellow (you can change the tint.)

* ![night_inside_facing_south_east.png](night_inside_facing_south_east.png)

One of the problems with any "big build" is lighting. Initially, I wasn't going to have any glass blocks but after realizing that the ceiling blocks all the light and having torches on the ground just wasn't going to cut it I decided to rip most of the East facing side and replace it with glass, stairs, and Jack O' Lanterns.

Originally I resisted replacing the blocks with glass due to not having enough yellow dye but after making a quick "dye farm" that literally spits out hundreds of red, orange, yellow or magenta dye a minute (!!) using a "burn-out" redstone torch clock and 2-tall flowers I went ahead.  The burnout clock are 5x3 blocks placed in a circle shape with redstone torches placed every other block which rapidly turns on and off dispensers with bonemeal placed in the 4 adjacent squares around a center flower.  The flower farm uses bonemeal on a double tall flower to make the flower grow and drop a duplicate of itself.  A hopper minecart below the dirt "sucks" the dropped flowers and then places them into a chest.

* [ ] TODO: Picture of Flower Farm

To keep the dispensors stocked each one has an attached double chest with bone meal.

* [ ] TODO: Picture of double chest with bone meal

Here is the morning view looking out the East side.

* ![morning_looking_out_east.png](morning_looking_out_east.png)

In hindsight I probably should of built more out of glass. Go figure when I'm in the middle of the desert with tons of sand that I can smelt into glass. =P

There are two circuits inside:

* The first circuit on a night sensor that turns on the Creeper lighting on the West side that was showcased above.
* The second circuit is also on a night sensor but on the North side.
The glowstone behind the stairs are on a delayed timing circuit that
makes them turn on in staggered delay increments as they going up the pyramid -- the goal was kind of like a poor man's animated "landing lights."  I haven't seen any UFO's yet though. =P

Each custom circuit took about an hour to design, wire-up, and debug.

* ![north_side_night.gif](north_side_night.gif)

The view from the top shows our 64 furnace "super smelter" off in the distance beyond East past the main portal entrance. It is an original design by zmrazit. A double chest feeds 32 furnaces on the north and 32 furnaces on the south. It uses the 1.13 kelp blocks as fuel since they last just as long as charcoal.  Smelting a double chest uses ~3 kelp block per furnace.

* ![view_from_top_looking_east_south.png](view_from_top_looking_east_south.png)

As you can tell I "splurged" and made the pyramid cap entirely out of gold blocks.  When you are rich and there is nothing else to spend them on so why not?


This 153 x 153 x 77 tall pyramid took about a week to build.  All 23,409 blocks were hand placed.

It's kind of funny to see Phantoms spawn inside. =P

* [ ] TODO: Picture of phantoms

I have a small glass house where you can safely AFK from the phantoms.

* [ ] TOOD: Picture of glass house


Here the north facing side is done before I decided what to do with the air gap.

* ![under_construction_north_side.png](under_construction_north_side.png)

This shot is from the SE corner.

* ![under_construction_looking_north_side.png](under_construction_looking_north_side.png)

I decided to go with a yellow glass theme.

* ![under_construction_north_gap_glass.png](under_construction_north_gap_glass.png)


# Crops

Inside, the South West corner holds mini farms of beets, carrots, netherwart, potatoes, and wheat. Press a button and water naturally flows down the terraces to harvest the crops funneling
them into a center collection water channel.

* [ ] TOOD: Picture of farms

Using the new 1.13 water mechanics items now float to the surface so there is a 
water bubble column to bring items up into chests.

* [ ] TODO: Picture of watter

Currently everything is being dumped into a bunch of double chests.
Eventually I'll add an item sorter.

* [ ] TODO: Picture of item sorter

The only way to automate _replanting_ of crops is to trap villagers with the crop.
I wanted to minimize lag since I already have a cactus XP farm (furnaces with carpet duper)
so I decided to pass on the villager virtual slave labor this time.


# Cactus XP Farm

The center of the pyramid features a multi-level cactus farm + cactus XP farm.

* [ ] TODO: Picutre of cactus fhttps://github.com/Michaelangel007/minecraft_pyramid#cactus-xp-farmarm

Each floor has 20 x 20 = 400 cactus.

Ilmango showed a very compact Minecraft 1.13 version "zero tick" cactus XP farm:

* [[24/7] Fully Automatic XP Farm 1.13.1+](https://www.youtube.com/watch?v=TEVrdTVflJk).

That is, it automates cactus growing by "shifting"  the sand underneath the cactus
in order to force trigger an update which causes the cactus to grow extremely fast.
It has numerous advantages ...

* Super compact
* Lag friendly; uses water streams to pull cactus and carpet into the furnaces
* Uses a carpet duper for infinite fuel

but one *major* disadvante:

* It is EXTREMELY noisy due to all the pistons firing moving the sand!

Given the choice between sounds of ...

* trickling/running water, or
* pistons _constantly_ firing

... I decided to go with the much larger water-based Minecraft 1.12 version.

Underneath is a water collection system that flushes the cactus into furnaces.

There is a master switch that duplicates carpet which is pulled into the furnaces
where they are used a fuel. There is also an automatic safety over-ride switch
that turns the carpet duper off if too much carpet is being produced and not consumed
fast enough.  A chest at the end of the fuel line has a comparator that sends
a redstone signal back to the on/off switch.

The cactus are smelted into green dye and then using an observer clock are 
dumped into a cactus where the dye is automatically destroyed.

To repair your items there is a level in front of each furnace where you can
"lock" the furnace. Then when the next cactus that is smelted the dye will stay
in the hopper.  When you manually remove it you will get a TON of XP due
to the furnace storing the XP from ALL the previously smelted cactus.

# Sheep Farm

* [ ] TODO: Pictures of sheep & dye

# Conclusion

On our "last season" on the server I built two bases:

* One in a jungle
* One in the middle of the ocean at sea level going down

The desert biome made for an interesting change of scenary
and was a good opportunity to try some different colors.
I took cues from traditional Egyptian colors: Yellow/Gold and Blue/Cobalt Turquoise.

* The yellow glass augments the sandstone well.

* I normally don't use tinted glass but the white stained glass looks really good.

* I barely used any blue / lapis colors. In the future I'll try to 
widen the color palette.

Now to finish those 10 floors of the Cactus XP farm inside ... :-)
