---
type: pc
race: "Dragon (gem)"
class:
 - "Emerald Dragon Wyrmling"
subClass:
 - "CR 2"
cover: "Emerald Dragon Wyrmling.png"
campaign:
locations:
tags:
  - race/gem
  - affinity/hostile
  - type/dragon
  - size/medium
  - cr/2
  - source/ftd
---
###### Emerald Dragon Wyrmling
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Fizban's Treasury of Dragons
___

> [!infobox|no-t right]
> ![[Emerald Dragon Wyrmling.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Dragon (gem) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Neutral |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 39 (6d8 + 12) |
> | :FasUserGroup: Race | Dragon (gem) |
> | :FasBook: Source | Fizban's Treasury of Dragons |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 15 | 12 | 15 | 14 | 12 | 14 |
| **Mod** | +2 | +1 | +2 | +2 | +1 | +2 |

**Speed:** 30 ft., burrow 20 ft., fly 60 ft. &nbsp;|&nbsp; **Senses:** blindsight 10 ft., darkvision 60 ft., passive Perception 15
**Languages:** Draconic, telepathy 120 ft.
**Saving Throws:** Dex +3, Con +4, Wis +3, Cha +4
**Skills:** Arcana +4, Deception +4, Perception +5, Stealth +3
**Damage Resistances:** fire; psychic

---

### Traits

**Tunneler.** The dragon can burrow through solid rock at half its burrowing speed and can leave a 10-foot-diameter tunnel in its wake.


---

### Actions

**Bite.** Melee Weapon Attack: +4 to hit, reach 10 ft., one target. *Hit:* 7 (1d10 + 2) piercing damage plus 3 (1d6) psychic damage.

**Disorienting Breath (Recharge 5–6).** The dragon exhales a wave of psychic dissonance in a 15-foot cone. Each creature in that area must make a DC 12 Intelligence saving throw. On a failed save, the creature takes 17 (5d6) psychic damage, and until the end of its next turn, when the creature makes an attack roll or an ability check, it must roll a d4 and reduce the total by the number rolled. On a successful save, the creature takes half as much damage with no additional effects.


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