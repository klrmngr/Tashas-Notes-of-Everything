---
type: pc
race: "Dragon (chromatic)"
class:
 - "Ancient Red Dragon"
subClass:
 - "CR 24"
cover: "Ancient Red Dragon.png"
campaign:
locations:
tags:
  - race/chromatic
  - affinity/hostile
  - type/dragon
  - size/gargantuan
  - cr/24
  - source/xmm
---
###### Ancient Red Dragon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Ancient Red Dragon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 24 (62,000 XP) |
> | :RiSwordFill: Type | Gargantuan Dragon (chromatic) |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 22 |
> | :FasHeart: HP | 507 (26d20 + 234) |
> | :FasUserGroup: Race | Dragon (chromatic) |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 30 | 10 | 29 | 18 | 15 | 27 |
| **Mod** | +10 | +0 | +9 | +4 | +2 | +8 |

**Speed:** 40 ft., climb 40 ft., fly 80 ft. &nbsp;|&nbsp; **Senses:** Blindsight 60 ft., Darkvision 120 ft., passive Perception 26
**Languages:** Common, Draconic
**Saving Throws:** Dex +7, Wis +9
**Skills:** Perception +16, Stealth +7
**Damage Immunities:** fire

---

### Traits

**Legendary Resistance (4/Day, or 5/Day in Lair).** If the dragon fails a saving throw, it can choose to succeed instead.


---

### Actions

**Multiattack.** The dragon makes three Rend attacks. It can replace one attack with a use of Spellcasting to cast Scorching Ray (level 3 version).

**Rend.** m +17, reach 15 ft. *Hit:* 19 (2d8 + 10) Slashing damage plus 10 (3d6) Fire damage.

**Fire Breath (Recharge 5–6).** dex DC 24, each creature in a 90-foot Cone.  91 (26d6) Fire damage.  Half damage.


---

### Legendary Actions

### 

**Commanding Presence.** The dragon uses Spellcasting to cast Command (level 2 version). The dragon can't take this action again until the start of its next turn.

**Fiery Rays.** The dragon uses Spellcasting to cast Scorching Ray (level 3 version). The dragon can't take this action again until the start of its next turn.

**Pounce.** The dragon moves up to half its Speed, and it makes one Rend attack.


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