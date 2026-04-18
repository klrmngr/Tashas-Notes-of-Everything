---
type: pc
race: "Humanoid"
class:
 - "Wolfwere"
subClass:
 - "CR 4"
cover: "Wolfwere.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/4
  - source/mabjov
---
###### Wolfwere
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MaBJoV
___

> [!infobox|no-t right]
> ![[Wolfwere.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Medium Humanoid |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 12 while in humanoid form; 13 while in wolf/hybrid form |
> | :FasHeart: HP | 55 (10d8 + 10) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | MaBJoV |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 14 | 12 | 10 | 8 | 15 |
| **Mod** | +4 | +2 | +1 | +0 | -1 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 13
**Languages:** Common (can't speak in wolf form)
**Skills:** Perception +4
**Damage Immunities:** bludgeoning, piercing, slashing damage from nonmagical weapons that aren't iron

---

### Traits

**Keen Hearing and Smell.** The wolfwere has advantage on Wisdom (Perception) checks that rely on hearing or smell.

**Pack Tactics.** The wolfwere has advantage on an attack roll against a creature if at least one of the wolfwere's allies is within 5 feet of the creature and the ally isn't incapacitated.


---

### Actions

**Multiattack (Hybrid form only).** The wolfwere makes two attacks: one with its Bite and one with its Claws.

**Longsword (Humanoid form only).** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 9 (1d8 + 4) slashing damage or 10 (1d10 + 5) slashing damage if used with two hands.

**Bite (Wolf or Hybrid form only).** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 11 (2d6 + 4) piercing damage. If the target is a creature, it must succeed on a DC 14 Strength saving throw or be knocked prone.

**Claws (Hybrid form only).** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 9 (2d4 + 4) slashing damage.

**Lethargic Song (Humanoid form only).** The wolfwere plays a magical melody on an instrument. Every Humanoid within 200 feet of the wolfwere that hears the melody must succeed on a DC 13 Wisdom saving throw or be slowed for 10 minutes, as if the slow spell has been cast on them. A creature can repeat the saving throw at the end of each of its turns. If a creature's saving throw is successful, the effect ends on it. A target that successfully saves is immune to this wolfwere's melody for the next 24 hours.

**Change Shape.** The wolfwere polymorphs into a wolf-humanoid hybrid or into a Humanoid (elf or human), or back into its true form, which is a dire wolf. Its statistics, other than its AC, are the same in each form. Any equipment it is wearing or carrying isn't transformed. It reverts to its true form if it dies


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