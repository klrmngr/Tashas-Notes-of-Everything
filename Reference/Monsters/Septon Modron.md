---
type: pc
race: "Construct"
class:
 - "Septon Modron"
subClass:
 - "CR 12"
cover: "Septon Modron.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/large
  - cr/12
  - source/mpp
---
###### Septon Modron
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MPP
___

> [!infobox|no-t right]
> ![[Septon Modron.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 12 (8,400 XP) |
> | :RiSwordFill: Type | Large Construct |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Lawful Neutral |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 204 (24d10 + 72) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | MPP |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 15 | 17 | 18 | 16 | 14 |
| **Mod** | +4 | +2 | +3 | +4 | +3 | +2 |

**Speed:** 30 ft., fly 30 ft. ((hover)), swim 30 ft. &nbsp;|&nbsp; **Senses:** truesight 120 ft., passive Perception 21
**Languages:** all, telepathy 120 ft.
**Saving Throws:** Int +8, Wis +7
**Skills:** Perception +11
**Damage Resistances:** lightning; psychic

---

### Traits

**Axiomatic Mind.** The septon can't be compelled to act in a manner contrary to its nature or its instructions.

**Combat Ready.** The septon has advantage on initiative checks.

**Disintegration.** If the septon dies, its body disintegrates into dust, leaving behind anything it was carrying.


---

### Actions

**Multiattack.** The septon makes four Tentacle attacks and uses Lightning Network or Spellcasting.

**Tentacle.** Melee Weapon Attack: +8 to hit, reach 10 ft., one target. *Hit:* 15 (2d10 + 4) piercing damage, and if the target is a Medium or smaller creature, it has the grappled condition (escape DC 14). Until this grapple ends, the septon can't use this tentacle against other targets. The septon has seven tentacles, each of which can grapple one target.

**Lightning Network.** The septon conjures a field of electricity that fills a 30-foot cube originating from itself before dissipating. Each creature in that area must make a DC 16 Dexterity saving throw. On a failed save, a creature takes 33 (6d10) lightning damage and has the stunned condition for 1 minute. On a successful save, a creature takes half as much damage only. A stunned creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.


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