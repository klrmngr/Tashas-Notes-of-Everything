---
type: pc
race: "Fiend"
class:
 - "Fiendish Spirit"
subClass:
 - "CR —"
cover: "Fiendish Spirit.png"
campaign:
locations:
tags:
  - race/fiend
  - affinity/hostile
  - type/fiend
  - size/large
  - cr/—
  - source/xphb
---
###### Fiendish Spirit
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XPHB
___

> [!infobox|no-t right]
> ![[Fiendish Spirit.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | — (— XP) |
> | :RiSwordFill: Type | Large Fiend |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC |  |
> | :FasHeart: HP | 50 (Demon only) or 40 (Devil only) or 60 (Yugoloth only) + 15 for each spell level above 6 |
> | :FasUserGroup: Race | Fiend |
> | :FasBook: Source | XPHB |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 13 | 16 | 15 | 10 | 10 | 16 |
| **Mod** | +1 | +3 | +2 | +0 | +0 | +3 |

**Speed:** 40 ft., climb 40 ft. ((Demon only)), fly 60 ft. ((Devil only)) &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 10
**Languages:** Abyssal, Infernal, Telepathy 60 ft.
**Damage Resistances:** fire
**Damage Immunities:** poison
**Condition Immunities:** poisoned

---

### Traits

**Death Throes (Demon Only).** When the spirit drops to 0 Hit Points or the spell ends, the spirit explodes. dex DC equals your spell save DC, each creature in a 10-foot Emanation originating from the spirit.  2d10 plus this spell's level Fire damage.  Half damage.

**Devil's Sight (Devil Only).** Magical Darkness doesn't impede the spirit's Darkvision.

**Magic Resistance.** The spirit has Advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The spirit makes a number of attacks equal to half this spell's level (round down).

**Bite (Demon Only).** m Bonus equals your spell attack modifier, reach 5 ft. *Hit:* 1d12 + 3 + summonSpellLevel Necrotic damage.

**Claws (Yugoloth Only).** m Bonus equals your spell attack modifier, reach 5 ft. *Hit:* 1d8 + 3 + summonSpellLevel Slashing damage. Immediately after the attack hits or misses, the spirit can teleport up to 30 feet to an unoccupied space it can see.

**Fiery Strike (Devil Only).** m,r Bonus equals your spell attack modifier, reach 5 ft. or range 150 ft. *Hit:* 2d6 + 3 + summonSpellLevel Fire damage.


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