---
type: pc
race: "Dragon (chromatic)"
class:
 - "Ancient White Dragon"
subClass:
 - "CR 20"
cover: "Ancient White Dragon.png"
campaign:
locations:
tags:
  - race/chromatic
  - affinity/hostile
  - type/dragon
  - size/gargantuan
  - cr/20
  - source/xmm
---
###### Ancient White Dragon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Ancient White Dragon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 20 (25,000 XP) |
> | :RiSwordFill: Type | Gargantuan Dragon (chromatic) |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 20 |
> | :FasHeart: HP | 333 (18d20 + 144) |
> | :FasUserGroup: Race | Dragon (chromatic) |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 26 | 10 | 26 | 10 | 13 | 18 |
| **Mod** | +8 | +0 | +8 | +0 | +1 | +4 |

**Speed:** 40 ft., burrow 40 ft., fly 80 ft., swim 40 ft. &nbsp;|&nbsp; **Senses:** Blindsight 60 ft., Darkvision 120 ft., passive Perception 23
**Languages:** Common, Draconic
**Saving Throws:** Dex +6, Wis +7
**Skills:** Perception +13, Stealth +6
**Damage Immunities:** cold

---

### Traits

**Ice Walk.** The dragon can move across and climb icy surfaces without needing to make an ability check. Additionally, Difficult Terrain composed of ice or snow doesn't cost it extra movement.

**Legendary Resistance (4/Day, or 5/Day in Lair).** If the dragon fails a saving throw, it can choose to succeed instead.


---

### Actions

**Multiattack.** The dragon makes three Rend attacks.

**Rend.** m +14, reach 15 ft. *Hit:* 17 (2d8 + 8) Slashing damage plus 7 (2d6) Cold damage.

**Cold Breath (Recharge 5–6).** con DC 22, each creature in a 90-foot Cone.  63 (14d8) Cold damage.  Half damage.


---

### Legendary Actions

### 

**Freezing Burst.** con DC 20, each creature in a 30-foot-radius Sphere centered on a point the dragon can see within 120 feet.  14 (4d6) Cold damage, and the target's Speed is 0 until the end of the target's next turn.  The dragon can't take this action again until the start of its next turn.

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