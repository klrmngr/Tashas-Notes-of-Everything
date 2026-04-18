---
type: pc
race: "Dragon"
class:
 - "Ender Dragon"
subClass:
 - "CR 19"
cover: "Ender Dragon.png"
campaign:
locations:
tags:
  - race/dragon
  - affinity/hostile
  - type/dragon
  - size/gargantuan
  - cr/19
  - source/mcv3mc
---
###### Ender Dragon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MCV3MC
___

> [!infobox|no-t right]
> ![[Ender Dragon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 19 (22,000 XP) |
> | :RiSwordFill: Type | Gargantuan Dragon |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 22 (natural armor) |
> | :FasHeart: HP | 350 (20d20 + 140) |
> | :FasUserGroup: Race | Dragon |
> | :FasBook: Source | MCV3MC |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 27 | 14 | 25 | 10 | 15 | 19 |
| **Mod** | +8 | +2 | +7 | +0 | +2 | +4 |

**Speed:** 30 ft., fly 120 ft. &nbsp;|&nbsp; **Senses:** darkvision 240 ft., passive Perception 24
**Languages:** Draconic
**Saving Throws:** Con +13, Int +6, Wis +8
**Skills:** Perception +14, Stealth +8
**Damage Resistances:** fire
**Damage Immunities:** necrotic
**Condition Immunities:** charmed; frightened

---

### Traits

**Dragon Egg.** When the Ender Dragon drops to 0 hit points, it radiates beams of purple light and then disappears, leaving behind an inert, jet-black dragon egg worth 5,000 gp.

**Legendary Resistance (4/Day).** If the dragon fails a saving throw, it can choose to succeed instead.


---

### Actions

**Multiattack.** The dragon makes one Bite attack and uses Beating Wings.

**Bite.** Melee Weapon Attack: +14 to hit; reach 15 ft., one target. *Hit:* 18 (3d6 + 8) piercing damage plus 7 (2d6) necrotic damage.

**Beating Wings.** The dragon beats its great wings. Each creature within 15 feet of the dragon must succeed on a DC 21 Dexterity saving throw or take 10 (1d4 + 8) bludgeoning damage, be pushed 10 feet away from the dragon, and have the prone condition.

**Harmful Breath (Recharge 5–6).** The dragon exhales putrid gas in a 60-foot cone. Each creature in that area must make a DC 21 Constitution saving throw, taking 52 (15d6) necrotic damage on a failed save, or half as much damage on a successful one. The dragon then chooses a point it can see where the cone makes contact with the ground. That point becomes the center of a 10-foot-high, 10-foot-radius cylinder of lingering gas that disappears at the start of the dragon's next turn. Any creature that starts its turn in the cylinder takes 10 (3d6) necrotic damage.


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