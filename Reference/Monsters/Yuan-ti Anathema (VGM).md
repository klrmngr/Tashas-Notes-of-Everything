---
type: pc
race: "Monstrosity (shapechanger, yuan-ti)"
class:
 - "Yuan-ti Anathema"
subClass:
 - "CR 12"
cover: "Yuan-ti Anathema.png"
campaign:
locations:
tags:
  - race/shapechanger
  - affinity/hostile
  - type/monstrosity
  - size/huge
  - cr/12
  - source/vgm
---
###### Yuan-ti Anathema
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Volo's Guide to Monsters
___

> [!infobox|no-t right]
> ![[Yuan-ti Anathema.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 12 (8,400 XP) |
> | :RiSwordFill: Type | Huge Monstrosity (shapechanger, yuan-ti) |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 189 (18d12 + 72) |
> | :FasUserGroup: Race | Monstrosity (shapechanger, yuan-ti) |
> | :FasBook: Source | Volo's Guide to Monsters |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 23 | 13 | 19 | 19 | 17 | 20 |
| **Mod** | +6 | +1 | +4 | +4 | +3 | +5 |

**Speed:** 40 ft., climb 30 ft., swim 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., blindsight 30 ft., passive Perception 17
**Languages:** Abyssal, Common, Draconic
**Skills:** Perception +7, Stealth +5
**Damage Resistances:** acid; fire; lightning
**Damage Immunities:** poison
**Condition Immunities:** poisoned

---

### Traits

**Magic Resistance.** The anathema has advantage on saving throws against spells and other magical effects.

**Ophidiophobia Aura.** Any creature of the anathema's choice, other than a snake or a yuan-ti, that starts its turn within 30 feet of the anathema and can see or hear it must succeed on a DC 17 Wisdom saving throw or become frightened of snakes and yuan-ti. A frightened target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. If a target's saving throw is successful or the effect ends for it, the target is immune to this aura for the next 24 hours.

**Shapechanger.** The anathema can use its action to polymorph into a Huge giant constrictor snake, or back into its true form. its statistics are the same in each form. Any equipment it is wearing or carrying isn't transformed.

**Six Heads.** The anathema has advantage on Wisdom (Perception) checks and on saving throws against being blinded. charmed, deafened, frightened, stunned, or knocked unconscious.


---

### Actions

**Multiattack (Anathema Form Only).** The anathema makes two claw attacks, one constrict attack, and one Flurry of Bites attack.

**Claw (Anathema Form Only).** Melee Weapon Attack: +10 to hit, reach 10 ft., one target. *Hit:* 13 (2d6 + 6) slashing damage.

**Constrict.** Melee Weapon Attack: +10 to hit, reach 15 ft., one Large or smaller creature. *Hit:* 16 (3d6 + 6) bludgeoning damage plus 7 (2d6) acid damage, and the target is grappled (escape DC 16). Until this grapple ends, the target is restrained and takes 16 (3d6 + 6) bludgeoning damage plus 7 (2d6) acid damage at the start of each of its turns, and the anathema can't constrict another target.

**Flurry of Bites.** Melee Weapon Attack: +10 to hit, reach 10 ft., one creature. *Hit:* 27 (6d6 + 6) piercing damage plus 14 (4d6) poison damage.


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