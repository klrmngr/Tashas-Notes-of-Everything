---
type: pc
race: "Dragon"
class:
 - "Juvenile Shadow Dragon"
subClass:
 - "CR 4"
cover: "Juvenile Shadow Dragon.png"
campaign:
locations:
tags:
  - race/dragon
  - affinity/hostile
  - type/dragon
  - size/medium
  - cr/4
  - source/xmm
---
###### Juvenile Shadow Dragon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Juvenile Shadow Dragon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Medium Dragon |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 15 |
> | :FasHeart: HP | 45 (6d8 + 18) |
> | :FasUserGroup: Race | Dragon |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 17 | 14 | 17 | 12 | 11 | 15 |
| **Mod** | +3 | +2 | +3 | +1 | +0 | +2 |

**Speed:** 30 ft., climb 30 ft., fly 60 ft. &nbsp;|&nbsp; **Senses:** Blindsight 10 ft., Darkvision 60 ft., passive Perception 14
**Languages:** Common, Draconic
**Saving Throws:** Dex +4
**Skills:** Perception +4, Stealth +6
**Damage Immunities:** necrotic

---

### Traits

**Living Shadow.** While in Dim Light or Darkness, the dragon has Resistance to damage that isn't Force, Psychic, or Radiant.

**Sunlight Sensitivity.** While in sunlight, the dragon has Disadvantage on ability checks and attack rolls.


---

### Actions

**Multiattack.** The dragon makes two Rend attacks.

**Rend.** m +5, reach 10 ft. *Hit:* 7 (1d8 + 3) Slashing damage plus 3 (1d6) Necrotic damage.

**Shadow Breath (Recharge 5–6).** dex DC 13, each creature in a 30-foot Cone.  17 (5d6) Necrotic damage.  Half damage.  A Humanoid reduced to 0 Hit Points by this damage dies, and a [[Shadow]] rises from its corpse. The shadow is under the dragon's control and shares the dragon's Initiative count but acts immediately after the dragon.


---

### Bonus Actions

**Shadow Stealth.** While in Dim Light or Darkness, the dragon takes the Hide action.


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