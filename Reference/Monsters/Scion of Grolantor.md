---
type: pc
race: "Giant (titan)"
class:
 - "Scion of Grolantor"
subClass:
 - "CR 22"
cover: "Scion of Grolantor.png"
campaign:
locations:
tags:
  - race/titan
  - affinity/hostile
  - type/giant
  - size/gargantuan
  - cr/22
  - source/bgg
---
###### Scion of Grolantor
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: BGG
___

> [!infobox|no-t right]
> ![[Scion of Grolantor.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 22 (41,000 XP) |
> | :RiSwordFill: Type | Gargantuan Giant (titan) |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 18 (natural armor) |
> | :FasHeart: HP | 402 (23d20 + 161) |
> | :FasUserGroup: Race | Giant (titan) |
> | :FasBook: Source | BGG |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 27 | 14 | 25 | 15 | 21 | 18 |
| **Mod** | +8 | +2 | +7 | +2 | +5 | +4 |

**Speed:** 60 ft. &nbsp;|&nbsp; **Senses:** passive Perception 22
**Languages:** Giant, Primordial
**Saving Throws:** Wis +12, Cha +11
**Skills:** Perception +12
**Damage Resistances:** cold; fire; lightning; bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** poison
**Condition Immunities:** exhaustion; paralyzed; poisoned

---

### Traits

**Legendary Resistance (6/Day).** If the scion fails a saving throw, it can choose to succeed instead.

**Magic Resistance.** The scion has advantage on saving throws against spells and other magical effects.

**Siege Monster.** The scion deals double damage to objects and structures.


---

### Actions

**Multiattack.** The scion makes one Great Tree Club attack and two Slam attacks, or it makes three Boulder attacks.

**Great Tree Club.** Melee Weapon Attack: +15 to hit, reach 30 ft., one target. *Hit:* 30 (4d10 + 8) bludgeoning damage. If the target is a creature, it must succeed on a DC 23 Strength saving throw or be pushed horizontally up to 100 feet straight away from the scion and have the prone condition.

**Slam.** Melee Weapon Attack: +15 to hit, reach 20 ft., one target. *Hit:* 26 (4d8 + 8) force damage.

**Boulder.** Ranged Weapon Attack: +15 to hit, range 120/480 ft., one target. *Hit:* 27 (3d12 + 8) bludgeoning damage.

**Inhale (Recharge 5–6).** The scion inhales a vortex of air in a 120-foot line that is 15 feet wide. Each creature in that area that is Huge or smaller must succeed on a DC 23 Strength saving throw or be pulled up to 120 feet straight toward the scion and be swallowed. A swallowed creature has the restrained condition, has 3 against attacks and other effects outside the scion, and takes 24 (7d6) force damage at the start of each of the scion's turns.
The scion's stomach can hold up to two creatures at a time. If the scion takes 60 damage or more on a single turn from a creature inside it, the scion must succeed on a DC 17 Constitution saving throw at the end of that turn or regurgitate all swallowed creatures, each of which falls in a space within 10 feet of the scion and has the prone condition. If the scion dies, any swallowed creature no longer has the restrained condition and can escape from the corpse using 15 feet of movement, exiting with the prone condition.


---

### Bonus Actions

**Earth-Shaking Movement.** The scion moves up to its speed and then sends a shock wave through the ground in a 60-foot-radius circle centered on itself. Each creature on the ground in that area that is concentrating must succeed on a DC 23 Constitution saving throw or lose concentration.


---

### Reactions

**Feed.** Immediately after taking damage, if it has at least one creature swallowed, the scion deals 10 (3d6) force damage to each swallowed creature and regains 10 hit points.


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