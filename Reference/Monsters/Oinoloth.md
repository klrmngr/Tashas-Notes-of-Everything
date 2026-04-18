---
type: pc
race: "Fiend (yugoloth)"
class:
 - "Oinoloth"
subClass:
 - "CR 12"
cover: "Oinoloth.png"
campaign:
locations:
tags:
  - race/yugoloth
  - affinity/hostile
  - type/fiend
  - size/medium
  - cr/12
  - source/mpmm
---
###### Oinoloth
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Oinoloth.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 12 (8,400 XP) |
> | :RiSwordFill: Type | Medium Fiend (yugoloth) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 119 (14d8 + 56) |
> | :FasUserGroup: Race | Fiend (yugoloth) |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 17 | 18 | 17 | 16 | 19 |
| **Mod** | +4 | +3 | +4 | +3 | +3 | +4 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** blindsight 60 ft., darkvision 60 ft., passive Perception 17
**Languages:** Abyssal, Infernal, telepathy 60 ft.
**Saving Throws:** Con +8, Wis +7
**Skills:** Deception +8, Intimidation +8, Perception +7
**Damage Resistances:** cold; fire; lightning; bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** acid; poison
**Condition Immunities:** poisoned

---

### Traits

**Magic Resistance.** The oinoloth has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The oinoloth makes two Claw attacks, and it uses Spellcasting or Teleport.

**Claw.** Melee Weapon Attack: +8 to hit, reach 5 ft., one target. *Hit:* 14 (3d6 + 4) slashing damage plus 22 (4d10) necrotic damage.

**Corrupted Healing (Recharge 6).** The oinoloth touches one willing creature within 5 feet of it. The target regains all its hit points. In addition, the oinoloth can end one disease on the target or remove one of the following conditions from it: blinded, deafened, paralyzed, or poisoned. The target then gains 1 level of exhaustion, and its hit point maximum is reduced by 7 (2d6). This reduction can be removed only by a wish spell or by casting greater restoration on the target three times within the same hour. The target dies if its hit point maximum is reduced to 0.

**Teleport.** The oinoloth teleports, along with any equipment it is wearing or carrying, up to 60 feet to an unoccupied space it can see.


---

### Bonus Actions

**Bringer of Plagues (Recharge 5–6).** The oinoloth blights the area in a 30-foot-radius sphere centered on itself. The blight lasts for 24 hours. While the area is blighted, all normal plants there wither and die.
Furthermore, when a creature moves into the blighted area or starts its turn there, that creature must make a DC 16 Constitution saving throw. On a failed save, the creature takes 14 (4d6) poison damage and is poisoned. On a successful save, the creature is immune to the oinoloth's Bringer of Plagues for the next 24 hours.
The poisoned creature can't regain hit points. After every 24 hours that elapse, the poisoned creature can repeat the saving throw. On a failed save, the creature's hit point maximum is reduced by 5 (1d10). This reduction lasts until the poison ends, and the target dies if its hit point maximum is reduced to 0. The poison ends after the creature successfully saves against it three times.


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