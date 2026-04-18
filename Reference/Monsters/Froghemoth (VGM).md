---
type: pc
race: "Monstrosity"
class:
 - "Froghemoth"
subClass:
 - "CR 10"
cover: "Froghemoth.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/huge
  - cr/10
  - source/vgm
---
###### Froghemoth
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Volo's Guide to Monsters
___

> [!infobox|no-t right]
> ![[Froghemoth.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 10 (5,900 XP) |
> | :RiSwordFill: Type | Huge Monstrosity |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 14 (natural armor) |
> | :FasHeart: HP | 184 (16d12 + 80) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | Volo's Guide to Monsters |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 23 | 13 | 20 | 2 | 12 | 5 |
| **Mod** | +6 | +1 | +5 | -4 | +1 | -3 |

**Speed:** 30 ft., swim 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 19
**Languages:** —
**Saving Throws:** Con +9, Wis +5
**Skills:** Perception +9, Stealth +5
**Damage Resistances:** fire; lightning

---

### Traits

**Amphibious.** The froghemoth can breathe air and water.

**Shock Susceptibility.** If the froghemoth takes lightning damage, it suffers several effects until the end of its next turn: its speed is halved, it takes a −2 penalty to AC and Dexterity saving throws, it can't use reactions or Multiattack, and on its turn, it can use either an action or a bonus action, not both.


---

### Actions

**Multiattack.** The froghemoth makes two attacks with its tentacles. It can also use its tongue or bite.

**Tentacle.** Melee Weapon Attack: +10 to hit, reach 20 ft., one target. *Hit:* 19 (3d8 + 6) bludgeoning damage, and the target is grappled (escape DC 16) if it is a Huge or smaller creature. Until the grapple ends, the froghemoth can't use this tentacle on another target. The froghemoth has four tentacles.

**Bite.** Melee Weapon Attack: +10 to hit, reach 5 ft., one target. *Hit:* 22 (3d10 + 6) piercing damage, and the target is swallowed if it is a Medium or smaller creature. A swallowed creature is blinded and restrained, has 3 against attacks and other effects outside the froghemoth, and takes 10 (3d6) acid damage at the start of each of the froghemoth's turns.
The froghemoth's gullet can hold up to two creatures at a time. If the Froghemoth takes 20 damage or more on a single turn from a creature inside it, the Froghemoth must succeed on a DC 20 Constitution saving throw at the end of that turn or regurgitate all swallowed creatures, each of which falls prone in a space within 10 feet of the froghemoth. If the froghemoth dies, a swallowed creature is no longer restrained by it and can escape from the corpse using 10 feet of movement, exiting prone.

**Tongue.** The Froghemoth targets one Medium or smaller creature that it can see within 20 feet of it. The target must make a DC 18 Strength saving throw. On a failed save, the target is pulled into an unoccupied space within 5 feet of the froghemoth, and the froghemoth can make a bite attack against it as a bonus action.


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