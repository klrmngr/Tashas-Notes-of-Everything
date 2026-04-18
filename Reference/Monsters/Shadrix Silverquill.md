---
type: pc
race: "Dragon (bard)"
class:
 - "Shadrix Silverquill"
subClass:
 - "CR 22"
cover: "Shadrix Silverquill.png"
campaign:
locations:
tags:
  - race/bard
  - affinity/hostile
  - type/dragon
  - size/gargantuan
  - cr/22
  - source/scc
---
###### Shadrix Silverquill
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Strixhaven: A Curriculum of Chaos
___

> [!infobox|no-t right]
> ![[Shadrix Silverquill.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 22 (41,000 XP) |
> | :RiSwordFill: Type | Gargantuan Dragon (bard) |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 21 (natural armor) |
> | :FasHeart: HP | 363 (22d20 + 132) |
> | :FasUserGroup: Race | Dragon (bard) |
> | :FasBook: Source | Strixhaven: A Curriculum of Chaos |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 25 | 14 | 23 | 18 | 18 | 26 |
| **Mod** | +7 | +2 | +6 | +4 | +4 | +8 |

**Speed:** 40 ft., fly 80 ft. &nbsp;|&nbsp; **Senses:** blindsight 120 ft., passive Perception 21
**Languages:** all
**Saving Throws:** Dex +9, Con +13, Wis +11, Cha +15
**Skills:** Arcana +18, Deception +15, Perception +11, Persuasion +15
**Damage Immunities:** psychic; radiant

---

### Traits

**Legendary Resistance (3/Day).** If Shadrix fails a saving throw, he can choose to succeed instead.


---

### Actions

**Multiattack.** Shadrix makes one Bite attack and two Claw attacks.

**Bite.** Melee Weapon Attack: +14 to hit, reach 15 ft., one target. *Hit:* 12 (1d10 + 7) piercing damage plus 4 (1d8) radiant damage.

**Claw.** Melee Weapon Attack: +14 to hit, reach 10 ft., one target. *Hit:* 10 (1d6 + 7) slashing damage. If the target is a creature, it is wracked with despair and has disadvantage on attack rolls until the end of its next turn.

**Illuminating Shadow Breath (Recharge 5–6).** Shadrix exhales an entwined burst of blinding radiance and unnerving shadow in a 90-foot cone. Each creature in that area must make a DC 21 Constitution saving throw. On a failed save, a creature takes 31 (7d8) radiant damage and 31 (7d8) psychic damage and is blinded until the start of Shadrix's next turn. On a successful save, a creature takes half as much damage and isn't blinded.


---

### Legendary Actions

### 

**Claw.** Shadrix makes one Claw attack.

**Shadow Slip (Costs 2 Actions).** Shadrix becomes an inky cloud of shadow and can move up to half his flying speed without provoking opportunity attacks, then resumes his true form. During this movement, he can move through creatures and objects as if they were 3. If he moves through a creature, it must succeed on a DC 21 Constitution saving throw or become blinded until the end of its next turn. If Shadrix ends this move inside an object, he takes 5 (1d10) force damage and is shunted to the nearest unoccupied space.

**Flash of Inspiration (Costs 3 Actions).** Shadrix magically summons 1d4 [[Inkling Mascot|inkling mascots]] in unoccupied spaces he can see within 60 feet of himself. The inklings obey his commands and take their turns immediately after his. While any of these inklings live, Shadrix has advantage on attack rolls and saving throws. These inklings disappear after 10 minutes, when Shadrix dies, or when he uses this action again.


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