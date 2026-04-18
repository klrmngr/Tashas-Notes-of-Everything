---
type: pc
race: "Humanoid (human)"
class:
 - "Arrant Quill"
subClass:
 - "CR 11"
cover: "Arrant Quill.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/11
  - source/cm
---
###### Arrant Quill
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Candlekeep Mysteries
___

> [!infobox|no-t right]
> ![[Arrant Quill.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 11 (7,200 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 14 |
> | :FasHeart: HP | 135 (18d8 + 54) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | Candlekeep Mysteries |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 18 | 16 | 16 | 15 | 20 |
| **Mod** | +0 | +4 | +3 | +3 | +2 | +5 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 12
**Languages:** Common, Draconic, Elvish, Undercommon
**Saving Throws:** Int +7, Wis +6, Cha +9
**Skills:** Arcana +11, Deception +9, History +7, Performance +13

---

### Actions

**Multiattack.** Quill makes two attacks with his dagger and uses Supreme Mockery.

**Dagger.** Melee or Ranged Weapon Attack: +8 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* 6 (1d4 + 4) piercing damage.

**Quill's Fable (Recharge 6).** Quill utters a short fable while targeting up to five creatures within 30 feet of him that he can see. Each target that can hear Quill's magical fable must make a DC 17 Wisdom saving throw, taking 36 (8d8) psychic damage on a failed save, or half as much damage on a successful one.

**Supreme Mockery.** Quill hurls a string of insults laced with enchantments at a creature he can see within 60 feet of him. If the creature can hear Quill (though it need not understand him), it must succeed on a DC 17 Wisdom saving throw or take 66 (12d10) psychic damage and have disadvantage on the next attack roll it makes before the end of its next turn.


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