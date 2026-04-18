---
type: pc
race: "Undead"
class:
 - "Flitterstep Eidolon"
subClass:
 - "CR 3"
cover: "Flitterstep Eidolon.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/medium
  - cr/3
  - source/mot
---
###### Flitterstep Eidolon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mythic Odysseys of Theros
___

> [!infobox|no-t right]
> ![[Flitterstep Eidolon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Medium Undead |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 14 |
> | :FasHeart: HP | 44 (8d8 + 8) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | Mythic Odysseys of Theros |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 8 | 18 | 13 | 11 | 12 | 10 |
| **Mod** | -1 | +4 | +1 | +0 | +1 | +0 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** passive Perception 13
**Languages:** the languages it knew in life
**Skills:** Perception +3, Stealth +8
**Damage Resistances:** necrotic; bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** poison
**Condition Immunities:** charmed; exhaustion; frightened; grappled; paralyzed; petrified; poisoned; restrained

---

### Traits

**Blurred Form.** Attack rolls against the eidolon are made with disadvantage unless the eidolon is incapacitated.

**Evasion.** If the eidolon is subjected to an effect that allows it to make a Dexterity saving throw to take only half damage, the eidolon instead takes no damage if it succeeds on the saving throw, and only half damage if it fails. It can't use this trait if it's incapacitated.

**Incorporeal Movement.** The eidolon can move through other creatures and objects as if they were 3. It takes 5 (1d10) force damage if it ends its turn inside an object.

**Turn Resistance.** The eidolon has advantage on saving throws against any effect that turns undead.


---

### Actions

**Multiattack.** The eidolon makes two melee attacks. Immediately before or after one of its attacks, it can use Flitterstep if it is available.

**Flickering Dagger.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 6 (1d4 + 4) piercing damage plus 3 (1d6) psychic damage.

**Flitterstep (Recharge 5–6).** The eidolon magically teleports to an unoccupied space it can see within 30 feet of it. If it makes an attack immediately after teleporting, it has advantage on the attack roll.


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