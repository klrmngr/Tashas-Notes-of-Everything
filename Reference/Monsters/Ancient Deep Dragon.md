---
type: pc
race: "Dragon"
class:
 - "Ancient Deep Dragon"
subClass:
 - "CR 18"
cover: "Ancient Deep Dragon.png"
campaign:
locations:
tags:
  - race/dragon
  - affinity/hostile
  - type/dragon
  - size/gargantuan
  - cr/18
  - source/fraif
---
###### Ancient Deep Dragon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: FRAiF
___

> [!infobox|no-t right]
> ![[Ancient Deep Dragon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 18 (20,000 XP) |
> | :RiSwordFill: Type | Gargantuan Dragon |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 20 |
> | :FasHeart: HP | 247 (15d20 + 90) |
> | :FasUserGroup: Race | Dragon |
> | :FasBook: Source | FRAiF |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 23 | 16 | 22 | 19 | 18 | 21 |
| **Mod** | +6 | +3 | +6 | +4 | +4 | +5 |

**Speed:** 40 ft., burrow 40 ft., fly 80 ft., swim 40 ft. &nbsp;|&nbsp; **Senses:** Blindsight 60 ft., Darkvision 300 ft., passive Perception 26
**Languages:** Common, Draconic, Undercommon
**Saving Throws:** Dex +9, Wis +10
**Skills:** Perception +16, Stealth +15
**Damage Resistances:** poison; psychic
**Condition Immunities:** charmed; frightened; poisoned

---

### Traits

**Legendary Resistance (4/Day, or 5/Day in Lair).** If the dragon fails a saving throw, it can choose to succeed instead.


---

### Actions

**Multiattack.** The dragon makes three Rend attacks.

**Rend.** m +12, reach 15 ft. *Hit:* 17 (2d10 + 6) Slashing damage plus 5 (1d10) Poison damage.

**Nightmare Breath (Recharge 5–6).** wis DC 20, each creature in a 90-foot Cone.  44 (8d10) Psychic damage, and the target has the Frightened condition until the end of the dragon's next turn.  Half damage only.


---

### Bonus Actions

**Shape-Shift.** The dragon shape-shifts into a Small or Medium Humanoid or a Small or Medium Beast, or it returns to its true form. Its game statistics, other than its size, are the same in each form. Any equipment it is wearing or carrying isn't transformed.


---

### Legendary Actions

### 

**Pounce.** The dragon moves up to half its Speed, and it makes one Rend attack.

**Spore Salvo.** con DC 20, one creature within 30 feet of the dragon that it can see.  16 (3d10) Poison damage, and the target has the Poisoned condition. It repeats the save at the end of each of its turns, ending the effect on itself on a success. After 1 minute, it succeeds automatically.  The dragon can't take this action again until the start of its next turn.


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