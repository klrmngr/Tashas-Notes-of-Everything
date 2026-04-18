---
type: pc
race: "Humanoid (human)"
class:
 - "Karas Chembryl"
subClass:
 - "CR 8"
cover: "Karas Chembryl.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/8
  - source/fraif
---
###### Karas Chembryl
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: FRAiF
___

> [!infobox|no-t right]
> ![[Karas Chembryl.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 17 |
> | :FasHeart: HP | 104 (19d8 + 19) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | FRAiF |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 11 | 20 | 12 | 18 | 15 | 17 |
| **Mod** | +0 | +5 | +1 | +4 | +2 | +3 |

**Speed:** 30 ft., climb 30 ft. &nbsp;|&nbsp; **Senses:** Blindsight 10 ft., passive Perception 18
**Languages:** Common, Elvish, Infernal, Thieves' cant
**Saving Throws:** Dex +8, Con +4, Int +7, Wis +5
**Skills:** Acrobatics +8, Perception +8, Stealth +11
**Damage Resistances:** poison; psychic

---

### Traits

**Evasion.** If Karas is subjected to an effect that allows her to make a Dexterity saving throw to take only half damage, Karas instead takes no damage if she succeeds on the save and only half damage if she fails. She can't use this trait if she has the Incapacitated condition.

**Legendary Resistance (3/Day or 4/Day in Lair).** If Karas fails a saving throw, she can choose to succeed instead.


---

### Actions

**Multiattack.** Karas makes two attacks using Dread Dagger or Tyrant's Blade in any combination.

**Dread Dagger.** m,r +8, reach 5 ft. or range 20/60 ft. *Hit:* 10 (2d4 + 5) Piercing damage plus 4 (1d8) Necrotic damage. The dagger magically returns to Karas's hand immediately after a ranged attack.

**Tyrant's Blade.** m +8, reach 5 ft. *Hit:* 8 (1d6 + 5) Slashing damage, and the target has the Frightened condition until the start of Karas's next turn. If the target is already Frightened, it instead takes 10 (3d6) Psychic damage.


---

### Bonus Actions

**Withdraw.** Karas moves up to half her Speed without provoking Opportunity Attack action and takes the Hide action.


---

### Legendary Actions

### 

**Harrow.** wis DC 15, one creature Karas can see within 90 feet of herself.  10 (3d6) Psychic damage, and the target has the Frightened condition for 1 minute. While Frightened, the target's Speed is 0 feet, and it repeats the save at the end of each of its turns, ending the effect on a success.  Karas can't take this action again until the start of her next turn.

**Stealth Attack.** Karas makes one Dread Dagger attack and uses Withdraw.


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