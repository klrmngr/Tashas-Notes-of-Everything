---
type: pc
race: "Fey (sorcerer)"
class:
 - "High Fae Mage"
subClass:
 - "CR 12"
cover: "High Fae Mage.png"
campaign:
locations:
tags:
  - race/sorcerer
  - affinity/hostile
  - type/fey
  - size/medium
  - cr/12
  - source/mcv4ec
---
###### High Fae Mage
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MCV4EC
___

> [!infobox|no-t right]
> ![[High Fae Mage.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 12 (8,400 XP) |
> | :RiSwordFill: Type | Medium Fey (sorcerer) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 14; 17 with mage armor |
> | :FasHeart: HP | 148 (27d8 + 27) |
> | :FasUserGroup: Race | Fey (sorcerer) |
> | :FasBook: Source | MCV4EC |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 11 | 18 | 12 | 17 | 15 | 24 |
| **Mod** | +0 | +4 | +1 | +3 | +2 | +7 |

**Speed:** 30 ft., fly 30 ft. ((hover)) &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 12
**Languages:** Common, Sylvan
**Saving Throws:** Int +7, Wis +6, Cha +11
**Skills:** Arcana +11, Investigation +7, Nature +7
**Damage Resistances:** bludgeoning, piercing, slashing from nonmagical attacks

---

### Traits

**Magic Resistance.** The high fae has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The high fae makes two Elemental Strike attacks.

**Elemental Strike.** Melee or Ranged Spell Attack: +11 to hit, reach 5 ft. or range 60 ft., one target. *Hit:* 18 (2d10 + 7) acid, cold, fire, force, lightning, or thunder damage (the high fae's choice).

**Negotiate Life (Recharge 5–6).** The high fae enacts a magical bargain, siphoning energy from its opponents to heal its wounds. The high fae targets up to three creatures it can see within 60 feet of itself. Each target must make a DC 19 Constitution saving throw, taking 26 (4d12) necrotic damage on a failed save, or half as much damage on a successful one. The high fae then regains 30 hit points.


---

### Reactions

**Fae Counterspell.** The high fae interrupts a creature it can see that is casting a spell with verbal, somatic, or material components. The caster takes 10 (3d6) psychic damage and must make a DC 19 Charisma saving throw. On a failed save, the spell fails and has no effect, but the spell slot used to cast it is not expended.


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