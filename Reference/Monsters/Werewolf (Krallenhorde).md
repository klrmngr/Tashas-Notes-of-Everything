---
type: pc
race: "Humanoid (human, shapechanger)"
class:
 - "Werewolf (Krallenhorde)"
subClass:
 - "CR 3"
cover: "Werewolf (Krallenhorde).png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/3
  - source/psi
---
###### Werewolf (Krallenhorde)
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: PSI
___

> [!infobox|no-t right]
> ![[Werewolf (Krallenhorde).png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human, shapechanger) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 11 in humanoid form; 12 (natural armor) in canid form |
> | :FasHeart: HP | 58 (9d8 + 18) |
> | :FasUserGroup: Race | Humanoid (human, shapechanger) |
> | :FasBook: Source | PSI |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 15 | 13 | 14 | 10 | 11 | 10 |
| **Mod** | +2 | +1 | +2 | +0 | +0 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 14
**Languages:** Common (can't speak in canid form)
**Skills:** Perception +4, Stealth +3
**Damage Immunities:** bludgeoning, piercing, slashing from nonmagical attacks not made with silvered weapons

---

### Traits

**Shapechanger.** The werewolf polymorphs into a wolf-humanoid canid form, or back into its true human form. This change is dictated by the moon, but can also be induced by trauma or strong emotion. Its statistics, other than its AC, are the same in each form. Any equipment it is wearing or carrying isn't transformed. It reverts to its true form if it dies.

**Keen Hearing and Smell.** The werewolf has advantage on Wisdom (Perception) checks that rely on hearing or smell.

**Howlpack: Vildin.** Vildin Rampage (Canid Form Only). When the werewolf reduces a creature to 0 hit points with a melee attack on its turn, it can take a bonus action to move up to half its speed and make a bite attack.


---

### Actions

**Multiattack (Canid Form Only).** The werewolf makes two attacks: one with its bite and one with its claws or spear.

**Bite (Canid Form Only).** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 6 (1d8 + 2) piercing damage.

**Claws (Canid Form Only).** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 7 (2d4 + 2) slashing damage.

**Spear (Human Form Only).** Melee or Ranged Weapon Attack: +4 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* 5 (1d6 + 2) piercing damage, or 6 (1d8 + 2) piercing damage if used with two hands to make a melee attack.


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