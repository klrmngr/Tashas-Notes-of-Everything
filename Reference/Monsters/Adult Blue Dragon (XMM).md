---
type: pc
race: "Dragon (chromatic)"
class:
 - "Adult Blue Dragon"
subClass:
 - "CR 16"
cover: "Adult Blue Dragon.png"
campaign:
locations:
tags:
  - race/chromatic
  - affinity/hostile
  - type/dragon
  - size/huge
  - cr/16
  - source/xmm
---
###### Adult Blue Dragon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Adult Blue Dragon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 16 (15,000 XP) |
> | :RiSwordFill: Type | Huge Dragon (chromatic) |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 19 |
> | :FasHeart: HP | 212 (17d12 + 102) |
> | :FasUserGroup: Race | Dragon (chromatic) |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 25 | 10 | 23 | 16 | 15 | 20 |
| **Mod** | +7 | +0 | +6 | +3 | +2 | +5 |

**Speed:** 40 ft., burrow 30 ft., fly 80 ft. &nbsp;|&nbsp; **Senses:** Blindsight 60 ft., Darkvision 120 ft., passive Perception 22
**Languages:** Common, Draconic
**Saving Throws:** Dex +5, Wis +7
**Skills:** Perception +12, Stealth +5
**Damage Immunities:** lightning

---

### Traits

**Legendary Resistance (3/Day, or 4/Day in Lair).** If the dragon fails a saving throw, it can choose to succeed instead.


---

### Actions

**Multiattack.** The dragon makes three Rend attacks. It can replace one attack with a use of Spellcasting to cast Shatter.

**Rend.** m +12, reach 10 ft. *Hit:* 16 (2d8 + 7) Slashing damage plus 5 (1d10) Lightning damage.

**Lightning Breath (Recharge 5–6).** dex DC 19, each creature in a 90-foot-long, 5-foot-wide Line.  60 (11d10) Lightning damage.  Half damage.


---

### Legendary Actions

### 

**Cloaked Flight.** The dragon uses Spellcasting to cast Invisibility on itself, and it can fly up to half its Fly Speed. The dragon can't take this action again until the start of its next turn.

**Sonic Boom.** The dragon uses Spellcasting to cast Shatter. The dragon can't take this action again until the start of its next turn.

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