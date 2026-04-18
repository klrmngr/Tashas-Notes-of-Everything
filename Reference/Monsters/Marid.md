---
type: pc
race: "Elemental"
class:
 - "Marid"
subClass:
 - "CR 11"
cover: "Marid.png"
campaign:
locations:
tags:
  - race/elemental
  - affinity/hostile
  - type/elemental
  - size/large
  - cr/11
  - source/mm
---
###### Marid
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Marid.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 11 (7,200 XP) |
> | :RiSwordFill: Type | Large Elemental |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Neutral |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 229 (17d10 + 136) |
> | :FasUserGroup: Race | Elemental |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 22 | 12 | 26 | 18 | 17 | 18 |
| **Mod** | +6 | +1 | +8 | +4 | +3 | +4 |

**Speed:** 30 ft., fly 60 ft., swim 90 ft. &nbsp;|&nbsp; **Senses:** blindsight 30 ft., darkvision 120 ft., passive Perception 13
**Languages:** Aquan
**Saving Throws:** Dex +5, Wis +7, Cha +8
**Damage Resistances:** acid; cold; lightning

---

### Traits

**Amphibious.** The marid can breathe air and water.

**Elemental Demise.** If the marid dies, its body disintegrates into a burst of water and foam, leaving behind only equipment the marid was wearing or carrying.


---

### Actions

**Multiattack.** The marid makes two trident attacks.

**Trident.** Melee or Ranged Weapon Attack: +10 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* 13 (2d6 + 6) piercing damage, or 15 (2d8 + 6) piercing damage if used with two hands to make a melee attack.

**Water Jet.** The marid magically shoots water in a 60-foot line that is 5 feet wide. Each creature in that line must make a DC 16 Dexterity saving throw. On a failure, a target takes 21 (6d6) bludgeoning damage and, if it is Huge or smaller, is pushed up to 20 feet away from the marid and knocked prone. On a success, a target takes half the bludgeoning damage, but is neither pushed nor knocked prone.


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