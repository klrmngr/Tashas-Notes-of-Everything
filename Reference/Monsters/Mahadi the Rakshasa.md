---
type: pc
race: "Fiend"
class:
 - "Mahadi the Rakshasa"
subClass:
 - "CR 14"
cover: "Mahadi the Rakshasa.png"
campaign:
locations:
tags:
  - race/fiend
  - affinity/hostile
  - type/fiend
  - size/medium
  - cr/14
  - source/bgdia
---
###### Mahadi the Rakshasa
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: BGDIA
___

> [!infobox|no-t right]
> ![[Mahadi the Rakshasa.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 14 (11,500 XP) |
> | :RiSwordFill: Type | Medium Fiend |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 195 (23d8 + 92) |
> | :FasUserGroup: Race | Fiend |
> | :FasBook: Source | BGDIA |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 18 | 18 | 14 | 18 | 20 |
| **Mod** | +2 | +4 | +4 | +2 | +4 | +5 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 19
**Languages:** all (can read only), Common, Infernal
**Saving Throws:** Wis +9, Cha +10
**Skills:** Arcana +7, Deception +10, Insight +9, Perception +9
**Damage Vulnerabilities:** piercing from magic weapons wielded by good creatures
**Damage Resistances:** bludgeoning, piercing, slashing from nonmagical attacks

---

### Traits

**Limited Magic Immunity.** Mahadi can't be affected or detected by spells of 6th level or lower unless he wishes to be. He has advantage on saving throws against all other spells and magical effects.

**Magic Weapons.** Mahadi's weapon attacks are magical.


---

### Actions

**Multiattack.** Mahadi makes four claw attacks.

**Claw.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 9 (2d6 + 2) slashing damage, and the target is cursed if it's a creature. The curse takes effect whenever the target takes a short or long rest, filling the target's thoughts with horrible images and dreams. The cursed target gains no benefit from finishing a short or long rest. The curse lasts until it is lifted by a remove curse spell or similar magic.

**Summon Erinyes (1/Day).** Mahadi summons Ilzabet, an erinyes bound to him by an infernal contract. The erinyes appears in an unoccupied space within 60 feet of him, acts as his ally, and can't summon other devils. The erinyes remains for 10 minutes or until Mahadi dismisses it as an action. If the erinyes dies, Mahadi loses this action option.


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