---
type: pc
race: "Monstrosity"
class:
 - "Thri-kreen Mystic"
subClass:
 - "CR 5"
cover: "Thri-kreen Mystic.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/medium
  - cr/5
  - source/bam
---
###### Thri-kreen Mystic
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Boo's Astral Menagerie
___

> [!infobox|no-t right]
> ![[Thri-kreen Mystic.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Medium Monstrosity |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 99 (18d8 + 18) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | Boo's Astral Menagerie |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 15 | 13 | 12 | 16 | 10 |
| **Mod** | +1 | +2 | +1 | +1 | +3 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 16
**Languages:** telepathy 60 ft., Thri-kreen
**Skills:** Perception +6, Stealth +5, Survival +6

---

### Actions

**Multiattack.** The thri-kreen makes two Gythka attacks or four Psychic Bolt attacks.

**Gythka.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 10 (2d8 + 1) slashing damage.

**Psychic Bolt.** Ranged Spell Attack: +6 to hit, range 60 ft., one creature. *Hit:* 6 (1d6 + 3) psychic damage.

**Drain Vitality (Recharges after a Short or Long Rest).** The thri-kreen targets one creature it can see within 30 feet of itself. The target must make a DC 14 Constitution saving throw, taking 32 (5d12) necrotic damage on a failed save, or half as much damage on a successful one. The thri-kreen regains hit points equal to the damage dealt.


---

### Bonus Actions

**Chameleon Carapace.** The thri-kreen changes the color of its carapace to match the color and texture of its surroundings, gaining advantage on Dexterity (Stealth) checks it makes to hide in those surroundings.


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