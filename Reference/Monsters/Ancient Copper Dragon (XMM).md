---
type: pc
race: "Dragon (metallic)"
class:
 - "Ancient Copper Dragon"
subClass:
 - "CR 21"
cover: "Ancient Copper Dragon.png"
campaign:
locations:
tags:
  - race/metallic
  - affinity/hostile
  - type/dragon
  - size/gargantuan
  - cr/21
  - source/xmm
---
###### Ancient Copper Dragon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Ancient Copper Dragon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 21 (33,000 XP) |
> | :RiSwordFill: Type | Gargantuan Dragon (metallic) |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Chaotic Good |
> | :FasShield: AC | 21 |
> | :FasHeart: HP | 367 (21d20 + 147) |
> | :FasUserGroup: Race | Dragon (metallic) |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 27 | 12 | 25 | 20 | 17 | 22 |
| **Mod** | +8 | +1 | +7 | +5 | +3 | +6 |

**Speed:** 40 ft., climb 40 ft., fly 80 ft. &nbsp;|&nbsp; **Senses:** Blindsight 60 ft., Darkvision 120 ft., passive Perception 27
**Languages:** Common, Draconic
**Saving Throws:** Dex +8, Wis +10
**Skills:** Deception +13, Perception +17, Stealth +8
**Damage Immunities:** acid

---

### Traits

**Legendary Resistance (4/Day, or 5/Day in Lair).** If the dragon fails a saving throw, it can choose to succeed instead.


---

### Actions

**Multiattack.** The dragon makes three Rend attacks. It can replace one attack with a use of (A) Slowing Breath or (B) Spellcasting to cast Mind Spike (level 5 version).

**Rend.** m +15, reach 15 ft. *Hit:* 19 (2d10 + 8) Slashing damage plus 9 (2d8) Acid damage.

**Acid Breath (Recharge 5–6).** dex DC 22, each creature in an 90-foot-long, 10-foot-wide Line.  63 (14d8) Acid damage.  Half damage.

**Slowing Breath.** con DC 22, each creature in a 90-foot Cone.  The target can't take Reactions; its Speed is halved; and it can take either an action or a Bonus Action on its turn, not both. This effect lasts until the end of its next turn.


---

### Legendary Actions

### 

**Giggling Magic.** cha DC 21, one creature the dragon can see within 120 feet.  31 (9d6) Psychic damage. Until the end of its next turn, the target rolls 1d8 whenever it makes an ability check or attack roll and subtracts the number rolled from the D20 Test.  The dragon can't take this action again until the start of its next turn.

**Mind Jolt.** The dragon uses Spellcasting to cast Mind Spike (level 5 version). The dragon can't take this action again until the start of its next turn.

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