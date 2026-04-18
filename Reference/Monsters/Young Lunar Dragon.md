---
type: pc
race: "Dragon"
class:
 - "Young Lunar Dragon"
subClass:
 - "CR 7"
cover: "Young Lunar Dragon.png"
campaign:
locations:
tags:
  - race/dragon
  - affinity/hostile
  - type/dragon
  - size/large
  - cr/7
  - source/bam
---
###### Young Lunar Dragon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Boo's Astral Menagerie
___

> [!infobox|no-t right]
> ![[Young Lunar Dragon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 7 (2,900 XP) |
> | :RiSwordFill: Type | Large Dragon |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 123 (13d10 + 52) |
> | :FasUserGroup: Race | Dragon |
> | :FasBook: Source | Boo's Astral Menagerie |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 12 | 18 | 8 | 10 | 13 |
| **Mod** | +4 | +1 | +4 | -1 | +0 | +1 |

**Speed:** 40 ft., burrow 20 ft., fly 80 ft. &nbsp;|&nbsp; **Senses:** darkvision 240 ft., passive Perception 16
**Languages:** Draconic
**Saving Throws:** Con +7, Wis +3
**Skills:** Perception +6, Stealth +7
**Damage Immunities:** cold

---

### Traits

**Tunneler.** The dragon can burrow through solid rock at half its burrowing speed and leaves a 10-foot-diameter tunnel in its wake.

**Unusual Nature.** The dragon doesn't require air.


---

### Actions

**Multiattack.** The dragon makes one Bite attack and two Claw attacks.

**Bite.** Melee Weapon Attack: +7 to hit, reach 10 ft., one target. *Hit:* 7 (1d6 + 4) piercing damage plus 3 (1d6) cold damage.

**Claw.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 7 (1d6 + 4) slashing damage.

**Cold Breath (Recharge 5–6).** The dragon exhales a blast of frost in a 30-foot cone. Each creature in the cone must make a DC 15 Constitution saving throw. On a failed save, the creature takes 27 (6d8) cold damage, and its speed is halved until the end of its next turn. On a successful save, the creature takes half as much damage, and its speed isn't reduced.


---

### Bonus Actions

**Phase (2/Day).** The dragon becomes partially incorporeal for as long as it maintains concentration on the effect (as if concentrating on a spell). While partially incorporeal, the dragon has resistance to bludgeoning, piercing, and slashing damage.


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