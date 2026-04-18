---
type: pc
race: "Aberration"
class:
 - "Core Spawn Emissary"
subClass:
 - "CR 6"
cover: "Core Spawn Emissary.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/medium
  - cr/6
  - source/egw
---
###### Core Spawn Emissary
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Explorer's Guide to Wildemount
___

> [!infobox|no-t right]
> ![[Core Spawn Emissary.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 6 (2,300 XP) |
> | :RiSwordFill: Type | Medium Aberration |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 102 (12d8 + 48) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | Explorer's Guide to Wildemount |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 17 | 15 | 18 | 8 | 13 | 8 |
| **Mod** | +3 | +2 | +4 | -1 | +1 | -1 |

**Speed:** 40 ft., fly 60 ft. ((hover)) &nbsp;|&nbsp; **Senses:** blindsight 30 ft., tremorsense 60 ft., passive Perception 14
**Languages:** telepathy 120 ft., understands Deep Speech but can't speak
**Saving Throws:** Dex +5, Wis +4, Cha +2
**Skills:** Perception +4
**Damage Immunities:** psychic
**Condition Immunities:** blinded

---

### Traits

**Magic Resistance.** The emissary has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The emissary makes three talons attacks.

**Talons.** Melee Weapon Attack: +6 to hit, reach 5 ft., one creature. *Hit:* 14 (2d10 + 3) slashing damage.

**Alluring Thrum (Recharge 5–6).** The emissary emits a dreadful yet alluring hum. Each creature within 20 feet of the emissary that can hear it and that isn't an aberration must succeed on a DC 14 Constitution saving throw or be charmed for 1 minute. A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

**Crystal Spores (Recharge 6).** A 15-foot-radius cloud of toxic crystalline spores extends out from the emissary. The spores spread around corners. Each creature in the area must succeed on a DC 14 Constitution saving throw or become poisoned. While poisoned in this way, a creature takes 11 (2d10) poison damage at the start of each of its turns. A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.


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