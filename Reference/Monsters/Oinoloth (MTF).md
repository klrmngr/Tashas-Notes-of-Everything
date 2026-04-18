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
  - source/mtf
---
###### Oinoloth
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen's Tome of Foes
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
> | :FasHeart: HP | 126 (12d10 + 60) |
> | :FasUserGroup: Race | Fiend (yugoloth) |
> | :FasBook: Source | Mordenkainen's Tome of Foes |

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

**Bringer of Plagues (Recharge 5–6).** As a bonus action, the oinoloth blights the area within 30 feet of it. The blight lasts for 24 hours. While blighted, all normal plants in the area wither and die, and the number of hit points restored by a spell to a creature in that area is halved.
Furthermore, when a creature moves into the blighted area or starts its turn there, that creature must make a DC 16 Constitution saving throw. On a successful save, the creature is immune to the oinoloth's Bringer of Plagues for the next 24 hours. On a failed save, the creature takes 14 (4d6) necrotic damage and is poisoned.
The poisoned creature can't regain hit points. After every 24 hours that elapse, the poisoned creature can repeat the saving throw. On a failed save, the creature's hit point maximum is reduced by 5 (1d10). This reduction lasts until the poison ends, and the target dies if its hit point maximum is reduced to 0. The poison ends after the creature successfully saves against it three times.

**Magic Resistance.** The oinoloth has advantage on saving throws against spells and other magical effects.

**Magic Weapons.** The oinoloth's weapon attacks are magical.


---

### Actions

**Multiattack.** The oinoloth uses its Transfixing Gaze and makes two claw attacks.

**Claw.** Melee Weapon Attack: +8 to hit, reach 5 ft., one target. *Hit:* 14 (3d6 + 4) slashing damage plus 22 (4d10) necrotic damage.

**Corrupted Healing (Recharge 6).** The oinoloth touches one willing creature within 5 feet of it. The target regains all its hit points. In addition, the oinoloth can end one disease on the target or remove one of the following conditions from it: blinded, deafened, paralyzed, or poisoned. The target then gains 1 level of exhaustion, and its hit point maximum is reduced by 7 (2d6). This reduction can be removed only by a wish spell or by casting greater restoration on the target three times within the same hour. The target dies if its hit point maximum is reduced to 0.

**Teleport.** The oinoloth magically teleports, along with any equipment it is wearing or carrying, up to 60 feet to an unoccupied space it can see.

**Transfixing Gaze.** The oinoloth targets one creature it can see within 30 feet of it. The target must succeed on a DC 16 Wisdom saving throw against this magic or be charmed until the end of the oinoloth's next turn. While charmed in this way, the target is restrained. If the target's saving throw is successful, the target is immune to the oinoloth's gaze for the next 24 hours.


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