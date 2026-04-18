---
type: pc
race: "Humanoid"
class:
 - "Sarevok"
subClass:
 - "CR 17"
cover: "Sarevok.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/17
  - source/coa
---
###### Sarevok
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: CoA
___

> [!infobox|no-t right]
> ![[Sarevok.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 17 (18,000 XP) |
> | :RiSwordFill: Type | Medium Humanoid |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 21 (plate armor of Bhaal) |
> | :FasHeart: HP | 190 (20d8 + 100) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | CoA |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 23 | 10 | 21 | 11 | 18 | 14 |
| **Mod** | +6 | +0 | +5 | +0 | +4 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 14
**Languages:** Abyssal, Common, Infernal
**Saving Throws:** Con +11, Wis +10
**Skills:** History +6, Intimidation +14, Religion +6
**Damage Immunities:** acid; necrotic; poison
**Condition Immunities:** charmed; frightened; poisoned

---

### Traits

**Magic Resistance.** Sarevok has advantage on saving throws against spells and other magical effects.

**Rejuvenation.** If Sarevok is killed, he gains a new body in 24 hours, regaining all his hit points. The new body appears on the altar of the temple of Bhaal beneath Baldur's Gate. This ability ceases to function if a cleric of good alignment casts Hallow on the altar in the temple of Bhaal.


---

### Actions

**Multiattack.** Sarevok makes three Longsword attacks. He can replace one of the attacks with Flames of Bhaal or Spellcasting.

**Longsword.** Melee Weapon Attack: +12 to hit, reach 5ft., one target. *Hit:* 10 (1d8 + 6) slashing damage or 11 (1d10 + 6) if wielded in two hands. The target must succeed on a DC 18 Constitution saving throw or be cursed by Bhaal, preventing it from regaining hit points. The curse lasts until removed by the Remove Curse spell or similar effect.

**Flames of Bhaal.** Sarevok causes flames to engulf one creature that he can see within 60 feet. The target must succeed on a DC 18 Dexterity saving throw or take 18 (4d8) necrotic damage. This damage can't be restored except by a Lesser Restoration spell or similar effect.


---

### Legendary Actions

### 

**Slash.** Sarevok makes a Longsword attack.

**Unholy Flame.** Sarevok uses Flames of Bhaal.

**Channel Bhaal's Hate (Costs 2 Actions).** Sarevok unleashes Bhaal's power. Creatures within 30 feet of Sarevok, including ones behind barriers and around corners, can't regain hit points until the end of Sarevok's next turn.


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