---
layout: page
title: Strategy
nav_order: 3
---

[Return to Home](../index.html){: .btn} [Mechanical Reference](../mechanics/index.html){: .btn}

# Strategy Guide
{: .no_toc}

<details>
<summary><b>Table of Contents</b></summary>
<div markdown=block>
1. TOC
{:toc}
</div>
</details>

The standard strategy for the Nexus of Eternity focuses on precise positioning and defensive utility to manage the consistent stream of enemies and counteract the various dangerous mechanics that characterize the encounter.

---

#### Main Points
{: .no_toc}
- A large amount of defensive utility is required to manage Vloxx's especially large variety of attacks. Projectile deflection in particular is a common failure point.
- Groups must constantly cleave [Champion Weapons] to counteract Vloxx's passive <img class='inline empowered'> [Empowered] gain.
- The boss will randomly select a <img class='inline fixate-icon'> [Fixate] to focus with mechanics. This requires groups to react and improvise on the fly based on the selection.

<img class=divider>

## General Information

Vloxx as an enemy has a large selection of attacks, which is then narrowed down to a smaller number based on the specific phase of the encounter:

```mermaid
flowchart LR
    %%{init: {'themeVariables': { 'edgeLabelBackground': 'transparent'}}}%%
    linkStyle default stroke:#7fdefd,stroke-width:3px,color:#7fdefd,font-size:13px,background-color:#000000
    classDef invis fill:#000000,stroke:#000000,color:#000000
    classDef green fill:#00540d,stroke-width:0,color:#fff
    classDef blue fill:#0072c9,stroke-width:0,color:#fff
    classDef default fill:#000000,stroke:#7fdefd,color:#7fdefd

    phase1("`100% - 70%
    Staff`")
    phase2("`70% - 40%
    Spear`")
    phase3("`40% - 10%
    Sword`")
    phase4("`10% - 0%
    Perfect Form`")

    phase1 --> phase2
    phase2 --> phase3
    phase3 --> phase4

    click phase1 "../mechanics/index.html#100---70---staff-phase"
    click phase2 "../mechanics/index.html#70---40---spear-phase"
    click phase3 "../mechanics/index.html#40---10---sword-phase"
    click phase4 "../mechanics/index.html#10---0---perfect-form"

```
{: .center}
As a result, all three phases play quite differently, as the squad will have to deal with different mechanics in each.

---

### <img class='inline empowered'> Empowered and Weapon Management

