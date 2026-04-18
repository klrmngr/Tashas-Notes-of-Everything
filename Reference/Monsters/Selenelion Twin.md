---
type: pc
race: "Humanoid (elf)"
class:
 - "Selenelion Twin"
subClass:
 - "CR 2"
cover: "Selenelion Twin.png"
campaign:
locations:
tags:
  - race/elf
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/2
  - source/wbtw
---
###### Selenelion Twin
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: The Wild Beyond the Witchlight
___

> [!infobox|no-t right]
> ![[Selenelion Twin.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Humanoid (elf) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Good |
> | :FasShield: AC | 14 |
> | :FasHeart: HP | 33 (6d8 + 6) |
> | :FasUserGroup: Race | Humanoid (elf) |
> | :FasBook: Source | The Wild Beyond the Witchlight |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 7 | 18 | 13 | 12 | 10 | 17 |
| **Mod** | -2 | +4 | +1 | +1 | +0 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 10
**Languages:** Common, Elvish
**Saving Throws:** Dex +6, Cha +5
**Skills:** Acrobatics +8, Sleight Of Hand +6, Stealth +6

---

### Traits

**Fey Ancestry.** The Selenelion twins, Gleam and Glister, have advantage on saving throws against being charmed, and magic can't put them to sleep.

**Regeneration.** A Selenelion twin regains 5 hit points at the start of her turn as long as both twins are alive and within 60 feet of each other. A twin dies only if she starts her turn with 0 hit points and doesn't regenerate.

**Twin Bond.** While both Selenelion twins are alive and on the same plane of existence, each is aware of the other's emotions.


---

### Actions

**Dagger.** Melee or Ranged Weapon Attack: +6 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* 6 (1d4 + 4) piercing damage.

**Moon Ray (Gleam Only; 3/Day).** Ranged Spell Attack: +5 to hit, range 60 ft., one creature. *Hit:* 12 (2d8 + 3) radiant damage, and the target must succeed on a DC 13 Wisdom saving throw or be transformed into a bat for 1 minute, as though affected by a polymorph spell. The target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

**Sun Ray (Glister Only; 3/Day).** Ranged Spell Attack: +5 to hit, range 60 ft., one creature. *Hit:* 12 (2d8 + 3) radiant damage, and the target must succeed on a DC 13 Wisdom saving throw or be blinded for 1 minute. The target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

**Twin Sight (Recharges after a Short or Long Rest).** In her mind's eye, a Selenelion twin can see what the other twin sees for up to 1 minute, provided both twins are alive and on the same plane of existence. Maintaining this effect requires concentration (as if concentrating on a spell).


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