---
layout: page
title: Mechanics
nav_order: 2
---

[Return to Home](../index.html){: .btn}

# Mechanical Reference
{: .no_toc .center}

<img class='bordered' src='../images/vloxx.webp'>

| **Health** |  84,939,840  |
| **Defiance Bar** | 6000 |
| **Armor** | 2597 (standard) |
| **Hitbox** | 180 (medium) |
| **Enrage** |  10 minutes, kills everyone on running out. |

This page contains a detailed reference of the various attacks and mechanics present in the encounter.

<details>
<summary><b>Table of Contents</b></summary>
<div markdown=block>
1. TOC
{:toc}

---
</div>
</details>

<img class=divider>

## Fight Structure

The battle against Vloxx is divided into three main phases, three split phases and a final phase. The main phases are each styled around one of his weapons: *Staff*, *Spear* and *Sword*.

Except for a few of attacks that are present throughout all phases, each main phase is limited to a subset of Vloxx's mechanics that are specific to the phase's weapon. The final phase instead alternates attacks from all three weapons.

Each split phase starts with Vloxx teleporting to the center of the arena and gaining <img class='inline defensive'> [Defensive Inspiration](). An enemy champion will them spawn, along with two elites. The type of enemy depends on the phase:
- 70% - [Cosmic Piercer](#split-phase-enemies)
- 40% - [Cosmic Bulwark](#split-phase-enemies)
- 10% - [Cosmic Sunderer](#split-phase-enemies)

Killing this champion unlock Vloxx's <img class='inline defiance'> [Defiance Bar], allowing the squad to break it and the fight to continue into the following phase.

---

### 100% - 70% - Staff Phase

Vloxx's staff is modeled after [Ancora Pax](https://wiki.guildwars2.com/wiki/Ancora_Pax). This phase is characterized by a large amount of projectiles: reflecting or blocking these can be potentially dangerous since some will bounce off, resulting in several potentially dangerous AoEs.

#### Weapon Skills
{:.no_toc}
[Annihilating Orb], [Ascension's Sacrifice], [Eternal Reflection], [Surrounding Curse]

---

### 70% - 40% - Spear Phase

Vloxx's spear is modeled after [Ancora Bellum](https://wiki.guildwars2.com/wiki/Ancora_Bellum). This phase is mostly characterized by [Worldpiercer] heavily limiting squad movement while [Raging Storm] requires either permanent projectile block or constant repositioning.

#### Weapon Skills
{:.no_toc}
[Cosmic Charge], [Raging Storm], [Thousand Strikes], [Worldpiercer]

---

### 40% - 10% - Sword Phase

Vloxx's sword is modeled after [Wages of Stars](https://wiki.guildwars2.com/wiki/Wages_of_Stars). This phase is characterized by a large amount of AoE Damage, especially from [Echoing Blade] and [Excision Extremis]. This requires a lot of attention from the group to either out-heal or avoid most of the danger.

#### Weapon Skills
{:.no_toc}
[Division Eternal], [Echoing Blade], [Excision Extremis], [Slice Through Reality]

---

### 10% - 0% - Final Phase

At the beginning of this phase, Vloxx will lose his external golem armor and transition into his final form. He will then cast [Threshold of Eternity], which will kill all players 2 minutes after the beginning of the phase. During this cast, Vloxx will constantly cycle through the same set of skills ad infinitum:
1. [Judgement of Eternity] (Greens)
2. [Surrounding Curse] (Small AoEs)
3. [Excision Extremis] (Swords)
4. [Probability Distribution] (Puddles)
5. [Raging Storm] (Spears)
6. [Excision Extremis] (Swords)

<img class=divider>

## General Mechanics

These mechanics are present for the entirety of the fight independent of the phase.

|**Mechanic**|**Common Name**|**Brief Description**|
| <img class='inline empowered'> [Empowered] | Stacks | Buff applied to Vloxx on failed mechanics. |
| <img class='inline ascension'> [Ascension] | Stacks | Buff applied to players to counteract <img class='inline empowered'> [Empowered]. |
| <img class='inline fixate'> [Fixate] | Tank | Randomly selects a player to become the target for Vloxx's attacks. |
| [Judgement of Eternity] | Greens | Three greens requiring three people each. |
| [Probability Distribution] | Pools | Three large AoEs that leave lingering pools. |

---

### <img class='inline empowered'> Empowered

<img class='inline empowered'> [Empowered] is an effect granted to Vloxx by several sources over the course of the encounter. Each stack grants him 5% increased outgoing damage and 1% reduced incoming damage, stacking additively. Additionally, Vloxx starts gaining boons at certain stack thresholds:
- At 5 <img class='inline empowered'> stacks, he periodically gains <img class='inline might'> [Might].
- At 15 <img class='inline empowered'> stacks, he periodically gains 25 <img class='inline might'> [Might].
- At 50 <img class='inline empowered'> stacks, he periodically gains <img class='inline resolution'> [Resolution].
- At 75 <img class='inline empowered'> stacks, he periodically gains <img class='inline protection'> [Protection].

Vloxx can gain <img class='inline empowered'> [Empowered] in three ways:
- [Champion Weapons](#weapons) will grant him one <img class='inline empowered'> stack 24 seconds after spawning and one additional <img class='inline empowered'> stack at 20 second intervals following.
- [Visions of Eternity] will grant him 10 <img class='inline empowered'> stacks when he either completes the cast or his <img class='inline defiance'> [Defiance Bar] is broken.
- Whenever a player loses one or more stacks of <img class='inline ascension'> [Ascension], Vloxx will gain an equivalent number of <img class='inline empowered'> [Empowered].

{: .note}
This counts dead players as well, since they "lose" 10 <img class='inline ascension'> stacks on dying. Vloxx will therefore gain 10 <img class='inline empowered'> [Empowered] for each dead player.

Additionally, whenever a player gains a stack of <img class='inline ascension'> [Ascension], Vloxx will *lose* a stack of <img class='inline empowered'> [Empowered].

---

### <img class='inline ascension'> Ascension

<img class='inline ascension'> [Ascension] is a player buff that is diametrically opposed to <img class='inline empowered'> [Empowered]. All players will begin the encounter with 10 <img class='inline ascension'> stacks, and will immediately die if they ever reach zero.

Players *lose* <img class='inline ascension'> stacks whenever they fail certain mechanics:
- [Judgement of Eternity] - if a green fails, each player inside it loses 3 <img class='inline ascension'> stacks.
- [Ascension's Sacrifice] - if a chain fails, the chained player loses a <img class='inline ascension'> stack.

Whenever a player loses <img class='inline ascension'> stacks, Vloxx will gain the same number of <img class='inline empowered'> [Empowered].

Players will *gain* <img class='inline ascension'> stacks whenever they pick up *orbs*. Three of these drop from [Champion Weapons](#weapons) whenever their <img class='inline defiance'> [Defiance Bar] is broken.

---

### <img class='inline fixate'> Fixate

This effect is applied to a random player in Vloxx's cone of vision. If no one is in sight, it will select the closest person instead. This player will gain an <img class='inline fixate-icon'> icon over their head showing the effect, and will become the target for most of Vloxx's skills.

The effect lasts for 60 seconds, and is re-assigned 10 seconds after running out.

---

### Judgement of Eternity

Targets the <img class='inline fixate-icon'> [Fixated] player and the two closest non-fixated players with a green, requiring three people inside. Failing to solve a green will remove two stacks of <img class='inline ascension'> [Ascension] from all players inside its area and <img class='inline float'> [Float] them.

Players standing in multiple greens will go <img class='inline invuln'> [Downstate]. This cannot be prevented by damage immunity or invulnerability effects such as <img class='inline no-yield'> [We Will Never Yield!](https://wiki.guildwars2.com/wiki/%22We_Will_Never_Yield!%22) or <img class='inline august-queen'> [Tale of the August Queen](https://wiki.guildwars2.com/wiki/Tale_of_the_August_Queen), unlike other similar mechanics.

Greens have a maximum range of 3000 units. The number of greens in this mechanic depends on the number of living players: with less players alive, fewer greens will spawn so that the mechanic is always solvable.

---

### Probability Distribution

Summons large AoEs on the <img class='inline fixate-icon'> [Fixate] and two additional random players. After tracking their targets for five seconds, they will become stationary. Players then have three seconds to leave their area while they fill and turn into stationary pools, which pulse damage, strip boons and inflict <img class='inline cripple'> [Cripple] on anyone in their area.

AoEs can and should be stacked together to save space.

<img class=divider>

## Enemies

The Nexus of Eternity encounter is characterized by a large amount of enemy adds that enter the picture at different points in the encounter. These can mostly be divided into two groups: *split phase adds* and *weapon adds*.

---

### Weapons

These are three Champion Weapons, one for each of Vloxx's weapons:

<div class="alt-row-container">

<div class='center adapt-width-30' markdown=block>
#### Aspect of the Staff
{: .no_toc}
<img class='center margins' width="70%" src='./staff.webp'>
Spawns at the beginning of the fight. Can use the skills: [Eternal Reflection], [Surrounding Curse].
</div>

<div class='center adapt-width-30' markdown=block>
#### Aspect of the Spear
{: .no_toc}
<img class='center margins' width="70%" src='./spear.webp'>
Spawns at the beginning of the first split phase (70%). Can use the skills: [Cosmic Charge], [Thousand Strikes].
</div>

<div class='center adapt-width-30' markdown=block>
#### Aspect of the Sword
{: .no_toc}

[No Image Yet]

Spawns at the beginning of the second split phase (40%). Can use the skills: [Division Eternal], [Excision Extremis].
</div>

</div>

#### Champion Weapon
{: .no_toc .center}

| **Health** |  4,620,570  |
| **Defiance Bar** | 1000 |
| **Armor** | 2597 (standard) |
| **Hitbox** | 100 (small) |

Champion weapons spawn in before their associated split phase. They gain a CC bar at 25% HP. When this bar is broken or when the add is killed, they will spawn in three orbs that when picked up by a player will grant them a stack of <img class='inline ascension'> [Ascension], removing a stack of <img class='inline empowered'> [Empowered] from the Vloxx. These orbs can only be spawned once per add. Once a weapon is killed, it will respawn 40 seconds later.

Weapons will grant Vloxx a stack of <img class='inline empowered'> [Empowered] 24 seconds after spawning, and at 20 second intervals following.

{: .note}
This means that weapons should be killed at most 84 seconds after spawning to be neutral on <img class='inline empowered'> [Empowered]. The <img class='inline achievement'> [True Visionary](https://wiki.guildwars2.com/wiki/The_Nexus_of_Eternity) achievement, which involves ending on less than 10 stacks, requires killing seven champions in less than 24 seconds, or 11 champions in less than 44 seconds, or 21 champions in less than 64 seconds.


---

### Elementals

There are three elemental types: the *Cosmic Piercer*, the *Cosmic Bulwark* and the *Cosmic Sunderer*.

<div class="alt-row-container">

<div class='center adapt-width-30' markdown=block>
#### Cosmic Piercer
{: .no_toc}
<img class='center margins' width="70%" src='./piercer.webp'>
Spawns during the 70% split phase. Summons waves of projectiles and teleports.
</div>

<div class='center adapt-width-30' markdown=block>
#### Cosmic Bulwark
{: .no_toc}
<img class='center margins' width="70%" src='./bulwark.webp'>
Spawns during the 40% split phase. Charges and knocks down enemies.
</div>

<div class='center adapt-width-30' markdown=block>
#### Cosmic Sunderer
{: .no_toc}
<img class='center margins' width="70%" src='./sunderer.webp'>
Spawns during the 10% split phase. He looks cool for a bit, I guess.
</div>

</div>

#### Champion Elemental
{: .no_toc .center}

| **Health** |  1,592,622  |
| **Defiance Bar** | 1000 |
| **Armor** | 2597 (standard) |
| **Hitbox** | 100 (small) |

A champion and three Elite versions of are spawned at the beginning of each split phase as a part of the cast of [Visions of Eternity]. Killing these adds is necessary to unlock Vloxx's <img class='inline defiance'> [Defiance Bar] and progress the encounter.

<img class=divider>

## Staff Attacks

These attacks can be used by Vloxx during the first phase or the final phase, and by the [Champion Staff].

|**Mechanic**|**Common Name**|**Brief Description**|
| [Annihilating Orb] | Orb, Teleport | Launches a massive orb in a line, then teleports to its final location. |

### Annihilating Orb

### Ascension's Sacrifice

### Eternal Reflection

### Surrounding Curse

<img class=divider>

## Spear Attacks

### Cosmic Charge

### Raging Storm

### Thousand Strikes

### Worldpiercer

<img class=divider>

## Sword Attacks

### Division Eternal

### Echoing Blade

### Excision Extremis

### Slice Through Reality

<img class=divider>

## Special Attacks

### Visions of Eternity

### Threshold of Eternity

<img class=divider>

[Return to Home](../index.html){: .btn} [Return to Top](#mechanical-reference){: .btn .fixed}


<!-- Links to other pages in the guide -->
[Judgement of Eternity]: #judgement-of-eternity
[Probability Distribution]: #probability-distribution
[Visions of Eternity]: #visions-of-eternity
[Threshold of Eternity]: #threshold-of-eternity
[Annihilating Orb]: #annihilating-orb
[Ascension's Sacrifice]: #ascensions-sacrifice
[Eternal Reflection]: #eternal-reflection
[Surrounding Curse]: #surrounding-curse
[Cosmic Charge]: #cosmic-charge
[Raging Storm]: #raging-storm
[Thousand Strikes]: #thousand-strikes
[Worldpiercer]: #worldpiercer
[Division Eternal]: #division-eternal
[Echoing Blade]: #echoing-blade
[Excision Extremis]: #excision-extremis
[Slice Through Reality]: #slice-through-reality

[Ascension]: #-ascension
[Empowered]: #-empowered
[Fixate]: #-fixate
[Fixated]: #-fixate

<!-- Links to classes and specializations -->

<!-- Links to player skills -->

<!-- Links to buffs and debuffs -->
[Invulnerable]: https://wiki.guildwars2.com/wiki/Invulnerability
[Might]: https://wiki.guildwars2.com/wiki/Might
[Resolution]: https://wiki.guildwars2.com/wiki/Resolution
[Protection]: https://wiki.guildwars2.com/wiki/Protection
[Float]: https://wiki.guildwars2.com/wiki/Float
[Downstate]: https://wiki.guildwars2.com/wiki/Downstate
[Cripple]: https://wiki.guildwars2.com/wiki/Cripple

<!-- Links to enemies and enemy skills -->
[Champion Staff]: #weapons
[Champion Spear]: #weapons
[Champion Sword]: #weapons

<!-- Other -->
[Defiance Bar]: https://wiki.guildwars2.com/wiki/Defiance_bar
