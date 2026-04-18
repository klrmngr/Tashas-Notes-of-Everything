---
type: pc
race: "Undead"
class:
 - "Banshee"
subClass:
 - "CR 4"
cover: "Banshee.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/medium
  - cr/4
  - source/xmm
---
###### Banshee
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Banshee.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Medium Undead |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 54 (12d8) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 1 | 14 | 10 | 12 | 11 | 17 |
| **Mod** | -5 | +2 | +0 | +1 | +0 | +3 |

**Speed:** 5 ft., fly 40 ft. ((hover)) &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 10
**Languages:** Common, Elvish
**Saving Throws:** Wis +2
**Damage Resistances:** acid; bludgeoning; fire; lightning; piercing; slashing; thunder
**Damage Immunities:** cold; necrotic; poison
**Condition Immunities:** charmed; exhaustion; frightened; grappled; paralyzed; petrified; poisoned; prone; restrained

---

### Traits

**Detect Life.** The banshee magically senses the direction of creatures up to 1 mile away that aren't Constructs or Undead.

**Incorporeal Movement.** The banshee can move through other creatures and objects as if they were Difficult Terrain. It takes 5 (1d10) Force damage if it ends its turn inside an object.


---

### Actions

**Multiattack.** The banshee makes two Corrupting Touch attacks and uses Horrify.

**Corrupting Touch.** m +5, reach 5 ft. *Hit:* 7 (1d8 + 3) Necrotic damage.

**Horrify.** wis DC 13, one creature the banshee can see within 60 feet that can see the banshee.  The target has the Frightened condition until the start of the banshee's next turn.  The target is immune to this banshee's Horrify for 24 hours.

**Deathly Wail (1/Day).** The banshee releases a mournful wail if it isn't in sunlight. con DC 13, each creature within 30 feet that can hear the wail and isn't a Construct or an Undead.  If the target has 25 Hit Points or fewer, it drops to 0 Hit Points. Otherwise, the target takes 10 (3d6) Psychic damage.


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