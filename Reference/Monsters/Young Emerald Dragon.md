---
type: pc
race: "Dragon (gem)"
class:
 - "Young Emerald Dragon"
subClass:
 - "CR 8"
cover: "Young Emerald Dragon.png"
campaign:
locations:
tags:
  - race/gem
  - affinity/hostile
  - type/dragon
  - size/large
  - cr/8
  - source/ftd
---
###### Young Emerald Dragon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Fizban's Treasury of Dragons
___

> [!infobox|no-t right]
> ![[Young Emerald Dragon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Large Dragon (gem) |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Lawful Neutral |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 142 (15d10 + 60) |
> | :FasUserGroup: Race | Dragon (gem) |
> | :FasBook: Source | Fizban's Treasury of Dragons |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 21 | 12 | 19 | 16 | 14 | 16 |
| **Mod** | +5 | +1 | +4 | +3 | +2 | +3 |

**Speed:** 40 ft., burrow 30 ft., fly 60 ft. &nbsp;|&nbsp; **Senses:** blindsight 30 ft., darkvision 120 ft., passive Perception 18
**Languages:** Common, Draconic, telepathy 120 ft.
**Saving Throws:** Dex +4, Con +7, Wis +5, Cha +6
**Skills:** Arcana +6, Deception +6, Perception +8, Stealth +4
**Damage Resistances:** fire; psychic

---

### Traits

**Tunneler.** The dragon can burrow through solid rock at half its burrowing speed and can leave a 10-foot-diameter tunnel in its wake.


---

### Actions

**Multiattack.** The dragon makes one Bite attack and two Claw attacks.

**Bite.** Melee Weapon Attack: +8 to hit, reach 10 ft., one target. *Hit:* 16 (2d10 + 5) piercing damage plus 3 (1d6) psychic damage.

**Claw.** Melee Weapon Attack: +8 to hit, reach 5 ft., one target. *Hit:* 8 (1d6 + 5) slashing damage.

**Disorienting Breath (Recharge 5–6).** The dragon exhales a wave of psychic dissonance in a 30-foot cone. Each creature in that area must make a DC 15 Intelligence saving throw. On a failed save, the creature takes 31 (9d6) psychic damage, and until the end of its next turn, when the creature makes an attack roll or an ability check, it must roll a d6 and reduce the total by the number rolled. On a successful save, the creature takes half as much damage with no additional effects.


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