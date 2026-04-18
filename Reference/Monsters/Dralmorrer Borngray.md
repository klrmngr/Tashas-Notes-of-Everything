---
type: pc
race: "Humanoid (elf)"
class:
 - "Dralmorrer Borngray"
subClass:
 - "CR 3"
cover: "Dralmorrer Borngray.png"
campaign:
locations:
tags:
  - race/elf
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/3
  - source/hotdq
---
###### Dralmorrer Borngray
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Hoard of the Dragon Queen
___

> [!infobox|no-t right]
> ![[Dralmorrer Borngray.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Medium Humanoid (elf) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 16 (studded leather, shield) |
> | :FasHeart: HP | 52 (7d10 + 14) |
> | :FasUserGroup: Race | Humanoid (elf) |
> | :FasBook: Source | Hoard of the Dragon Queen |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 14 | 14 | 16 | 10 | 8 |
| **Mod** | +4 | +2 | +2 | +3 | +0 | -1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 12
**Languages:** Common, Bullywug, Draconic, Elvish, Goblin, Sylvan
**Saving Throws:** Str +6, Con +4
**Skills:** Arcana +5, Deception +1, Insight +2, Perception +2, Religion +5

---

### Traits

**Fey Ancestry.** Dralmorrer has advantage on saving throws against being charmed, and magic can't put him to sleep.

**War Magic.** When Dralmorrer uses his action to cast a cantrip, he can also take a bonus action to make one weapon attack.

**Weapon Bond.** Provided his longsword is on the same plane Dralmorrer can take a bonus action to teleport it to his hand.


---

### Actions

**Multiattack.** Dralmorrer attacks twice, either with his longsword or dagger.

**Longsword.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 8 (1d8 + 4) slashing damage.

**Dagger.** Melee or Ranged Weapon Attack: +6 to hit, reach 5 ft. or ranged 20/60 ft., one target. *Hit:* 6 (1d4 + 4) piercing damage.


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