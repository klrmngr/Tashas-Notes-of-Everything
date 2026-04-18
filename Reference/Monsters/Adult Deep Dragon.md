---
type: pc
race: "Dragon"
class:
 - "Adult Deep Dragon"
subClass:
 - "CR 11"
cover: "Adult Deep Dragon.png"
campaign:
locations:
tags:
  - race/dragon
  - affinity/hostile
  - type/dragon
  - size/huge
  - cr/11
  - source/fraif
---
###### Adult Deep Dragon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: FRAiF
___

> [!infobox|no-t right]
> ![[Adult Deep Dragon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 11 (7,200 XP) |
> | :RiSwordFill: Type | Huge Dragon |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 17 |
> | :FasHeart: HP | 161 (17d12 + 51) |
> | :FasUserGroup: Race | Dragon |
> | :FasBook: Source | FRAiF |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 14 | 17 | 16 | 16 | 18 |
| **Mod** | +5 | +2 | +3 | +3 | +3 | +4 |

**Speed:** 40 ft., burrow 30 ft., fly 80 ft., swim 40 ft. &nbsp;|&nbsp; **Senses:** Blindsight 60 ft., Darkvision 150 ft., passive Perception 21
**Languages:** Common, Draconic, Undercommon
**Saving Throws:** Dex +6, Wis +7
**Skills:** Perception +11, Stealth +10
**Damage Resistances:** poison; psychic
**Condition Immunities:** charmed; frightened; poisoned

---

### Traits

**Legendary Resistance (3/Day, or 4/Day in Lair).** If the dragon fails a saving throw, it can choose to succeed instead.


---

### Actions

**Multiattack.** The dragon makes three Rend attacks.

**Rend.** m +9, reach 10 ft. *Hit:* 14 (2d8 + 5) Slashing damage plus 5 (1d10) Poison damage.

**Nightmare Breath (Recharge 5–6).** wis DC 15, each creature in a 30-foot Cone.  38 (7d10) Psychic damage, and the target has the Frightened condition until the end of the dragon's next turn.  Half damage only.


---

### Bonus Actions

**Shape-Shift.** The dragon shape-shifts into a Small or Medium Humanoid or a Small or Medium Beast, or it returns to its true form. Its game statistics, other than its size, are the same in each form. Any equipment it is wearing or carrying isn't transformed.


---

### Legendary Actions

### 

**Pounce.** The dragon moves up to half its Speed, and it makes one Rend attack.

**Spore Salvo.** con DC 15, one creature within 30 feet of the dragon that it can see.  13 (3d8) Poison damage, and the target has the Poisoned condition. It repeats the save at the end of each of its turns, ending the effect on itself on a success. After 1 minute, it succeeds automatically.  The dragon can't take this action again until the start of its next turn.


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