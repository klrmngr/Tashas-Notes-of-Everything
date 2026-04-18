---
type: pc
race: "Dragon"
class:
 - "Shadow Dragon"
subClass:
 - "CR 13"
cover: "Shadow Dragon.png"
campaign:
locations:
tags:
  - race/dragon
  - affinity/hostile
  - type/dragon
  - size/huge
  - cr/13
  - source/xmm
---
###### Shadow Dragon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Shadow Dragon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 13 (10,000 XP) |
> | :RiSwordFill: Type | Huge Dragon |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 16 |
> | :FasHeart: HP | 189 (18d12 + 72) |
> | :FasUserGroup: Race | Dragon |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 21 | 19 | 18 | 14 | 12 | 18 |
| **Mod** | +5 | +4 | +4 | +2 | +1 | +4 |

**Speed:** 40 ft., climb 40 ft., fly 80 ft. &nbsp;|&nbsp; **Senses:** Blindsight 30 ft., Darkvision 120 ft., passive Perception 21
**Languages:** Common, Draconic
**Saving Throws:** Dex +9, Wis +6
**Skills:** Perception +11, Stealth +14
**Damage Immunities:** necrotic

---

### Traits

**Legendary Resistance (3/Day, or 4/Day in Lair).** If the dragon fails a saving throw, it can choose to succeed instead.

**Living Shadow.** While in Dim Light or Darkness, the dragon has Resistance to damage that isn't Force, Psychic, or Radiant.

**Sunlight Sensitivity.** While in sunlight, the dragon has Disadvantage on ability checks and attack rolls.


---

### Actions

**Multiattack.** The dragon makes three Rend attacks.

**Rend.** m +10, reach 10 ft. *Hit:* 12 (2d6 + 5) Slashing damage plus 3 (1d6) Necrotic damage.

**Shadow Breath (Recharge 5–6).** dex DC 17, each creature in a 60-foot Cone.  35 (10d6) Necrotic damage.  Half damage.  A Humanoid reduced to 0 Hit Points by this damage dies, and a [[Shadow]] rises from the corpse. The shadow is under the dragon's control and shares the dragon's Initiative count but acts immediately after the dragon.


---

### Bonus Actions

**Shadow Stealth.** While in Dim Light or Darkness, the dragon takes the Hide action.


---

### Legendary Actions

### 

**Pounce.** The dragon moves up to half its Speed, and it makes one Rend attack.

**Veil of Shadow.** The dragon uses Shadow Stealth, and one creature of its choice that it can see within 10 feet of it takes 10 (3d6) Necrotic damage. The dragon can't take this action again until the start of its next turn.


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