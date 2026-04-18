---
type: pc
race: "Dragon (chromatic)"
class:
 - "Adult Red Dragon"
subClass:
 - "CR 17"
cover: "Adult Red Dragon.png"
campaign:
locations:
tags:
  - race/chromatic
  - affinity/hostile
  - type/dragon
  - size/huge
  - cr/17
  - source/xmm
---
###### Adult Red Dragon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Adult Red Dragon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 17 (18,000 XP) |
> | :RiSwordFill: Type | Huge Dragon (chromatic) |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 19 |
> | :FasHeart: HP | 256 (19d12 + 133) |
> | :FasUserGroup: Race | Dragon (chromatic) |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 27 | 10 | 25 | 16 | 13 | 23 |
| **Mod** | +8 | +0 | +7 | +3 | +1 | +6 |

**Speed:** 40 ft., climb 40 ft., fly 80 ft. &nbsp;|&nbsp; **Senses:** Blindsight 60 ft., Darkvision 120 ft., passive Perception 23
**Languages:** Common, Draconic
**Saving Throws:** Dex +6, Wis +7
**Skills:** Perception +13, Stealth +6
**Damage Immunities:** fire

---

### Traits

**Legendary Resistance (3/Day, or 4/Day in Lair).** If the dragon fails a saving throw, it can choose to succeed instead.


---

### Actions

**Multiattack.** The dragon makes three Rend attacks. It can replace one attack with a use of Spellcasting to cast Scorching Ray.

**Rend.** m +14, reach 10 ft. *Hit:* 13 (1d10 + 8) Slashing damage plus 5 (2d4) Fire damage.

**Fire Breath (Recharge 5–6).** dex DC 21, each creature in a 60-foot Cone.  59 (17d6) Fire damage.  Half damage.


---

### Legendary Actions

### 

**Commanding Presence.** The dragon uses Spellcasting to cast Command (level 2 version). The dragon can't take this action again until the start of its next turn.

**Fiery Rays.** The dragon uses Spellcasting to cast Scorching Ray. The dragon can't take this action again until the start of its next turn.

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