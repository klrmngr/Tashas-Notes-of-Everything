---
type: pc
race: "Aberration"
class:
 - "Gaj"
subClass:
 - "CR 4"
cover: "Gaj.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/large
  - cr/4
  - source/bam
---
###### Gaj
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Boo's Astral Menagerie
___

> [!infobox|no-t right]
> ![[Gaj.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Large Aberration |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 75 (10d10 + 20) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | Boo's Astral Menagerie |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 10 | 15 | 12 | 15 | 7 |
| **Mod** | +3 | +0 | +2 | +1 | +2 | -2 |

**Speed:** 30 ft., climb 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 16
**Languages:** understands all languages but can't speak
**Skills:** Perception +6, Stealth +4

---

### Actions

**Multiattack.** The gaj makes one Mandibles attack and uses Mind-Probing Antennae or Paralyze (if available).

**Mandibles.** Melee Weapon Attack: +5 to hit, reach 5 ft., one creature. *Hit:* 10 (2d6 + 3) slashing damage, and the target is grappled (escape DC 11). Until the grapple ends, the target takes 10 (2d6 + 3) slashing damage at the start of each of the gaj's turns. While it is grappling a creature, the gaj can't use its mandibles to attack other creatures.

**Mind-Probing Antennae.** The gaj targets one creature grappled by it. The target must make a DC 12 Wisdom saving throw. On a failed save, the target takes 16 (3d10) psychic damage, and the gaj magically pulls one piece of information from the target's mind that the gaj wants to know. On a successful save, the target takes half as much damage, and the gaj learns nothing.

**Paralyze (Recharge 6).** The gaj magically targets one creature it can see within 60 feet of itself. The target must succeed on a DC 12 Wisdom saving throw or be paralyzed for 1 minute. The target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.


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