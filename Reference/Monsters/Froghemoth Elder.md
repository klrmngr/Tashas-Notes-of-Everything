---
type: pc
race: "Monstrosity"
class:
 - "Froghemoth Elder"
subClass:
 - "CR 15"
cover: "Froghemoth Elder.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/huge
  - cr/15
  - source/qftis
---
###### Froghemoth Elder
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: QftIS
___

> [!infobox|no-t right]
> ![[Froghemoth Elder.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 15 (13,000 XP) |
> | :RiSwordFill: Type | Huge Monstrosity |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 14 (natural armor) |
> | :FasHeart: HP | 207 (18d12 + 90) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | QftIS |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 25 | 13 | 20 | 2 | 14 | 8 |
| **Mod** | +7 | +1 | +5 | -4 | +2 | -1 |

**Speed:** 30 ft., swim 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 22
**Languages:** —
**Saving Throws:** Str +12, Con +10, Wis +7
**Skills:** Perception +12, Stealth +6
**Damage Resistances:** fire; lightning

---

### Traits

**Amphibious.** The froghemoth can breathe air and water.

**Legendary Resistance (3/Day).** If the froghemoth fails a saving throw, it can choose to succeed instead.

**Shock Susceptibility.** If the froghemoth takes lightning damage, it suffers two effects until the end of its next turn: its speed is halved, and it has disadvantage on Dexterity saving throws.


---

### Actions

**Multiattack.** The froghemoth makes one Bite attack and two Tentacle attacks, and it can use Tongue.

**Bite.** Melee Weapon Attack: +12 to hit, reach 5 ft., one target. *Hit:* 23 (3d10 + 7) piercing damage, and the target is swallowed if it is a Medium or smaller creature. A swallowed creature has the blinded and restrained conditions, has 3 against attacks and other effects outside the froghemoth, and takes 10 (3d6) acid damage at the start of each of the froghemoth's turns.
The froghemoth's gullet can hold up to three creatures at a time. If the froghemoth takes 25 damage or more on a single turn from a creature inside it, the froghemoth must succeed on a DC 20 Constitution saving throw at the end of that turn or regurgitate all swallowed creatures, each of which lands in a space within 10 feet of the froghemoth and has the prone condition. If the froghemoth dies, any swallowed creatures are no longer restrained by it and can escape from the corpse using 10 feet of movement, exiting with the prone condition.

**Tentacle.** Melee Weapon Attack: +12 to hit, reach 20 ft., one target. *Hit:* 20 (3d8 + 7) bludgeoning damage, and the target has the grappled condition (escape DC 20). Until this grapple ends, the froghemoth can't use this tentacle on another target. The froghemoth has four tentacles.

**Tongue.** The froghemoth targets one Large or smaller creature that it can see within 25 feet of it. The target must make a DC 20 Strength saving throw. On a failed save, the target is pulled into an unoccupied space within 5 feet of the froghemoth.


---

### Reactions

**Alien Gaze.** When a creature the froghemoth can see damages the froghemoth, the froghemoth swivels its eyestalk toward the creature and pierces the creature's mind with its otherworldly gaze. That creature must make a DC 18 Intelligence saving throw, taking 7 (2d6) psychic damage on a failed save or half as much damage on a successful one.

**Leap.** Immediately after a creature the froghemoth can see ends its turn, the froghemoth jumps up to half its speed. Each creature within 5 feet of the froghemoth when it lands must succeed on a DC 20 Strength saving throw or have the prone condition.


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