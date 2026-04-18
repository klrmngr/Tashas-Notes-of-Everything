---
type: pc
race: "Aberration"
class:
 - "Feyr"
subClass:
 - "CR 5"
cover: "Feyr.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/large
  - cr/5
  - source/bam
---
###### Feyr
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Boo's Astral Menagerie
___

> [!infobox|no-t right]
> ![[Feyr.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Large Aberration |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 88 (16d10) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | Boo's Astral Menagerie |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 16 | 11 | 14 | 14 | 11 |
| **Mod** | +3 | +3 | +0 | +2 | +2 | +0 |

**Speed:** 0 ft., fly 50 ft. ((hover)) &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 15
**Languages:** —
**Saving Throws:** Int +5, Wis +5
**Skills:** Perception +5, Stealth +9
**Condition Immunities:** frightened

---

### Traits

**Unusual Nature.** The feyr doesn't require air.


---

### Actions

**Multiattack.** The feyr makes one Frightful Bite attack and one Tentacle attack.

**Frightful Bite.** Melee Weapon Attack: +6 to hit, reach 5 ft., one creature. *Hit:* 8 (1d10 + 3) piercing damage, and each creature within 10 feet of the feyr that can see it must succeed on a DC 13 Wisdom saving throw or be frightened of the feyr until the end of the feyr's next turn.

**Tentacle.** Melee Weapon Attack: +6 to hit, reach 10 ft., one creature. *Hit:* 17 (4d6 + 3) psychic damage, and the target is grappled (escape DC 13). Until this grapple ends, the feyr can't use this tentacle against other targets. The feyr has two tentacles, each of which can grapple one creature.

**Invisibility.** The feyr becomes invisible until it attacks, uses Nightmare Fuel, or uses a bonus action to become visible.

**Nightmare Fuel (1/Day).** The feyr targets one unconscious creature it can see within 10 feet of itself. The target must succeed on a DC 13 Wisdom saving throw or take 27 (5d10) psychic damage, and the feyr gains temporary hit points equal to the damage dealt.


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