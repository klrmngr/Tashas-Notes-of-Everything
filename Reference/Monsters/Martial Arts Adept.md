---
type: pc
race: "Humanoid"
class:
 - "Martial Arts Adept"
subClass:
 - "CR 3"
cover: "Martial Arts Adept.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/3
  - source/mpmm
---
###### Martial Arts Adept
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Martial Arts Adept.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Medium Humanoid |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 16 (Unarmored Defense) |
> | :FasHeart: HP | 60 (11d8 + 11) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 11 | 17 | 13 | 11 | 16 | 10 |
| **Mod** | +0 | +3 | +1 | +0 | +3 | +0 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** passive Perception 13
**Languages:** any one language (usually Common)
**Skills:** Acrobatics +5, Insight +5, Stealth +5

---

### Traits

**Unarmored Defense.** While the adept is wearing no armor and wielding no shield, its AC includes its Wisdom modifier.


---

### Actions

**Multiattack.** The adept makes three Unarmed Strike attacks or five Dart attacks.

**Unarmed Strike.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 7 (1d8 + 3) bludgeoning damage. Once per turn, the adept can cause one of the following additional effects (choose one or roll a d4):
- **1–2: Knock Down..** The target must succeed on a DC 13 Dexterity saving throw or be knocked prone.
- **3–4: Push..** The target must succeed on a DC 13 Strength saving throw or be pushed up to 10 feet directly away from the adept.

**Dart.** Ranged Weapon Attack: +5 to hit, range 20/60 ft., one target. *Hit:* 5 (1d4 + 3) piercing damage.


---

### Reactions

**Deflect Missile.** In response to being hit by a ranged weapon attack, the adept deflects the missile. The damage it takes from the attack is reduced by 1d10 + 3. If the damage is reduced to 0, the adept catches the missile if it's small enough to hold in one hand and the adept has a hand free.


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