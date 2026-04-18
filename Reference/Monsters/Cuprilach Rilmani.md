---
type: pc
race: "Celestial"
class:
 - "Cuprilach Rilmani"
subClass:
 - "CR 12"
cover: "Cuprilach Rilmani.png"
campaign:
locations:
tags:
  - race/celestial
  - affinity/hostile
  - type/celestial
  - size/medium
  - cr/12
  - source/mpp
---
###### Cuprilach Rilmani
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MPP
___

> [!infobox|no-t right]
> ![[Cuprilach Rilmani.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 12 (8,400 XP) |
> | :RiSwordFill: Type | Medium Celestial |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 202 (27d8 + 81) |
> | :FasUserGroup: Race | Celestial |
> | :FasBook: Source | MPP |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 20 | 16 | 16 | 15 | 14 |
| **Mod** | +1 | +5 | +3 | +3 | +2 | +2 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** truesight 120 ft., passive Perception 16
**Languages:** telepathy 120 ft., any four languages
**Saving Throws:** Dex +9, Cha +6
**Skills:** Perception +6, Stealth +13
**Damage Resistances:** psychic

---

### Actions

**Multiattack.** The cuprilach makes three Burnished Blade or Bolt attacks.

**Burnished Blade.** Melee Weapon Attack: +9 to hit, reach 5 ft., one target. *Hit:* 8 (1d6 + 5) piercing damage plus 13 (2d12) psychic damage.

**Bolt.** Ranged Weapon Attack: +9 to hit, range 20/60 ft., one target. *Hit:* 7 (1d4 + 5) piercing damage plus 13 (2d12) psychic damage.


---

### Bonus Actions

**Assassin's Agility.** The cuprilach takes the Dash or Disengage action, or it makes one Burnished Blade attack.


---

### Reactions

**Uncanny Dodge.** The cuprilach halves the damage it takes from an attack that hits it, provided it can see the attacker.


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