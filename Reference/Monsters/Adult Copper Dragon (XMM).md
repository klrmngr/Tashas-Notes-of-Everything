---
type: pc
race: "Dragon (metallic)"
class:
 - "Adult Copper Dragon"
subClass:
 - "CR 14"
cover: "Adult Copper Dragon.png"
campaign:
locations:
tags:
  - race/metallic
  - affinity/hostile
  - type/dragon
  - size/huge
  - cr/14
  - source/xmm
---
###### Adult Copper Dragon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Adult Copper Dragon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 14 (11,500 XP) |
> | :RiSwordFill: Type | Huge Dragon (metallic) |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Chaotic Good |
> | :FasShield: AC | 18 |
> | :FasHeart: HP | 184 (16d12 + 80) |
> | :FasUserGroup: Race | Dragon (metallic) |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 23 | 12 | 21 | 18 | 15 | 18 |
| **Mod** | +6 | +1 | +5 | +4 | +2 | +4 |

**Speed:** 40 ft., climb 40 ft., fly 80 ft. &nbsp;|&nbsp; **Senses:** Blindsight 60 ft., Darkvision 120 ft., passive Perception 22
**Languages:** Common, Draconic
**Saving Throws:** Dex +6, Wis +7
**Skills:** Deception +9, Perception +12, Stealth +6
**Damage Immunities:** acid

---

### Traits

**Legendary Resistance (3/Day, or 4/Day in Lair).** If the dragon fails a saving throw, it can choose to succeed instead.


---

### Actions

**Multiattack.** The dragon makes three Rend attacks. It can replace one attack with a use of (A) Slowing Breath or (B) Spellcasting to cast Mind Spike (level 4 version).

**Rend.** m +11, reach 10 ft. *Hit:* 17 (2d10 + 6) Slashing damage plus 4 (1d8) Acid damage.

**Acid Breath (Recharge 5–6).** dex DC 18, each creature in an 60-foot-long, 5-foot-wide Line.  54 (12d8) Acid damage.  Half damage.

**Slowing Breath.** con DC 18, each creature in a 60-foot Cone.  The target can't take Reactions; its Speed is halved; and it can take either an action or a Bonus Action on its turn, not both. This effect lasts until the end of its next turn.


---

### Legendary Actions

### 

**Giggling Magic.** cha DC 17, one creature the dragon can see within 90 feet.  24 (7d6) Psychic damage. Until the end of its next turn, the target rolls 1d6 whenever it makes an ability check or attack roll and subtracts the number rolled from the D20 Test.  The dragon can't take this action again until the start of its next turn.

**Mind Jolt.** The dragon uses Spellcasting to cast Mind Spike (level 4 version). The dragon can't take this action again until the start of its next turn.

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