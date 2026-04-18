---
type: pc
race: "Dragon (chromatic)"
class:
 - "Ancient Green Dragon"
subClass:
 - "CR 22"
cover: "Ancient Green Dragon.png"
campaign:
locations:
tags:
  - race/chromatic
  - affinity/hostile
  - type/dragon
  - size/gargantuan
  - cr/22
  - source/xmm
---
###### Ancient Green Dragon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Ancient Green Dragon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 22 (41,000 XP) |
> | :RiSwordFill: Type | Gargantuan Dragon (chromatic) |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 21 |
> | :FasHeart: HP | 402 (23d20 + 161) |
> | :FasUserGroup: Race | Dragon (chromatic) |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 27 | 12 | 25 | 20 | 17 | 22 |
| **Mod** | +8 | +1 | +7 | +5 | +3 | +6 |

**Speed:** 40 ft., fly 80 ft., swim 40 ft. &nbsp;|&nbsp; **Senses:** Blindsight 60 ft., Darkvision 120 ft., passive Perception 27
**Languages:** Common, Draconic
**Saving Throws:** Dex +8, Wis +10
**Skills:** Deception +13, Perception +17, Persuasion +13, Stealth +8
**Damage Immunities:** poison
**Condition Immunities:** poisoned

---

### Traits

**Amphibious.** The dragon can breathe air and water.

**Legendary Resistance (4/Day, or 5/Day in Lair).** If the dragon fails a saving throw, it can choose to succeed instead.


---

### Actions

**Multiattack.** The dragon makes three Rend attacks. It can replace one attack with a use of Spellcasting to cast Mind Spike (level 5 version).

**Rend.** m +15, reach 15 ft. *Hit:* 17 (2d8 + 8) Slashing damage plus 10 (3d6) Poison damage.

**Poison Breath (Recharge 5–6).** con DC 22, each creature in a 90-foot Cone.  77 (22d6) Poison damage.  Half damage.


---

### Legendary Actions

### 

**Mind Invasion.** The dragon uses Spellcasting to cast Mind Spike (level 5 version).

**Noxious Miasma.** con DC 21, each creature in a 30-foot-radius Sphere centered on a point the dragon can see within 90 feet.  17 (5d6) Poison damage, and the target takes a -2 penalty to AC until the end of its next turn.  The dragon can't take this action again until the start of its next turn.

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