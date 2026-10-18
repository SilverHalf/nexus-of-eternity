---
layout: page
title: Mechanics
nav_order: 2
---

[Return to Home](../index.html){: .btn} [Strategy Guide](../strategy/index.html){: .btn}

# Vloxx
{: .no_toc .center}

<img class='bordered' src='../images/vloxx.webp'>

| **Health** |  84'939'840 (CM), 102'777'208 (LM) |
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
</div>
</details>

<img class=divider>

## Fight Structure

The battle against Vloxx is divided into three main phases, three split phases and a final phase.

---

### Main Phases

Vloxx's main phases are styled around his three weapons: *Staff*, *Spear* and *Sword*. Each one is mostly limited to a set of mechanics specific to the phase's weapon, plus a few attacks that are present in all three.

Vloxx's behaviour in the main phases is based on a priority-cooldown system:
- All active mechanics have their own *cooldown* and *priority*.
- The boss will always cast the highest priority skill that is off-cooldown.

While this is similar in concept to bosses such as [Greer](https://silverhalf.github.io/mount-balrior/greer/overview.html) and [Ura](https://silverhalf.github.io/mount-balrior/ura/overview.html), in practice Vloxx's relatively short cooldowns and absence of skill interruptions means the boss will usually present the same order of mechanics consistently for each phase. Exceptions to this standard order occur in high DPS situations, where skills do not have the time to come off-cooldown after split phases.

<div class="sidebar-background" markdown=block>
#### 100% - 70% - Staff Phase
{: .no_toc}
Vloxx's staff is modeled after [Ancora Pax](https://wiki.guildwars2.com/wiki/Ancora_Pax). This phase is characterized by a large amount of projectiles: reflecting or blocking these can be potentially dangerous since some will bounce off, resulting in several potentially dangerous AoEs.

*Weapon Skills:* [Annihilating Orb], [Ascension's Sacrifice], [Eternal Reflection], [Surrounding Curse]
</div>

<div style="padding:10px" markdown=block>
#### 70% - 40% - Spear Phase
{: .no_toc}
Vloxx's spear is modeled after [Ancora Bellum](https://wiki.guildwars2.com/wiki/Ancora_Bellum). This phase is mostly characterized by [Worldpiercer] heavily limiting squad movement while [Raging Storm] requires either permanent projectile block or constant repositioning.

*Weapon Skills:* [Cosmic Charge], [Raging Storm], [Thousand Strikes], [Worldpiercer]
</div>

<div class="sidebar-background" markdown=block>
#### 40% - 10% - Sword Phase
{: .no_toc}
Vloxx's sword is modeled after [Wages of Stars](https://wiki.guildwars2.com/wiki/Wages_of_Stars). This phase is characterized by a large amount of AoE Damage, especially from [Echoing Blade] and [Excision Extremis]. This requires a lot of attention from the group to either out-heal or avoid most of the danger.

*Weapon Skills:* [Division Eternal], [Echoing Blade], [Excision Extremis], [Slice Through Reality]
</div>

---

### Split Phases

Each split phase starts with Vloxx teleporting to the center of the arena and gaining <img class='inline defensive'> [Defensive Inspiration](). An enemy champion will them spawn, along with two elites. The type of enemy depends on the phase:
- 70% - [Cosmic Piercer](#split-phase-enemies) champion and elites.
- 40% - [Cosmic Bulwark](#split-phase-enemies) champion, [Cosmic Piercer](#split-phase-enemies) elites.
- 10% - [Cosmic Sunderer](#split-phase-enemies) champion, [Cosmic Piercer](#split-phase-enemies) and [Cosmic Bulwark](#split-phase-enemies) elites.

{: .legendary}
All enemies summoned in split phases will be Champion versions instead.

Killing all three enemies unlocks Vloxx's <img class='inline defiance'> [Defiance Bar], allowing the squad to break it and continue into the following phase.

---

### Final Phase

At the beginning of this phase, Vloxx will transition into his final form. He will then cast [Threshold of Eternity], which kills all players 2 minutes after the beginning of the phase. During this cast, Vloxx will constantly cycle through the same set of skills ad infinitum:
1. [Judgement of Eternity] (Greens)
2. [Surrounding Curse] (Small AoEs)
3. [Excision Extremis] (Swords)
4. [Probability Distribution] (Puddles)
5. [Raging Storm] (Spears)
6. [Excision Extremis] (Swords)

This makes for a challenging phase, since incoming damage and mechanical pressure are extremely high up until the boss dies.

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
- [Judgement of Eternity] - every player inside a green when it fails loses 3 <img class='inline ascension'> stacks.
- [Ascension's Sacrifice] - if a chain fails, the chained player loses a <img class='inline ascension'> stack.
- [Slice Through Reality] - every player that is dragged into the teleport area after it spawns loses a <img class='inline ascension'> stack.

Whenever a player loses <img class='inline ascension'> stacks, Vloxx will gain the same number of <img class='inline empowered'> [Empowered].

Players will *gain* <img class='inline ascension'> stacks whenever they pick up *orbs*. Three of these drop from [Champion Weapons](#weapons) whenever their <img class='inline defiance'> [Defiance Bar] is broken.

---

### <img class='inline fixate'> Fixate

This effect is applied to a random player in Vloxx's cone of vision. If no one is in sight, it will select the closest person instead. This player will hear an audio cue and gain an <img class='inline fixate-icon'> icon over their head showing the effect. They will then become the primary target for most of Vloxx's skills.

The effect lasts for 60 seconds, and is re-assigned 10 seconds after running out.

---

### Judgement of Eternity

<div class='sidebar-background row-container margins'>

<div class='adapt-width'>
<video class='bordered center' width="100%" controls>
<source src='../videos/judgement-of-eternity.mp4' type='video/mp4'>
</video>
</div>

<div class='adapt-width' markdown=block>

|*Common Name*| Greens |
|*Used By*| Vloxx |
|*Used in Phases*| All |
|*Cooldown*| 40 seconds |

</div>

</div>

Targets the <img class='inline fixate-icon'> [Fixated] player and the two closest non-fixated players with a green, requiring three people inside. Failing to solve a green deals moderate damage, applies <img class='inline burning'> [Burning], <img class='inline chilled'> [Chilled] and <img class='inline float'> [Float], and removes three stacks of <img class='inline ascension'> [Ascension] from all players in its area.

Players standing in multiple greens will go <img class='inline invuln'> [Downstate]. This cannot be prevented by damage immunity or invulnerability effects such as <img class='inline no-yield'> [We Will Never Yield!] or <img class='inline august-queen'> [Tale of the August Queen], unlike other similar mechanics. Additionally, they are not counted as being inside either green, possibly leading them to fail.

Greens have a maximum range of 3000 units. The number of greens in this mechanic depends on the number of living players: with less players alive, fewer greens will spawn so that the mechanic is always solvable.

#### Strategy
{: .no_toc}
It is customary to choose two players to act as *green baiters*. These are usually melee DPS or boonDPS, and their job is to stay inside the boss's hitbox in order to get targeted by this mechanic.

The squad can be divided then into three groups of three people, usually called *left*, *mid* and *right*. Each group will have an *anchor*, representing the location where the group will stack inside a green. These *anchors* are usually the two *green baiters* for the side groups, and the <img class='inline tag'> tag for the middle group. The tenth person has a special role, and is usually called the *joker* or the *float*. 

<img class='center' width='80%' src='./greens/green-strategy.webp'>

When solving greens, all three groups will position referenced to the tag, with each anchor taking a side. Improvisation depends on who is selected as the <img class='inline fixate-icon'> [Fixate], as this is always selected randomly. Ideally the fixate should always be in the center, as this makes it easier to bait out mechanics in a determined direction.

The easiest situation is when the <img class='inline fixate-icon'> [Fixate] is selected from the middle group. In this case, no additional adjustments are necessary and players can simply stack on top of their anchors to solve the mechanic. 

<img class='center' width='70%' src='./greens/green-strategy-1.webp'>

If the <img class='inline fixate-icon'> [Fixate] is selected from a side group, they should move to the middle group with their green and call what group they are from (usually "backup left/right/arrow/circle"). The *float* can then move to that group to even out the numbers. 

<img class='center' width='70%' src='./greens/green-strategy-2.webp'>

If the <img class='inline fixate-icon'> [Fixate] is also an *anchor*, then an additional step is required, as the float will have to bait a green instead of them. Anchors should also communicate when they specifically are fixated (usually "left/right/arrow/circle anchor fixated").

<img class='center' width='70%' src='./greens/green-strategy-3.webp'>

---

### Probability Distribution

<div class='sidebar-background row-container margins'>

<div class='adapt-width'>
<video class='bordered center' width="100%" controls>
<source src='../videos/probability-distribution.mp4' type='video/mp4'>
</video>
</div>

<div class='adapt-width' markdown=block>

|*Common Name*| Large AoEs, Puddles |
|*Used By*| Vloxx |
|*Used in Phases*| All |
|*Cooldown*| 30 seconds |

</div>

</div>

Targets the <img class='inline fixate-icon'> [Fixate] and two additional random players with large tracking AoEs. After following their targets for five seconds, they will become stationary and explode three second later, dealing moderate damage and inflicting <img class='inline knockback'> [Knockback] and <img class='inline poison'> [Poison] to any players in the area and turning into stationary pools.

Pools two pulse damage and inflict <img class='inline cripple'> [Crippled], and last for two minutes or until the next phase change.

#### Strategy
{: .no_toc}
This attack has no indicator except for the AoE, so it is relatively common for players not to realize when they are targeted. The common solution is to "wiggle" when the AoEs appear, which makes it easier to see who is targeted (similar to what occurs on KO CM).

<img class=divider>

## Staff Attacks

These attacks can be used by Vloxx during the first phase or the final phase, or by the [Champion Staff].

|**Mechanic**|**Common Name**|**Brief Description**|
| [Annihilating Orb] | Orb, Teleport | Launches a massive orb in a line, then teleports to its final location. |
| [Ascension's Sacrifice] | Chains | Targets players with chains that require a friend. |
| [Eternal Reflection] | Cone, Barrage | Launches a barrage of exploding projectiles in a cone. |
| [Surrounding Curse] | Small AoEs | Summons a rain of projectiles on the group. |

---

### Annihilating Orb

<div class='sidebar-background row-container margins'>

<div class='adapt-width'>
<video class='bordered center' width="100%" controls>
<source src='../videos/annihilating-orb.mp4' type='video/mp4'>
</video>
</div>

<div class='adapt-width' markdown=block>

|*Common Name*| Orb, Port |
|*Used By*| Vloxx |
|*Used in Phases*| [Phase 1] |
|*Cooldown*| 30 seconds |

</div>

</div>

Launches a massive orb towards the <img class='inline fixate-icon'> [Fixated] player, indicating the direction with a large arrow. The orb inflicts <img class='inline slow'> [Slow], <img class='inline burning'> [Burning] and <img class='inline knockback'> [Knockback] to players in its area. Once it reaches its maximum range of 1500 units, Vloxx teleports to it, unleashing a shockwave that deals damage and inflicts <img class='inline knockback'> [Knockback].

After teleporting, Vloxx will maintain an aura for a few seconds that continues to <img class='inline knockback'> [Knockback] and <img class='inline slow'> [Slow] players.

{: .warning}
There is a common bug where the shockwave from this attack is invisible. Always try to dodge or jump, even if you cannot see it.

#### Strategy
{: .no_toc}
Supports should provide <img class='inline aegis'> [Aegis] or <img class='inline stability'> [Stability] for the initial <img class='inline knockback'> [Knockback] and ideally also for the secondary shockwave. <img class='inline superspeed'> [Superspeed] is also extremely useful to increase damage uptime and improve positioning.

---

### Ascension's Sacrifice

<div class='sidebar-background row-container margins'>

<div class='adapt-width'>
<video class='bordered center' width="100%" controls>
<source src='../videos/ascensions-sacrifice.mp4' type='video/mp4'>
</video>
</div>

<div class='adapt-width' markdown=block>

|*Common Name*| Stunbreak, Greens, Chains |
|*Used By*| Vloxx |
|*Used in Phases*| [Phase 1] |
|*Cooldown*| est. 45 seconds |

</div>

</div>

Three players, including the <img class='inline fixate-icon'> [Fixate], will get targeted by chains. These <img class='inline float'> [Float] and push away the chained player, summoning a small green below them that requires two players to solve. Failing to solve a green will <img class='inline float'> [Float] the chained player a second time and remove a stack of <img class='inline ascension'> [Ascension] from them.

Players standing in multiple greens will go <img class='inline invuln'> [Downstate]. This cannot be prevented by damage immunity or invulnerability effects such as <img class='inline no-yield'> [We Will Never Yield!] or <img class='inline august-queen'> [Tale of the August Queen], unlike other similar mechanics.

#### Strategy
{: .no_toc}
To improve damage uptime overall, supports should <img class='inline stunbreak'> [Stunbreak] the chained players out of the initial <img class='inline float'> [Float]. To improve green solving, a common approach is to try splitting into the same groups that would be used to solve [Judgement of Eternity].

---

### Eternal Reflection

<div class='sidebar-background row-container margins'>

<div class='adapt-width'>
<video class='bordered center' width="100%" controls>
<source src='../videos/eternal-reflection.mp4' type='video/mp4'>
</video>
</div>

<div class='adapt-width' markdown=block>

|*Common Name*| Fan, Cone, "Who is reflecting?!" |
|*Used By*| Vloxx, [Champion Staff] |
|*Used in Phases*| [Phase 1] |
|*Cooldown*| est. 9 seconds |

</div>

</div>

Launches a barrage of projectiles in a wide cone towards the <img class='inline fixate-icon'> [Fixate], dealing moderate damage.

{: .warning}
These projectiles bounce and explode whenever they interact with projectile destruction or reflection effects such as <img class='inline feedback'> [Feedback] or <img class='inline cpc'> [Corrosive Poison Cloud], dealing heavy damage in proximity of the effect.

---

### Surrounding Curse

<div class='sidebar-background row-container margins'>

<div class='adapt-width'>
<video class='bordered center' width="100%" controls>
<source src='../videos/surrounding-curse.mp4' type='video/mp4'>
</video>
</div>

<div class='adapt-width' markdown=block>

|*Common Name*| Rain, Small AoES |
|*Used By*| Vloxx, [Champion Staff] |
|*Used in Phases*| [Phase 1], [Phase 4] |
|*Cooldown*| est. 30 seconds |

</div>

</div>

Summons a rain of small projectiles on the <img class='inline fixate-icon'> [Fixate] that explode, dealing light damage and inflicting <img class='inline torment'> [Torment] and <img class='inline weakness'> [Weakness].

{: .note}
While this attack can technically be reflected, it will often overlap with [Eternal Reflection], which makes it dangerous to do so.

#### Strategy
{: .no_toc}
This attack has a very obvious telegraph, meaning players have more than enough time to walk out of the AoEs. Projectile reflection can be used if necessary, but players should be careful in proximity of the [Champion Staff], as it could use [Eternal Reflection] at any point.

<img class=divider>

## Spear Attacks

These attacks can be used by Vloxx during the second phase or the final phase, or by the [Champion Spear].

|**Mechanic**|**Common Name**|**Brief Description**|
| [Cosmic Charge] | Charge | Charges in a line, leaving damaging pools on its trail. |
| [Raging Storm] | Spears | Launches a barrage of spears that <img class='inline knockback'> [Knockback] and leave lingering pools. |
| [Thousand Strikes] | Cone | Launches a barrage of spear thrusts in a cone. |
| [Worldpiercer] | Walls, Lines | Six walls divide the arena into six slices. |

---

### Cosmic Charge

<div class='sidebar-background row-container margins'>

<div class='adapt-width'>
<video class='bordered center' width="100%" controls>
<source src='../videos/cosmic-charge.mp4' type='video/mp4'>
</video>
</div>

<div class='adapt-width' markdown=block>

|*Common Name*| Charge, Dash |
|*Used By*| Vloxx, [Champion Spear] |
|*Used in Phases*| [Phase 2] |
|*Cooldown*| 45 seconds |

</div>

</div>

Targets the <img class='inline fixate-icon'> [Fixate] with a large orange arrow. After a brief pause, charges forward for 1500 units, dealing moderate damage, inflicting <img class='inline knockback'> [Knockback] and leaving behind a trail of lingering puddles. These corrupt boons and inflict <img class='inline cripple'> [Crippled] and <img class='inline burning'> [Burning].

#### Strategy
{: .no_toc}
This attack often occurs simultaneously with [Judgement of Eternity], making it extremely important to avoid <img class='inline knockback'> [Knockback] affecting player positioning. <img class='inline stability'> [Stability] is thus extremely important, as the dash hits multiple times. The trail itself also strips boons, so if players have to stand inside it, the only surefire way to mitigate this mechanic becomes mass <img class='inline invuln'> [Invulnerability] with <img class='inline august-queen'> [Tale of the August Queen].

---

### Raging Storm

<div class='sidebar-background row-container margins'>

<div class='adapt-width'>
<video class='bordered center' width="100%" controls>
<source src='../videos/raging storm.mp4' type='video/mp4'>
</video>
</div>

<div class='adapt-width' markdown=block>

|*Common Name*| Spears, Reflect |
|*Used By*| Vloxx |
|*Used in Phases*| [Phase 2], [Phase 4] |
|*Cooldown*| 36 seconds |

</div>

</div>

Targets the <img class='inline fixate-icon'> [Fixate] with a barrage of 16 spears at 1 second intervals. Each spear explodes in a small AoE on hitting the floor, dealing moderate damage, inflicting <img class='inline knockback'> [Knockback] and leaving behind a lingering puddle. This puddle deals moderate damage and strips boons.

Spears are projectiles and thus affected by projectile disruption.

{: .legendary}
Spears are no longer affected by projectile disruption during the final phase.

#### Strategy
{: .no_toc}
The most common way to mitigate this mechanic is by defining a rotation of projectile disruption skills to maintain coverage throughout the duration of the mechanic. This commonly involves four people in sequence, each one using skills such as <img class='inline feedback'> [Feedback] and <img class='inline cpc'> [Corrosive Poison Cloud].

---

### Thousand Strikes

<div class='sidebar-background row-container margins'>

<div class='adapt-width'>
<video class='bordered center' width="100%" controls>
<source src='../videos/thousand-strikes.mp4' type='video/mp4'>
</video>
</div>

<div class='adapt-width' markdown=block>

|*Common Name*| Cone, Thrusts |
|*Used By*| Vloxx, [Champion Spear] |
|*Used in Phases*| [Phase 2] |
|*Cooldown*| est. 8 seconds |

</div>

</div>

Vloxx attacks with a rapid series of strikes in a cone, dealing heavy damage and inflicting <img class='inline vuln'> [Vulnerability].

---

### Worldpiercer

<div class='sidebar-background row-container margins'>

<div class='adapt-width'>
<video class='bordered center' width="100%" controls>
<source src='../videos/worldpiercer.mp4' type='video/mp4'>
</video>
</div>

<div class='adapt-width' markdown=block>

|*Common Name*| Walls, Pizza |
|*Used By*| Vloxx |
|*Used in Phases*| [Phase 2] |
|*Cooldown*| 30 seconds |

</div>

</div>

Vloxx summons six red arrows in a star, which fire after a delay, <img class='inline invuln'> [Downstating] any player caught in one and killing any player caught in two.

The arrows then leave behind narrow walls that inflict <img class='inline knockback'> [Knockback] and 10 stacks of <img class='inline burning'> [Burning] on any players that attempt to walk through their area. It is possible to dodge through these, or walk through with <img class='inline stability'> [Stability] while cleansing the conditions.

Walls persist for 10 seconds, and are not removed on phase changes.

#### Strategy
{: .no_toc}
This attack has a very long telegraph, leaving players with a lot of time to position inside one of the "slices" before they're cut off. It's important for the entire squad to be inside the same slice to solve mechanics such as [Raging Storm] and [Judgement of Eternity].

<img class=divider>

## Sword Attacks

These attacks can be used by Vloxx during the third phase or the final phase, or by the [Champion Sword].

|**Mechanic**|**Common Name**|**Brief Description**|
| [Division Eternal] | Rectangle | Large rectangular damaging AoE. |
| [Echoing Blade] | Circle | Circular attack that launches rotating sword projectiles. |
| [Excision Extremis] | Blades, Storm | Large amount of overlapping semicircular AoE damage and boonstrip. |
| [Slice Through Reality] | Teleport, Suction | Teleport skill that leaves a rift that sucks in players. |

---

### Division Eternal

<div class='sidebar-background row-container margins'>

<div class='adapt-width'>
<video class='bordered center' width="100%" controls>
<source src='../videos/division-eternal.mp4' type='video/mp4'>
</video>
</div>

<div class='adapt-width' markdown=block>

|*Common Name*| Rectangle |
|*Used By*| Vloxx, [Champion Sword] |
|*Used in Phases*| [Phase 3] |
|*Cooldown*| 5 seconds |

</div>

</div>

Throws a massive sword at the <img class='inline fixate-icon'> [Fixate], resulting in a large rectangular AoE that inflicts high damage, strips boons and applies <img class='inline blind'> [Blinded] and <img class='inline confusion'> [Confusion].

This skill deals damage multiple times over its length: players that are too far from the boss can get hit multiple times, resulting in increased damage.

#### Strategy
{: .no_toc}
This attack has a very long and recognizable wind-up, giving players a large amount of time to move out of its AoE or dodge. This is especially relevant for the <img class='inline fixate-icon'> [Fixate] in [phase 3], who should also try to be close to the boss in order to avoid multi-hits.

If players are hit by this skill, it's important to quickly re-boon.

---

### Echoing Blade

<div class='sidebar-background row-container margins'>

<div class='adapt-width'>
<video class='bordered center' width="100%" controls>
<source src='../videos/echoing-blade.mp4' type='video/mp4'>
</video>
</div>

<div class='adapt-width' markdown=block>

|*Common Name*| Circle, Red Swords |
|*Used By*| Vloxx |
|*Used in Phases*| [Phase 3] |
|*Cooldown*| 20 seconds |

</div>

</div>

Circular attack composed of several semicircular AoE slices centered around the boss, combined with red rotating sword projectiles. While each slice deals moderate damage, the cumulative damage from multiple hits can quickly become threatening. The sword projectiles apply moderate damage and inflict <img class='inline torment'> [Torment] and <img class='inline weakness'> [Weakness], and can be deleted using standard projectile disruption.

{: .legendary}
The projectiles from this attack are larger and ignore projectile disruption.

#### Strategy
{: .no_toc}
Players should try to dodge at least some of the damage from this skill, especially if the boss has a lot of <img class='inline empowered'> [Empowered]. Players should use projectile disruption effects on the squad and on the <img class='inline fixate-icon'> [Fixate] to avoid the sword projectiles. When this attack overlaps with [Judgement of Eternity], one projectile disruption effect should be used per green group: try to sort this out beforehand.

---

### Excision Extremis

<div class='sidebar-background row-container margins'>

<div class='adapt-width'>
<video class='bordered center' width="100%" controls>
<source src='../videos/excision-extremis.mp4' type='video/mp4'>
</video>
</div>

<div class='adapt-width' markdown=block>

|*Common Name*| Geometry, Bladestorm |
|*Used By*| Vloxx, [Champion Sword] |
|*Used in Phases*| [Phase 3], [Phase 4] |
|*Cooldown*| 10 seconds |

</div>

</div>

Large area attack consisting of a storm of overlapping, small to medium semicircular AoE attacks. Each of these deals moderate damage, inflicts <img class='inline cripple'> [Crippled] and <img class='inline bleeding'> [Bleeding], and strips boons with an internal cooldown of 2 seconds.

#### Excision Extremis Patterns
{: .no_toc .center}

<div class="row-container">
<img class="adapt-width bordered" src="./excision/sample-1.webp">
<img class="adapt-width bordered" src="./excision/sample-2.webp">
</div>

While individual AoEs are not dangerous, the cumulative damage from multiple hits can quickly become threatening. This attack can occur with several different patterns; the boss will select which one to use based on the phase (3rd or 4th) and the distance of the <img class='inline fixate-icon'> [Fixate].

#### Strategy
{: .no_toc}
Patterns tend to leave "safe areas" behind the boss, especially when the <img class='inline fixate-icon'> [Fixate] is in melee range. For this reason, it's common to have them position on the opposite side of the boss from the main stack. This way, the supports can target heal them while avoiding most of the damage on the group.

Situations can occur when the <img class='inline fixate-icon'> [Fixate] changes, as the attack will then usually target the main stack. In this case, players should double dodge to avoid the majority of incoming damage, then heal up and re-boon. Otherwise, mass <img class='inline invuln'> [Invulnerability] skills such as <img class='inline august-queen'> [Tale of the August Queen] are commonly used.

---

### Slice Through Reality

<div class='sidebar-background row-container margins'>

<div class='adapt-width'>
<video class='bordered center' width="100%" controls>
<source src='../videos/slice-through-reality.mp4' type='video/mp4'>
</video>
</div>

<div class='adapt-width' markdown=block>

|*Common Name*| Teleport, Suck |
|*Used By*| Vloxx |
|*Used in Phases*| [Phase 3] |
|*Cooldown*| 60 seconds |

</div>

</div>

Vloxx slices through space, opening up a rift that transports him to a different location, 1500 units in the direction of the <img class='inline fixate-icon'> [Fixate]. Any players inside of Vloxx's hitbox will be transported with him. 

The entrance of the rift sucks in players, while the exit pushes them away. Players sucked into the rift after the initial teleportation will be transported to Vloxx's new location, have three boons corrupted and lose a stack of <img class='inline ascension'> [Ascension].

Any player that takes the rift, whether through the initial teleportation or later on, will get afflicted by <img class='inline knockdown'> [Knockdown].

#### Strategy
{: .no_toc}
Groups will either have everyone enter the rift (common with melee strategies) or no-one (requires a ranged strategy). When taking the rift, it's important to mitigate the <img class='inline knockdown'> [Knockdown] either by providing <img class='inline stability'> [Stability] before or with a <img class='inline stunbreak'> [Stunbreak] immediately after.

<img class='inline superspeed'> [Superspeed] is also extremely important to reduce the effect of the suction and pushback effects. This is doubly important for the <img class='inline fixate-icon'> [Fixate], as they will have to position correctly immediately after.

<img class=divider>

## Special Attacks

While technically single attacks, these mechanics are more like sequences of consecutive attacks that only appear in specific moments of the fight.

---

### Visions of Eternity

This attack is cast upon reaching *70%*, *%40%* and *10%* of Vloxx's maximum HP, triggering the beginning of his split phases. Vloxx will become <img class='inline invuln'> [Invulnerable] and start charging up a massive strike. While doing so, he will summon a [Champion Elemental] and three [Elite Elementals], with the composition of enemies depending on the specific split phase.

He will then start casting large AoEs targeting the group. These slowly fill, dealing moderate damage and applying <img class='inline float'> [Float] to players caught inside.

This attack can be interrupted by killing all the summoned elementals, which will unlock Vloxx's <img class='inline defiance'> [Defiance Bar]. Breaking this bar will stop the attack, grant Vloxx 10 <img class='inline empowered'> [Empowered], and begin the following phase.

If the attack is allowed to complete, 67 seconds after Vloxx becomes invulnerable, it will instantly defeat all players.

---

### Threshold of Eternity

This attack is used by Vloxx at the beginning of the 10% phase. He commences it by becoming <img class='inline invuln'> [Invulnerable] while changing to his smaller meditation form over the course of 15 seconds, upon which he becomes vulnerable once more.

While this transformation is ongoing, he will start casting a combination of attacks from all three phases.

#### Attacks Included
{: .no_toc .center}

|**General Attacks**| [Judgement of Eternity], [Probability Distribution] |
|**Staff Attacks**| [Surrounding Curse] |
|**Spear Attacks**| [Raging Storm] |
|**Sword Attacks**| [Excision Extremis] |

These mechanics rotate continuously until the boss is dead.

Beginning this attack will also start a timer, which overrides the enrage for the fight and shortens it to two minutes. If this timer runs out, Vloxx will instantly defeat all players.

<img class=divider>

## Enemies

The Nexus of Eternity encounter is characterized by a large amount of enemy adds that enter the picture at different points in the encounter. These can mostly be divided into two groups: *split phase adds* and *weapon adds*.

---

### Weapons

These are three Champion Weapons, one for each of Vloxx's armaments:

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
<img class='center margins' width="70%" src='./sword.webp'>
Spawns at the beginning of the second split phase (40%). Can use the skills: [Division Eternal], [Excision Extremis].
</div>

</div>

#### Champion Weapon
{: .no_toc .center}

| **Health** |  4,620,570  |
| **Defiance Bar** | 1000 |
| **Armor** | 2597 (standard) |
| **Hitbox** | 100 (small) |

Champion weapons spawn in before the main phase associated with their form. When killed, they will respawn 40 seconds later. They will always spawn and respawn at the same locations in the arena.

<img class=center width="60%" src='./weapon-spawns.webp'>

Weapon behaviour mainly consists in attempting to get in range of a player, then casting one of their available skills. Both the *Spear* and *Sword* are melee, and will attempt to get into melee range to attack. The *Staff* instead is ranged, and will stop at around 300 units from its target. Weapons will remain active as long as they are alive, continuously harassing the group through the entirety of the split phases and transitions up until the fight end.

Weapons will grant Vloxx a stack of <img class='inline empowered'> [Empowered] 24 seconds after spawning, and at 20 second intervals following.

{: .note}
This means that weapons should be killed at most 84 seconds after spawning to remain neutral on <img class='inline empowered'> [Empowered]. The <img class='inline achievement'> [True Visionary](https://wiki.guildwars2.com/wiki/The_Nexus_of_Eternity) achievement, which involves ending on less than 10 stacks, requires killing seven champions in less than 24 seconds, or 11 champions in less than 44 seconds, or 21 champions in less than 64 seconds.

Weapons gain a CC bar at 25% HP. When this bar is broken, they will spawn in three orbs that grant a stack of <img class='inline ascension'> [Ascension] when picked up by a player, removing a stack of <img class='inline empowered'> [Empowered] from Vloxx. These orbs can only be spawned once per add, and persist for 2 minutes before de-spawning.

---

### Elementals

There are three elemental types: the *Cosmic Piercer*, the *Cosmic Bulwark* and the *Cosmic Sunderer*.

<div class="alt-row-container">

<div class='center adapt-width-30' markdown=block>
#### Cosmic Piercer
{: .no_toc}
<img class='center margins' width="70%" src='./piercer.webp'>
Spawns during the 70% split phase. Summons projectile waves and teleports.
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

A champion and three Elite versions of these enemies are spawned at the beginning of each split phase as a part of the cast of [Visions of Eternity]. Killing these adds is necessary to unlock Vloxx's <img class='inline defiance'> [Defiance Bar] and progress the encounter.

<img class=divider>

[Return to Home](../index.html){: .btn} [Strategy Guide](../strategy/index.html){: .btn} [Return to Top](#vloxx){: .btn .fixed}


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

[Phase 1]: #staff-phase
[Phase 2]: #spear-phase
[Phase 3]: #sword-phase
[Phase 4]: #final-phase

<!-- Links to classes and specializations -->

<!-- Links to player skills -->
[Feedback]: https://wiki.guildwars2.com/wiki/Feedback
[Corrosive Poison Cloud]: https://wiki.guildwars2.com/wiki/Corrosive_Poison_Cloud
[We Will Never Yield!]: https://wiki.guildwars2.com/wiki/%22We_Will_Never_Yield!%22
[Tale of the August Queen]: https://wiki.guildwars2.com/wiki/Tale_of_the_August_Queen

<!-- Links to buffs and debuffs -->
[Downstating]: https://wiki.guildwars2.com/wiki/Downstate
[Invulnerable]: https://wiki.guildwars2.com/wiki/Invulnerability
[Invulnerability]: https://wiki.guildwars2.com/wiki/Invulnerability
[Vulnerability]: https://wiki.guildwars2.com/wiki/Vulnerability
[Might]: https://wiki.guildwars2.com/wiki/Might
[Resolution]: https://wiki.guildwars2.com/wiki/Resolution
[Protection]: https://wiki.guildwars2.com/wiki/Protection
[Stability]: ttps://wiki.guildwars2.com/wiki/Stability
[Float]: https://wiki.guildwars2.com/wiki/Float
[Floats]: https://wiki.guildwars2.com/wiki/Float
[Downstate]: https://wiki.guildwars2.com/wiki/Downstate
[Crippled]: https://wiki.guildwars2.com/wiki/Cripple
[Knockback]: https://wiki.guildwars2.com/wiki/Knockback
[Knockdown]: https://wiki.guildwars2.com/wiki/Knockdown
[Slow]: https://wiki.guildwars2.com/wiki/Slow
[Burning]: https://wiki.guildwars2.com/wiki/Burning
[Poison]: https://wiki.guildwars2.com/wiki/Poison
[Chilled]: https://wiki.guildwars2.com/wiki/Chilled
[Torment]: https://wiki.guildwars2.com/wiki/Torment
[Weakness]: https://wiki.guildwars2.com/wiki/Weakness
[Blinded]: https://wiki.guildwars2.com/wiki/Blinded
[Confusion]: https://wiki.guildwars2.com/wiki/Confusion
[Bleeding]: https://wiki.guildwars2.com/wiki/Bleeding
[Superspeed]: https://wiki.guildwars2.com/wiki/Superspeed
[Aegis]: https://wiki.guildwars2.com/wiki/Aegis

<!-- Links to enemies and enemy skills -->
[Champion Staff]: #weapons
[Champion Spear]: #weapons
[Champion Sword]: #weapons
[Champion Elemental]: #elementals
[Elite Elementals]: #elementals

<!-- Other -->
[Defiance Bar]: https://wiki.guildwars2.com/wiki/Defiance_bar
[Stunbreak]: https://wiki.guildwars2.com/wiki/Stun_break