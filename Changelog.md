**Version: 0.3.0**

**Config**

Ftb quests progress

---------------------------------------------------------

**Version: 0.2.0**

**Config**

Hide quark menu message

KubeJS
 - Hide ae2 facades but still allow to be crafted
 - Hide twilight forest uncrafter and disable uncrafting
 - Hide and get rid of cyclic uncrafter, sleeping mat, and crafter
 - Remove create draining, automatic shapeless, automatic shaped, automatic packaging, automatic packing categories
 - Prevent mob grinding utils from spawning forbidden arcanus lost souls
 - Replace draconic evolution draconium core recipe
 - Replace draconic evolution wyvern core recipe
 - Replace draconic evolution draconium core recipe
 - Replace avaritia diamond lattice recipe
 - Replace avaritia crystal matrix recipe
 - Replace extreme crafting table recipe

FTB Quests
 - Avaritia line progress
 - Draconic evolution line progress

Create
 - hosePulleyBlockThreshold = 10000 -> 125

**Update**

Update create crafts & additions

Update cupboard

Update extreme reactors

Update moonlight lib

Update EnderIO

**Add**

Add create new age

Add compressed blocks

Add botany pots

Add botany trees

Add botany pots tiers

Add resource chickens

**Remove**

Remove create teleporters - redundant/waystones/5+ other ways to teleport

Remove create goggles - engineer's goggles in base create

Remove create jetpack - redundant/iron's jetpacks and other create jetpacks

Remove create utilities - breaks intent of create

Remove charging gadgets - only adds 1 block and it is currently pointless

Remove aquatic torches - can just use glowstone or lamps or other torches that work underwater

---------------------------------------------------------

**Version: 0.1.0**

**Config**

Sparse Structures

 - "spreadFactor": 2 -> 2.5

Mahou Tsukai
 - Drain life
   - DRAIN_LIFE_BARRIER_MANA_COST = 5 -> 12
   - DRAIN_LIFE_BARRIER_RADIUS = 10 -> 5
   - DRAIN_LIFE_DAMAGE = 2.0 -> 5.0
 - Power Consolidation
   - POWER_CONSOLIDATION_SWORD_MANA_COST = 5000 -> 10000
 - Clarent
   - CLARENT_UNBREAKABLE = true -> false
   - CLARENT_ATTACK_CAP = 5000000 -> 300
 - Replica
   - REPLICA_BASE_DAMAGE = 4.0 -> 10.0
   - REPLICA_TELEPORT_MANA_COST = 300 -> 800
   - REPLICA_ATTACK_MANA_COST = 30 -> 1000
   - REPLICA_SHOCKWAVE_COOLDOWN = 50 -> 120
   - REPLICA_MAX_DAMAGE = 5000000.0 -> 200.0
 - Reality marble
   - MARBLE_MANA_COST = 4000 -> 500000 (effectively disables it)
 - Damage exchange
   - DAMAGE_EXCHANGE_MANA_COST = 40 -> 1000
   - DAMAGE_EXCHANGE_REDUCE_TO = 1.0 -> 0.0
   - DAMAGE_EXCHANGE_CAP = 5 -> 500

In Control
 - Initial mob limits

Just another mining dimension
 - Mining
   - Clay
     - "ore_size": 33 -> 10
   - Granite
     - "ore_size": 64 -> 32
   - Andesite
     - "ore_size": 64 -> 32
   - Diorite
     - "ore_size": 64 -> 32

Building gadgets 2
 - rayTraceRange = 32 -> 64

Ensorcellation
 - Magic protection
   - "Max Level" = 4 -> 7
 - Leech
   - "Max Level" = 4 -> 6
 - Magic edge
   - "Max Level" = 3 -> 6
 - Vorpal
   - "Max Level" = 3 -> 7

Apotheosis
 - Protection
   - I:"Max Level"=2 -> 8
 - Fire protection
   - I:"Max Level"=9 -> 6
 - Feather falling
   - I:"Max Level"=11 -> 8
 - Blast protection
   - I:"Max Level"=9 -> 6
 - Projectile protection
   - I:"Max Level"=11 -> 6
 - Frost walker
   - I:"Max Level"=7 -> 2
 - Sharpness
   - I:"Max Level"=9 -> 12
 - Looting
   - I:"Max Level"=8 -> 6
 - Efficiency
   - I:"Max Level"=9 -> 8
 - Fortune
   - I:"Max Level"=8 -> 6
 - Berserkers fury
   - I:"Max Level"=3 -> 10
 - Knowledge
   - I:"Max Level"=3 -> 5
 - Life mending
   - I:"Max Level"=3 -> 7
 - Mana regen
   - I:"Max Level"=7 -> 9
 - Mana boost
   - I:"Max Level"=7 -> 9
 - Life stealing
   - I:"Max Level"=6 -> 8
 - Magic protection
   - I:"Max Level"=9 -> 10

