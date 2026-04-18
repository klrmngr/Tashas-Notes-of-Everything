---
type: pc
race: "Aberration"
class:
 - "Storm Herald"
subClass:
 - "CR 17"
cover: "Storm Herald.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/huge
  - cr/17
  - source/bgg
---
###### Storm Herald
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: BGG
___

> [!infobox|no-t right]
> ![[Storm Herald.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 17 (18,000 XP) |
> | :RiSwordFill: Type | Huge Aberration |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 287 (23d12 + 138) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | BGG |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 27 | 14 | 22 | 24 | 18 | 18 |
| **Mod** | +8 | +2 | +6 | +7 | +4 | +4 |

**Speed:** 50 ft., swim 100 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 20
**Languages:** Common, Giant, telepathy 120 ft.
**Saving Throws:** Wis +10, Cha +10
**Skills:** Arcana +13, Deception +10, Perception +10
**Damage Resistances:** cold; psychic
**Damage Immunities:** lightning; thunder
**Condition Immunities:** charmed; frightened

---

### Traits

**Amphibious.** The herald can breathe air and water.

**Magic Resistance.** The herald has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The herald makes one Claw attack, one Tentacles attack, and one Trident attack.

**Claw.** Melee Weapon Attack: +14 to hit, reach 10 ft., one target. *Hit:* 18 (3d6 + 8) slashing damage.

**Tentacles.** Melee Weapon Attack: +14 to hit, reach 10 ft., one target. *Hit:* 21 (3d8 + 8) bludgeoning damage. If the target is a Large or smaller creature, it has the grappled condition (escape DC 18). It also has the restrained condition and takes 16 (3d10) psychic damage at the start of each of its turns until this grapple ends. The herald can have only one creature grappled this way at a time.

**Trident.** Melee Weapon Attack: +14 to hit, reach 10 ft., one target. *Hit:* 18 (3d6 + 8) piercing damage or 21 (3d8 + 8) piercing damage if used with two hands, plus 13 (3d8) lightning damage.

**Psychic Wave (Recharge 6).** The herald unleashes a blast of psionic energy into the minds of up to three creatures it can see within 90 feet of itself. Each target must make a DC 21 Intelligence saving throw. On a failed save, a target takes 23 (3d10 + 7) psychic damage and has the stunned condition for 1 minute. On a successful save, a target takes half as much damage only. An affected creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.
If a creature is reduced to 0 hit points by this psychic damage, it dies and its head explodes if it has one.


---

> [!column|flex 3]
>> [!important]- QUESTS:
>> ```base
>> properties:
>>   file.name:
>>     displayName: Name
>> views:
>>   - type: table
>>     name: Name
>>     filters:
>>       and:
>>         - file.inFolder("Compendium/Party/Quests")
>>         - file.hasLink(this.file)
>>     order:
>>       - file.name
>> ```
>
>> [!note]- HISTORY
>> ```base
>> properties:
>>   file.name:
>>     displayName: Name
>> views:
>>   - type: table
>>     name: Session Notes
>>     filters:
>>       and:
>>         - file.inFolder("Session Notes")
>>         - file.hasLink(this.file)
>> ```