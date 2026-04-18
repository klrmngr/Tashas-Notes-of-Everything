---
type: pc
race: "Ooze"
class:
 - "Black Pudding"
subClass:
 - "CR 4"
cover: "Black Pudding.png"
campaign:
locations:
tags:
  - race/ooze
  - affinity/hostile
  - type/ooze
  - size/large
  - cr/4
  - source/xmm
---
###### Black Pudding
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Black Pudding.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Large Ooze |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 7 |
> | :FasHeart: HP | 68 (8d10 + 24) |
> | :FasUserGroup: Race | Ooze |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 5 | 16 | 1 | 6 | 1 |
| **Mod** | +3 | -3 | +3 | -5 | -2 | -5 |

**Speed:** 20 ft., climb 20 ft. &nbsp;|&nbsp; **Senses:** Blindsight 60 ft., passive Perception 8
**Languages:** —
**Damage Immunities:** acid; cold; lightning; slashing
**Condition Immunities:** charmed; deafened; exhaustion; frightened; grappled; prone; restrained

---

### Traits

**Amorphous.** The pudding can move through a space as narrow as 1 inch without expending extra movement to do so.

**Corrosive Form.** A creature that hits the pudding with a melee attack roll takes 4 (1d8) Acid damage. Nonmagical ammunition is destroyed immediately after hitting the pudding and dealing any damage. Any nonmagical weapon takes a cumulative -1 penalty to attack rolls immediately after dealing damage to the pudding and coming into contact with it. The weapon is destroyed if the penalty reaches -5. The penalty can be removed by casting the Mending spell on the weapon.
In 1 minute, the pudding can eat through 2 feet of nonmagical wood or metal.

**Spider Climb.** The pudding can climb difficult surfaces, including along ceilings, without needing to make an ability check.


---

### Actions

**Dissolving Pseudopod.** m +5, reach 10 ft. *Hit:* 17 (4d6 + 3) Acid damage. Nonmagical armor worn by the target takes a -1 penalty to the AC it offers. The armor is destroyed if the penalty reduces its AC to 10. The penalty can be removed by casting the Mending spell on the armor.


---

### Reactions

**Split.**  While the pudding is Large or Medium and has 10+ Hit Points, it becomes Bloodied or is subjected to Lightning or Slashing damage.  The pudding splits into two new Black Puddings. Each new pudding is one size smaller than the original pudding and acts on its Initiative. The original pudding's Hit Points are divided evenly between the new puddings (round down).


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