---
type: pc
race: "Humanoid (grung)"
class:
 - "King Robbit the Slimy"
subClass:
 - "CR 2"
cover: "King Robbit the Slimy.png"
campaign:
locations:
tags:
  - race/grung
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/2
  - source/mgelft
---
###### King Robbit the Slimy
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MGELFT
___

> [!infobox|no-t right]
> ![[King Robbit the Slimy.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Small Humanoid (grung) |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | — |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 27 (5d6 + 10) |
> | :FasUserGroup: Race | Humanoid (grung) |
> | :FasBook: Source | MGELFT |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 7 | 16 | 15 | 10 | 11 | 15 |
| **Mod** | -2 | +3 | +2 | +0 | +0 | +2 |

**Speed:** 25 ft., climb 25 ft. &nbsp;|&nbsp; **Senses:** passive Perception 12
**Languages:** Grung
**Saving Throws:** Dex +5
**Skills:** Athletics +2, Intimidation +4, Perception +2, Stealth +5
**Damage Immunities:** poison
**Condition Immunities:** charmed; poisoned

---

### Traits

**Amphibious.** The grung can breathe air and water.

**Poisonous Skin.** Any creature that grapples the grung or otherwise comes into direct contact with the grung's skin must succeed on a DC 12 Constitution saving throw or become poisoned for 1 minute. A poisoned creature no longer in direct contact with the grung can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

**Standing Leap.** The grung's long jump is up to 25 feet and its high jump is up to 15 feet, with or without a running start.


---

### Actions

**Grumpy Grung Growl.** A ferocious gurgling issues from the throat of the Dankwood grung, warning those within 15 feet that they are indeed grumpy. Creatures in that area must succeed at a DC 12 Charisma saving throw or be frightened until the end of their next turn.

**Dagger.** Melee or Ranged Weapon Attack: +0 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* 3 (1d4 + 1) piercing damage in melee, or 3 (1d4 + 1) piercing damage at range. Target must succeed on a DC 12 Constitution saving throw or take 5 (2d4) poison damage.

**Shortbow.** Ranged Weapon Attack: +5 to hit, range 80/320 ft., one target. *Hit:* 9 (1d6 + 6) piercing damage. Target must succeed on a DC 12 Constitution saving throw or take 5 (2d4) poison damage.


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