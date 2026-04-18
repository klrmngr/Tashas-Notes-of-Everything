---
type: pc
race: "Fiend (yugoloth)"
class:
 - "Baernaloth"
subClass:
 - "CR 17"
cover: "Baernaloth.png"
campaign:
locations:
tags:
  - race/yugoloth
  - affinity/hostile
  - type/fiend
  - size/large
  - cr/17
  - source/mpp
---
###### Baernaloth
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MPP
___

> [!infobox|no-t right]
> ![[Baernaloth.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 17 (18,000 XP) |
> | :RiSwordFill: Type | Large Fiend (yugoloth) |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 256 (27d10 + 108) |
> | :FasUserGroup: Race | Fiend (yugoloth) |
> | :FasBook: Source | MPP |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 14 | 18 | 22 | 16 | 21 |
| **Mod** | +4 | +2 | +4 | +6 | +3 | +5 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** truesight 120 ft., passive Perception 19
**Languages:** all, telepathy 120 ft.
**Saving Throws:** Con +10, Wis +9
**Skills:** Arcana +12, Insight +9, Perception +9
**Damage Resistances:** cold; fire; lightning; necrotic; psychic; bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** acid; poison
**Condition Immunities:** charmed; frightened; poisoned

---

### Traits

**Legendary Resistance (4/Day).** If the baernaloth fails a saving throw, it can choose to succeed instead.

**Magic Resistance.** The baernaloth has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The baernaloth makes one Anguishing Bite attack and one Claw attack. It can also use Teleport.

**Anguishing Bite.** Melee Weapon Attack: +10 to hit, reach 5 ft., one target. *Hit:* 9 (1d10 + 4) piercing damage plus 10 (3d6) psychic damage. If the target is a creature, it can't regain hit points until the start of the baernaloth's next turn.

**Claw.** Melee Weapon Attack: +10 to hit, reach 10 ft., one target. *Hit:* 11 (2d6 + 4) slashing damage plus 17 (5d6) necrotic damage.

**Miasma of Discord (Recharge 5–6).** The baernaloth exhales gray vapors that coalesce at a point it can see within 120 feet of itself. The vapors fill a 20-foot-radius sphere centered on that point, then vanish. Each non-yugoloth creature in that area must make a DC 19 Wisdom saving throw. On a failed save, the creature takes 35 (10d6) psychic damage and has the charmed condition until the end of its next turn. A creature charmed in this way treats its allies as foes, and the colors of its body and equipment become shades of gray. On a successful save, the creature takes half as much damage only.

**Summon Yugoloth (1/Day).** The baernaloth has a 50 percent chance of summoning its choice of 1d4 mezzoloths, 1 arcanaloth, or 1 baernaloth (the mezzoloth and arcanaloth appear in the Monster Manual). A summoned yugoloth appears in an unoccupied space within 60 feet of the baernaloth, acts as an ally of the baernaloth, and can't summon other yugoloths. It remains for 1 minute, until it or the baernaloth dies, or until the baernaloth dismisses it as an action.

**Teleport.** The baernaloth teleports, along with any equipment it is wearing or carrying, up to 120 feet to an unoccupied space it can see.


---

### Reactions

**Afflict Despair.** When a creature that the baernaloth can see within 60 feet of itself hits with an attack roll or succeeds on a saving throw, the baernaloth forces the creature to reroll the d20 and use the new result.

**Inescapable Pain.** When the baernaloth is damaged by another creature, that creature must make a DC 19 Constitution saving throw, taking 14 (4d6) necrotic damage on a failed save, or half as much damage on a successful one.


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