FTB Quests

**Update**

Update Balm

Update Cyclops core

Update Evilcraft

Update Integrated Dynamics

Update Integrated Terminals

Update JAOPCA

Update The Twilight Forest

**Add**

Added custom emoji datapack

Add easy villagers

---------------------------------------------------------

**Version: 0.0.9**

**Config**

Quest chapters

Scaling Health - Will tune overtime
 - blight render = true -> false
 - enableBlights = true -> false
 - Datapack created
   - Difficulty exemptions/villagers, wandering traders
   - Damage scaling hostiles not peacefuls
   - Max difficulty 50
   - Difficulty fine tuning on kills, lunar cycle, dimension, biome
   - Player max health 100, min health 20, starting health 20

Clean tooltips
 - Disable durability tooltip in favor of durability tooltips

No Chat Reports
 - "showEncryptionButton": true -> false
 - "demandOnClient": false -> true

Emojiful - Remove all existing emojis because of lag, going to put in new emojis eventually
 - twemoji = true -> false
 - custom = true -> false

EnderIO
 - darkSteelLadderBoost = 0.15 -> 0.20

Create
 - bulkPressing = false -> true
 - crushingDamage = 4 -> 6
 - vaultCapacity = 20 -> 30

Elevator ID
 - sameColor = false -> true

Ensorcellation
 - "Mobs Teleport Players" = false -> true
 - "Mobs Knockback Players" = false -> true

Extra storage
 - base_energy = 15 -> 25

Packagedauto
 - energy_capacity = 5000 -> 7000
 - energy_req = 500 -> 1000
 - energy_usage = 100 -> 200

Railways
 - realisticTrains = false -> true

Rftools base
 - maxInfuse = 256 -> 512
 - usePerTick = 600 -> 1000

Sophisticated backpacks
 - allowOpeningOtherPlayerBackpacks = true -> false
 - inventorySlotCount = 81 -> 91
 - inventorySlotCount = 108 -> 120
 - inventorySlotCount = 120 -> 136
 - playJukebox = true -> false

**Update**

Updated Create Crafts & Additions

Updated GeckoLib

**Add**

Add Comforts

Add In Control

**Remove**

Remove passive skill tree additions

Remove building wands - redundant (building gadgets)

Remove exchangers - redundant (building gadgets)

Remove Better Tag NBT Tips

**Recipes**

Remove temporary void portal recipe

Remove default mahou tsukai mortar and pestle recipe

Add mahou tsukai mortar and pestle recipe

---------------------------------------------------------

**Version: 0.0.8**

**Config**

Mahou Tsukai
 - Mahou resets on death
 - Innate cap -> 100
 - Mahou required to increase capacity 100 -> 250
 - Mahou required to increase capacity percent of max mana 0.0 -> 0.1
 - Mahou maximum amount of mana required for increase 100 -> 10000

XNet Gasses
 - maxGasRateNormal 1000 -> 50000
 - maxGasRateAdvanced 5000 -> 100000

XNet
 - maxFluidRateNormal 1000 -> 50000
 - maxFluidRateAdvanced -> 5000 -> 100000

SOL Carrot Edition
 - milestones = [5, 10, 15, 20, 25] -> 5, 10, 15, 20, 25, 30, 35, 40, 45, 50, 55, 60, 65, 70, 75, 80, 85, 90, 95, 100

FTBChunks
 - fake_players: "check" -> allow
 - force_load_mode: "default" -> always

Trash Cans
 - Allow void nuclear waste false -> true

Powah
 - "dry_ice_veins_per_chunk": 9 -> 3
 - Reactors
   - Generation rate "nitro": 500000 -> 1000000
   - Transfer rate "nitro": 2000000 -> 4000000

Recipe essentials
 - "disableRecipebook": false -> true

Passive skill tree
 - "Maximum skill points" = 85 -> 105

Waystones
 - maximumBaseXpCost = 3.0 -> 30.0
 - frequency = 25 -> 10

Updated base defaultconfigs to include new mods

**Add**

Add Mahou Tsukai

Add Passive Skill Tree

Add Passive Skill Tree Additions

Add Scaling Health

---------------------------------------------------------

**Version: 0.0.7**

**Config**

Disable silent gear starter blueprints

Log begone
 - Disable apotheosis rogue spawner error message
 - Disabled other log spam messages

