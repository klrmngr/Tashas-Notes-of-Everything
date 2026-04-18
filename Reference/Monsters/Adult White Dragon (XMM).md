---
type: pc
race: "Dragon (chromatic)"
class:
 - "Adult White Dragon"
subClass:
 - "CR 13"
cover: "Adult White Dragon.png"
campaign:
locations:
tags:
  - race/chromatic
  - affinity/hostile
  - type/dragon
  - size/huge
  - cr/13
  - source/xmm
---
###### Adult White Dragon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Adult White Dragon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 13 (10,000 XP) |
> | :RiSwordFill: Type | Huge Dragon (chromatic) |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 18 |
> | :FasHeart: HP | 200 (16d12 + 96) |
> | :FasUserGroup: Race | Dragon (chromatic) |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 22 | 10 | 22 | 8 | 12 | 12 |
| **Mod** | +6 | +0 | +6 | -1 | +1 | +1 |

**Speed:** 40 ft., burrow 30 ft., fly 80 ft., swim 40 ft. &nbsp;|&nbsp; **Senses:** Blindsight 60 ft., Darkvision 120 ft., passive Perception 21
**Languages:** Common, Draconic
**Saving Throws:** Dex +5, Wis +6
**Skills:** Perception +11, Stealth +5
**Damage Immunities:** cold

---

### Traits

**Ice Walk.** The dragon can move across and climb icy surfaces without needing to make an ability check. Additionally, Difficult Terrain composed of ice or snow doesn't cost it extra movement.

**Legendary Resistance (3/Day, or 4/Day in Lair).** If the dragon fails a saving throw, it can choose to succeed instead.


---

### Actions

**Multiattack.** The dragon makes three Rend attacks.

**Rend.** m +11, reach 10 ft. *Hit:* 13 (2d6 + 6) Slashing damage plus 4 (1d8) Cold damage.

**Cold Breath (Recharge 5–6).** con DC 19, each creature in a 60-foot Cone.  54 (12d8) Cold damage.  Half damage.


---

### Legendary Actions

### 

**Freezing Burst.** con DC 14, each creature in a 30-foot-radius Sphere centered on a point the dragon can see within 120 feet.  7 (2d6) Cold damage, and the target's Speed is 0 until the end of the target's next turn.  The dragon can't take this action again until the start of its next turn.

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