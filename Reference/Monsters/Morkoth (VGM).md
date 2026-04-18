---
type: pc
race: "Aberration"
class:
 - "Morkoth"
subClass:
 - "CR 11"
cover: "Morkoth.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/medium
  - cr/11
  - source/vgm
---
###### Morkoth
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Volo's Guide to Monsters
___

> [!infobox|no-t right]
> ![[Morkoth.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 11 (7,200 XP) |
> | :RiSwordFill: Type | Medium Aberration |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 130 (20d8 + 40) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | Volo's Guide to Monsters |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 14 | 14 | 20 | 15 | 13 |
| **Mod** | +2 | +2 | +2 | +5 | +2 | +1 |

**Speed:** 25 ft., swim 50 ft. &nbsp;|&nbsp; **Senses:** blindsight 30 ft., darkvision 120 ft., passive Perception 20
**Languages:** telepathy 120 ft.
**Saving Throws:** Dex +6, Int +9, Wis +6
**Skills:** Arcana +9, History +9, Perception +10, Stealth +6
**Damage Resistances:** bludgeoning, piercing, slashing from nonmagical attacks

---

### Traits

**Amphibious.** The morkoth can breathe air and water.


---

### Actions

**Multiattack.** The morkoth makes three attacks: two with its bite and one with its tentacles or three with its bite.

**Bite.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 9 (2d6 + 2) slashing damage.

**Tentacles.** Melee Weapon Attack: +6 to hit, reach 15 ft., one target. *Hit:* 15 (3d8 + 2) bludgeoning damage, and the target is grappled (escape DC 14) if it is a Large or smaller creature. Until this grapple ends. the target is restrained and takes 15 (3d8 + 2) bludgeoning damage at the start of each of the morkoth's turns. and the morkoth can't use its tentacles on another target.

**Hypnosis.** The morkoth projects a 30-foot cone of magical energy. Each creature in that area must make a DC 17 Wisdom saving throw. On a failed save, the creature is charmed by the morkoth for 1 minute. While charmed in this way, the target tries to get as close to the morkoth as possible, using its actions to Dash until it is within 5 feet of the morkoth. A charmed target can repeat the saving throw at the end of each of its turns and whenever it takes damage, ending the effect on itself on a success. If a creature's saving throw is successful or the effect ends for it, the creature has advantage on saving throws against the morkoth's Hypnosis for 24 hours.


---

### Reactions

**Spell Reflection.** If the morkoth makes a successful saving throw against a spell, or a spell attack misses it, the morkoth can choose another creature (including the spellcaster) it can see within 120 feet of it. The spell targets the chosen creature instead of the morkoth. If the spell forced a saving throw, the chosen creature makes its own save. If the spell was an attack, the attack roll is rerolled against the chosen creature.


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