Re-unbound all keybinds

Performed terrain gen speed test with spark enabled

Adjusted main menu more


**Add**

Created datapack to disable Iron's Spells and Spellbooks guidebook from spawning on spawn

Add base defaultconfigs

Add log begone

Add sparse structures reforged

**Update**

EnderIO

JAOPCA

Moonlight Lib

Supplementaries

**Quests**

Prepare chapters
 - Getting Started
 - Challenges
 - End Game
 - Actually end game
   - Avaritia
   -  Draconic Evolution

---------------------------------------------------------

**Version: 0.0.6**

**Config**

Remove TOP book on spawn

Changed around title screen


**Added**

Changelog screen


**Update**

Update Embeddium

Update EnderIO

---------------------------------------------------------

**Version: 0.0.5**

**Config**

Changed the recipes for the consumables of Apotheosis spawners

Changed the recipe for the Void Portal (Temp to live in when we go into testing mode).

Changed the lootr texture back to the original one.

**Added**

Add Better Tag NBT.

---------------------------------------------------------

**Version: 0.0.4**

**Config**

Quark
  "Monster Box" = true -> "Monster Box" = false

Adjust Embeddium default options

Clear default keybinds

Almost unified
   Mod priorities
   Tags
   Materials
   Ignored Items

Apotheosis
  the_end|rare|mythic -> the_end|rare|epic|mythic
  "Boss Announce Range"=96.0 -> "Boss Announce Range"=32.0
  "Boss Announce Volume"=0.75 -> "Boss Announce Volume"=0.50
 
   "Cactus Height"=5 -> "Cactus Height"=12
   "Reed Height"=255 -> "Reed Height"=18

Fancy Menu
   Title image change (Placeholder?)
   Menu button change

**Added**

Add Global Packs
  Created apotheosis datapack to disable rogue spawners

Add JAOPCA

Add UtilitiX

Add Neat

Add JEI Integration

Add Architect's Palette

Add Iron's Spells 'n Spellbooks

Add Reliquary Reincarnations

Add Gateways to Eternity

Add Ensorcellation

Add EvilCraft

Add Apotheotic Additions

Add Super Saturation

Add Radium Reforged

Add No Chat Reports

Add Login Protection

---------------------------------------------------------

**Version: 0.0.3**

**Updated**

Downgraded FLIB 0.0.12

**Removed**

Removed Ultimine 

Removed Valhesa / Valhesa Core.


**Config**


Changed a few configs (Alex Caves, Quark, Apotheosis).

---------------------------------------------------------

**Version: 0.0.2**

Convert everything to CurseForge

Convert to Forge from NeoForge

Removed some unnecessary and duplicate mods


**Added**

Add KubeJS Create, Thermal

Add Draconic Additions

Add Apothic Curios

Add ME Requester

Add ExtendedAE

Add FTB Ultimine

Add Overloaded Armor Bar

Add Observable

Add Better Compatibility Checker

Add Better chunk loading

Add Chunk Pregenerator

Add Client Crafting

Add Configured

Add Connectivity

Add Default Options

Add Embeddium

Add Embeddium++

Add Entity Culling

Add Extreme sound muffler

Add FastSuite

Add Fast Workbench

Add Fast Async World Save

Add FPS Reducer

Add Get It Together, Drops!

Add fix GPU memory leak

Add ImmediatelyFast

Add ModernFix

Add Recipe Essentials

Add Saturn

Add Server Performance - Smooth Chunk Save

Add Structure Essentials

Add Shrink

Add Refined Storage Requestify

Add Refined Polymorhism

Add Enchantment Descriptions

Add FancyMenu - (Need to customize)

Add Artifacts

Add FTB Ultimine

Add JAMD

Add Cognition

Add Glassential

Add Eccentric Tome

Add Emojiful - (Need to configure)

Add Extreme Reactors

Add Functional Storage

Add Hostile Neural Networks - (Need to add mobs)

Add Hyperbox

Add Iron Jetpacks

Add Item Collectors

Add More Overlays Updated

Add Pedestals

Add Pylons

Add RFTools Builder

Add RFTools Utility

Add Supplementaries

Add FLIB

Add CoFH Core

Add MowLib

---------------------------------------------------------

**Version: 0.0.1**

Convert everything to CurseForge

Convert to Forge

Removed some unnecessary and duplicate mods

**Added**

Add KubeJS Create, Thermal

Add Draconic Additions

Add Apothic Curios

Add ME Requester

Add ExtendedAE

Add FTB Ultimine

Add Overloaded Armor Bar

Add Observable
