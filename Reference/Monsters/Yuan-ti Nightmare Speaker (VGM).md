---
type: pc
race: "Monstrosity (shapechanger, yuan-ti)"
class:
 - "Yuan-ti Nightmare Speaker"
subClass:
 - "CR 4"
cover: "Yuan-ti Nightmare Speaker.png"
campaign:
locations:
tags:
  - race/shapechanger
  - affinity/hostile
  - type/monstrosity
  - size/medium
  - cr/4
  - source/vgm
---
###### Yuan-ti Nightmare Speaker
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Volo's Guide to Monsters
___

> [!infobox|no-t right]
> ![[Yuan-ti Nightmare Speaker.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Medium Monstrosity (shapechanger, yuan-ti) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 14 (natural armor) |
> | :FasHeart: HP | 71 (13d8 + 13) |
> | :FasUserGroup: Race | Monstrosity (shapechanger, yuan-ti) |
> | :FasBook: Source | Volo's Guide to Monsters |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 14 | 13 | 14 | 12 | 16 |
| **Mod** | +3 | +2 | +1 | +2 | +1 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft. (penetrates magical darkness), passive Perception 11
**Languages:** Abyssal, Common, Draconic
**Saving Throws:** Wis +3, Cha +5
**Skills:** Deception +5, Stealth +4
**Damage Immunities:** poison
**Condition Immunities:** poisoned

---

### Traits

**Shapechanger.** The yuan-ti can use its action to polymorph into a Medium snake or back into its true form. Its statistics are the same in each form. Any equipment it is wearing or carrying isn't transformed. If it dies, it stays in its current form.

**Death Fangs (2/Day).** The first time the yuan-ti hits with a melee attack on its turn, it can deal an extra 16 (3d10) necrotic damage to the target.

**Magic Resistance.** The yuan-ti has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack (Yuan-ti Form Only).** The yuan-ti makes one constrict attack and one scimitar attack.

**Constrict.** Melee Weapon Attack: +5 to hit, reach 10 ft., one target. *Hit:* 10 (2d6 + 3) bludgeoning damage, and the target is grappled (escape DC 14) if it is a Large or smaller creature. Until this grapple ends, the target is restrained, and the yuan-ti can't constrict another target.

**Scimitar (Yuan-ti Form Only).** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 6 (1d6 + 3) slashing damage.

**Invoke Nightmare (Recharges after a Short or Long Rest).** The yuan-ti taps into the nightmares of a creature it can see within 60 feet of it and creates an illusory, immobile manifestation of the creature's deepest fears, visible only to that creature. The target must make a DC 13 Intelligence saving throw. On a failed save, the target takes 11 (2d10) psychic damage and is frightened of the manifestation, believing it to be real. The yuan-ti must concentrate to maintain the illusion (as if concentrating on a spell), which lasts for up to 1 minute and can't be harmed. The target can repeat the saving throw at the end of each of its turns, ending the illusion on a success, or taking 11 (2d10) psychic damage on a failure.


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