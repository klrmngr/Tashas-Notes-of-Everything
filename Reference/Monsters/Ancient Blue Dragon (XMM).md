---
type: pc
race: "Dragon (chromatic)"
class:
 - "Ancient Blue Dragon"
subClass:
 - "CR 23"
cover: "Ancient Blue Dragon.png"
campaign:
locations:
tags:
  - race/chromatic
  - affinity/hostile
  - type/dragon
  - size/gargantuan
  - cr/23
  - source/xmm
---
###### Ancient Blue Dragon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Ancient Blue Dragon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 23 (50,000 XP) |
> | :RiSwordFill: Type | Gargantuan Dragon (chromatic) |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 22 |
> | :FasHeart: HP | 481 (26d20 + 208) |
> | :FasUserGroup: Race | Dragon (chromatic) |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 29 | 10 | 27 | 18 | 17 | 25 |
| **Mod** | +9 | +0 | +8 | +4 | +3 | +7 |

**Speed:** 40 ft., burrow 40 ft., fly 80 ft. &nbsp;|&nbsp; **Senses:** Blindsight 60 ft., Darkvision 120 ft., passive Perception 27
**Languages:** Common, Draconic
**Saving Throws:** Dex +7, Wis +10
**Skills:** Perception +17, Stealth +7
**Damage Immunities:** lightning

---

### Traits

**Legendary Resistance (4/Day, or 5/Day in Lair).** If the dragon fails a saving throw, it can choose to succeed instead.


---

### Actions

**Multiattack.** The dragon makes three Rend attacks. It can replace one attack with a use of Spellcasting to cast Shatter (level 3 version).

**Rend.** m +16, reach 15 ft. *Hit:* 18 (2d8 + 9) Slashing damage plus 11 (2d10) Lightning damage.

**Lightning Breath (Recharge 5–6).** dex DC 23, each creature in a 120-foot-long, 10-foot-wide Line.  88 (16d10) Lightning damage.  Half damage.


---

### Legendary Actions

### 

**Cloaked Flight.** The dragon uses Spellcasting to cast Invisibility on itself, and it can fly up to half its Fly Speed. The dragon can't take this action again until the start of its next turn.

**Sonic Boom.** The dragon uses Spellcasting to cast Shatter (level 3 version). The dragon can't take this action again until the start of its next turn.

**Tail Swipe.** The dragon makes one Rend attack.


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