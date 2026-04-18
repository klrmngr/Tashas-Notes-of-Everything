---
type: pc
race: "Fiend (yugoloth)"
class:
 - "Ultroloth"
subClass:
 - "CR 13"
cover: "Ultroloth.png"
campaign:
locations:
tags:
  - race/yugoloth
  - affinity/hostile
  - type/fiend
  - size/medium
  - cr/13
  - source/xmm
---
###### Ultroloth
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Ultroloth.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 13 (10,000 XP) |
> | :RiSwordFill: Type | Medium Fiend (yugoloth) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 19 |
> | :FasHeart: HP | 221 (26d8 + 104) |
> | :FasUserGroup: Race | Fiend (yugoloth) |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 16 | 18 | 19 | 15 | 18 |
| **Mod** | +4 | +3 | +4 | +4 | +2 | +4 |

**Speed:** 30 ft., fly 60 ft. ((hover)) &nbsp;|&nbsp; **Senses:** Truesight 120 ft., passive Perception 17
**Languages:** Abyssal, Infernal; telepathy 120 ft.
**Skills:** Deception +9, Perception +7, Stealth +8
**Damage Resistances:** cold; fire; lightning
**Damage Immunities:** acid; poison
**Condition Immunities:** charmed; frightened; poisoned

---

### Traits

**Fiendish Restoration.** If the ultroloth dies outside Gehenna, its body dissolves into ichor, and it gains a new body instantly, reviving with all its Hit Points somewhere in Gehenna.

**Magic Resistance.** The ultroloth has Advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The ultroloth uses Hypnotic Gaze and makes two Mercurial Whip attacks.

**Mercurial Whip.** m +9, reach 15 ft. *Hit:* 25 (6d6 + 4) Force damage, and the ultroloth can teleport the target up to 10 feet to an unoccupied space the ultroloth can see that isn't in the air.

**Hypnotic Gaze.** wis DC 17, each creature in a 30-foot Cone.  10 (3d6) Psychic damage, and the target has the Stunned condition until the start of the ultroloth's next turn.  The target is immune to this ultroloth's Hypnotic Gaze for 24 hours.


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