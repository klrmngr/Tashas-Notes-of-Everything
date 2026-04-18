---
type: pc
race: "Aberration"
class:
 - "Death Embrace"
subClass:
 - "CR 11"
cover: "Death Embrace.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/huge
  - cr/11
  - source/crcotn
---
###### Death Embrace
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Critical Role: Call of the Netherdeep
___

> [!infobox|no-t right]
> ![[Death Embrace.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 11 (7,200 XP) |
> | :RiSwordFill: Type | Huge Aberration |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 13 (natural armor) |
> | :FasHeart: HP | 147 (14d12 + 56) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | Critical Role: Call of the Netherdeep |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 23 | 15 | 19 | 6 | 9 | 4 |
| **Mod** | +6 | +2 | +4 | -2 | -1 | -3 |

**Speed:** 0 ft., swim 20 ft. &nbsp;|&nbsp; **Senses:** blindsight 60 ft. (blind beyond this radius), passive Perception 9
**Languages:** —
**Saving Throws:** Str +10, Wis +3
**Condition Immunities:** exhaustion; paralyzed; petrified; prone

---

### Traits

**Petrifying Tendrils.** Any creature that starts its turn in the death embrace's space must make a DC 16 Constitution saving throw. On a failed saving throw, the creature is restrained. A creature restrained in this way must repeat the saving throw at the end of its next turn, becoming petrified on a failed saving throw or ending the effect on a successful one. The petrified condition lasts until the effect is ended by a greater restoration spell or similar magic.

**Reel.** At the start of each of its turns, the death embrace can pull each creature it is grappling up to 20 feet toward it (no action required).

**Water Breathing.** The death embrace can breathe only underwater.


---

### Actions

**Multiattack.** The death embrace makes two Tentacle attacks.

**Tentacle.** Melee Weapon Attack: +10 to hit, reach 60 ft., one target. *Hit:* 13 (2d6 + 6) piercing damage plus 11 (2d10) psychic damage. If the target is Large or smaller, it is also grappled (escape DC 16). The death embrace has six tentacles, each of which can grapple one target.


---

### Reactions

**Body Shield.** When the death embrace is hit by an attack, one creature the death embrace is grappling (chosen by the death embrace) takes the damage instead.


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