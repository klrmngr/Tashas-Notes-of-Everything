---
type: pc
race: "Dragon (metallic)"
class:
 - "Adult Silver Dragon"
subClass:
 - "CR 16"
cover: "Adult Silver Dragon.png"
campaign:
locations:
tags:
  - race/metallic
  - affinity/hostile
  - type/dragon
  - size/huge
  - cr/16
  - source/xmm
---
###### Adult Silver Dragon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Adult Silver Dragon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 16 (15,000 XP) |
> | :RiSwordFill: Type | Huge Dragon (metallic) |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Lawful Good |
> | :FasShield: AC | 19 |
> | :FasHeart: HP | 216 (16d12 + 112) |
> | :FasUserGroup: Race | Dragon (metallic) |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 27 | 10 | 25 | 16 | 13 | 22 |
| **Mod** | +8 | +0 | +7 | +3 | +1 | +6 |

**Speed:** 40 ft., fly 80 ft. &nbsp;|&nbsp; **Senses:** Blindsight 60 ft., Darkvision 120 ft., passive Perception 21
**Languages:** Common, Draconic
**Saving Throws:** Dex +5, Wis +6
**Skills:** History +8, Perception +11, Stealth +5
**Damage Immunities:** cold

---

### Traits

**Legendary Resistance (3/Day, or 4/Day in Lair).** If the dragon fails a saving throw, it can choose to succeed instead.


---

### Actions

**Multiattack.** The dragon makes three Rend attacks. It can replace one attack with a use of (A) Paralyzing Breath or (B) Spellcasting to cast Ice Knife.

**Rend.** m +13, reach 10 ft. *Hit:* 17 (2d8 + 8) Slashing damage plus 4 (1d8) Cold damage.

**Cold Breath (Recharge 5–6).** con DC 20, each creature in a 60-foot Cone.  54 (12d8) Cold damage.  Half damage.

**Paralyzing Breath.** con DC 20, each creature in a 60-foot Cone. 1 The target has the Incapacitated condition until the end of its next turn, when it repeats the save. 2 The target has the Paralyzed condition, and it repeats the save at the end of each of its turns, ending the effect on itself on a success. After 1 minute, it succeeds automatically.


---

### Legendary Actions

### 

**Chill.** The dragon uses Spellcasting to cast Hold Monster. The dragon can't take this action again until the start of its next turn.

**Cold Gale.** dex DC 19, each creature in a 60-foot-long, 10-foot-wide Line.  14 (4d6) Cold damage, and the target is pushed up to 30 feet straight away from the dragon.  Half damage only.  The dragon can't take this action again until the start of its next turn.

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