Vloxx, similarly to other bosses such as [Cerus](https://silverhalf.github.io/temple-of-febe/) and [Greer](https://silverhalf.github.io/mount-balrior/greer/overview.html), will *actively* gain <img class='inline empowered'> [Empowered] stacks whenever players fail mechanics. Unlike these other encounters, however, Vloxx also has several sources of *passive* gain. Left alone, these sources will gradually cause the encounter to fail, as the boss will start dealing prohibitive amounts of damage while taking very little.

The only way to counteract <img class='inline empowered'> [Empowered] is through <img class='inline ascension'> [Ascension], and the only way to gain <img class='inline ascension'> [Ascension] is through [Champion Weapons]: a maximum of three stacks can be gained from each by breaking their <img class='inline defiance'> [Defiance Bar] once they reach 25% maximum HP.

This results in significant strategic considerations: groups must position carefully to aggro any weapons onto the boss, and must bring large amounts of cleave to kill them quickly. When done correctly, this results in them surviving for less (and thus granting fewer <img class='inline empowered'> [Empowered]) and provides a steady source of <img class='inline ascension'> [Ascension] to offset any other gains.

---

### Solving Greens

[Judgement of Eternity], mostly known as [Greens], is one of the encounter's more challenging mechanics. This attack is present in all four phases, and requires careful attention and some improvisation to solve reliably.

Two common strategies exist for this mechanic:
- [Anchor Greens](../mechanics/index.html#strategy-anchors) assigns two players, called *anchors*, to bait the mechanic.
- [Subgroup Greens](../mechanics/index.html#strategy-subgroups) has four people (an entire subgroup minus the healer) bait the greens.

Both strategies are viable and commonly used.

<div class="alt-row-container">
<div class="strategy bordered" markdown=block>
#### [Anchor Baiting](../mechanics/index.html#strategy-anchors)
{: .no_toc .center}

<img class=warn> Almost exclusive to the EU region. <br>
<img class=pro> Greens know where to go in advance.<br>
<img class=con> Chaotic if not baited correctly. 
</div>
<div class="strategy bordered" markdown=block>
#### [Subgroup Baiting](../mechanics/index.html#strategy-subgroups)
{: .no_toc .center}

<img class=warn> Almost exclusive to the NA region. <br>
<img class=con> Requires a green to move after baiting. <br>
<img class=pro> More reliable baiting of greens.

</div>
</div>

Groups should decide on the strategy beforehand, and assign players to their specific roles.
- For [Anchor Greens](../mechanics/index.html#strategy-anchors), choose the three *anchors* and the *float*. Assign two additional players to each anchor, so that three are in each group.
- For [Subgroup Greens](../mechanics/index.html#strategy-subgroups), choose which subgroup is *melee* and which is *ranged*. Choose one non-heal player from the *ranged* subgroup to be the *float*.

---

### Projectile Management

Vloxx has a love-hate relationship with projectile management.

In the first phase, reflection or nullification skills can be extremely dangerous due to [Eternal Reflection]. This skill will generate large amounts of AoE damage when hitting these effects, easily leading to <img class='inline invuln'> [Downstates]. Groups will generally avoid using any projectile nullification except when they are absolutely certain that it will not overlap with this mechanic.

In phase 2, [Raging Storm] requires at least 20 seconds of continuous coverage to prevent both the <img class='inline knockback'> [Knockback] and the formation of dangerous pools under the group. This is usually done either by running a *solo bubble*, such as a heal <img class='inline vindicator'> [Vindicator], or by setting up a *rotation* with at least four sources of projectile negation, usually either <img class='inline feedback'> [Feedback] or <img class='inline cpc'> [Corrosive Poison Cloud].

In the final phase, [Raging Storm] lasts for the entire phase. This requires permanent projectile reflection (outside of legendary mode), which can again be done with a solo bubble. Alternatively, have three <img class='inline necromancer'> [Necromancers] rotate casts of <img class='inline cpc'> [Corrosive Poison Cloud]. With the proper timing, this skill can be re-cast off cooldown to provide permanent coverage for the main stack, freeing up <img class='inline feedback'> [Feedback] for the side groups during greens.

<img class=divider>

## Composition

Groups attempting to clear the Nexus of Eternity will benefit from a large amount of defensive utility. Groups will benefit from having:

- *Projectile Negation*: permanent coverage for CM, or at least 20 seconds of continuous duration for LCM.
- <img class='inline stability'> [Stability]: multiple stacks on a medium cooldown.
- Group <img class='inline stunbreak'> [Stunbreak]: on a medium-long cooldown.
- <img class='inline superspeed'> [Superspeed]: very useful since the encounter has a lot of movement.
- *Cleave*: to manage [Champion Weapons] and split phases efficiently.
- *Crowd Control*: necessary for [Champion Weapons], [Champion Elementals] and for Vloxx's large <img class='inline defiance'> [Defiance Bar] after every split phase.
- High *Survivability* and *Healing*: the boss will start dealing obscene damage towards the end of the fight due to <img class='inline empowered'> [Empowered].
- *Condition Cleanse*: most of Vloxx's attacks apply some form of damaging or debilitating condition.

By looking at this daunting list of requirements, one can understand why <img class='inline troubadour'> [Troubadour] is the ubiquitous healer on this encounter. Its strong healing output, large boon radius and incredible defensive utility with skills such as <img class='inline rogue'> [Tale of the Honorable Rogue], <img class='inline marshal'> [Tale of the Valiant Marshal] and <img class='inline august-queen'> [Tale of the August Queen] make it stand head and shoulders above any other defensive supports for the Nexus of Eternity. It can also run with a [Celestial] build to improve damage output at the cost of some healing.

As a result of <img class='inline troubadour'> [Troubadour]'s dominance, boon supports will almost always bring <img class='inline alacrity'> [Alacrity]. Common picks include <img class='inline evoker'> [Evoker], <img class='inline luminary'> [Luminary] and <img class='inline amalgam'> [Amalgam]. <img class='inline specter'> [Specter] is also a viable pick as it provides large amounts of CC when running spear, but is not as common due to its significant damage handicap compared to its alternatives.

Common strategies cover projectile negation by running at least three <img class='inline scourge'> [Scourges] with <img class='inline cpc'> [Corrosive Poison Cloud] (two in Legendary Mode). These can also bring additional strong utility for the encounter, such as <img class='inline epidemic'> [Epidemic] and large amounts of condition cleanse. Alternatively, some groups will run a heal <img class='inline vindicator'> [Vindicator] to cover projectile negation on its own, pairing it with a [Celestial] <img class='inline troubadour'> [Troubadour].

The encounter generally favours *condition damage*, since phases are long and conditions will keep ticking on the boss for some time after the beginning of each split phase. Condition builds also have the advantage of of being able to run [Trailblazer] prefix gear, granting them massively improved survivability for a moderate DPS loss.

<img class=divider>

## First Phase

<img class=divider>

## Second Phase

<img class=divider>

## Third Phase

<img class=divider>

## Final Phase

<img class=divider>

[Return to Home](../index.html){: .btn} [Mechanical Reference](../mechanics/index.html){: .btn} [Return to Top](#strategy-guide){: .btn .fixed}

<!-- Links to other pages in the guide -->
[Judgement of Eternity]: ../mechanics/index.html#judgement-of-eternity
[Greens]: ../mechanics/index.html#judgement-of-eternity
[Probability Distribution]: ../mechanics/index.html#probability-distribution
[Visions of Eternity]: ../mechanics/index.html#visions-of-eternity
[Threshold of Eternity]: ../mechanics/index.html#threshold-of-eternity
[Annihilating Orb]: ../mechanics/index.html#annihilating-orb
[Ascension's Sacrifice]: ../mechanics/index.html#ascensions-sacrifice
[Eternal Reflection]: ../mechanics/index.html#eternal-reflection
[Surrounding Curse]: ../mechanics/index.html#surrounding-curse
[Cosmic Charge]: ../mechanics/index.html#cosmic-charge
[Raging Storm]: ../mechanics/index.html#raging-storm
[Thousand Strikes]: ../mechanics/index.html#thousand-strikes
[Worldpiercer]: ../mechanics/index.html#worldpiercer
[Division Eternal]: ../mechanics/index.html#division-eternal
[Echoing Blade]: ../mechanics/index.html#echoing-blade
[Excision Extremis]: ../mechanics/index.html#excision-extremis
[Slice Through Reality]: ../mechanics/index.html#slice-through-reality

[Ascension]: ../mechanics/index.html#-ascension
[Empowered]: ../mechanics/index.html#-empowered
[Fixate]: ../mechanics/index.html#-fixate
[Fixated]: ../mechanics/index.html#-fixate

[Phase 1]: #first-phase
[Phase 2]: #second-phase
[Phase 3]: #third-phase
[Phase 4]: #final-phase

<!-- Links to classes and specializations -->
[Vindicator]: https://wiki.guildwars2.com/wiki/Vindicator
[Necromancers]: https://wiki.guildwars2.com/wiki/Necromancer
[Troubadour]: https://wiki.guildwars2.com/wiki/Troubadour
[Evoker]: https://wiki.guildwars2.com/wiki/Evoker
[Luminary]: https://wiki.guildwars2.com/wiki/Luminary
[Amalgam]: https://wiki.guildwars2.com/wiki/Amalgam
[Specter]: https://wiki.guildwars2.com/wiki/Specter
[Scourge]: https://wiki.guildwars2.com/wiki/Scourge
[Scourges]: https://wiki.guildwars2.com/wiki/Scourge

<!-- Links to player skills -->
[Feedback]: https://wiki.guildwars2.com/wiki/Feedback
[Corrosive Poison Cloud]: https://wiki.guildwars2.com/wiki/Corrosive_Poison_Cloud
[We Will Never Yield!]: https://wiki.guildwars2.com/wiki/%22We_Will_Never_Yield!%22
[Tale of the Honorable Rogue]: https://wiki.guildwars2.com/wiki/Tale_of_the_Honorable_Rogue
[Tale of the Valiant Marshal]: https://wiki.guildwars2.com/wiki/Tale_of_the_Valiant_Marshal
[Tale of the August Queen]: https://wiki.guildwars2.com/wiki/Tale_of_the_August_Queen
[Epidemic]: https://wiki.guildwars2.com/wiki/Epidemic

<!-- Links to buffs and debuffs -->
[Downstating]: https://wiki.guildwars2.com/wiki/Downstate
[Downstates]: https://wiki.guildwars2.com/wiki/Downstate
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
[Alacrity]: https://wiki.guildwars2.com/wiki/Alacrity

<!-- Links to enemies and enemy skills -->
[Champion Staff]: ../mechanics/index.html#weapons
[Champion Spear]: ../mechanics/index.html#weapons
[Champion Sword]: ../mechanics/index.html#weapons
[Champion Weapons]: ../mechanics/index.html#weapons
[Champion Elemental]: ../mechanics/index.html#elementals
[Champion Elementals]: ../mechanics/index.html#elementals
[Elite Elementals]: ../mechanics/index.html#elementals

<!-- Other -->
[Defiance Bar]: https://wiki.guildwars2.com/wiki/Defiance_bar
[Stunbreak]: https://wiki.guildwars2.com/wiki/Stun_break
[Trailblazer]: https://wiki.guildwars2.com/wiki/Trailblazer's
[Celestial]: https://wiki.guildwars2.com/wiki/Celestial