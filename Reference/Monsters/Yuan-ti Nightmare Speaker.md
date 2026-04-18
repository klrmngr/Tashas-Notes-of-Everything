---
type: pc
race: "Monstrosity (warlock)"
class:
 - "Yuan-ti Nightmare Speaker"
subClass:
 - "CR 4"
cover: "Yuan-ti Nightmare Speaker.png"
campaign:
locations:
tags:
  - race/warlock
  - affinity/hostile
  - type/monstrosity
  - size/medium
  - cr/4
  - source/mpmm
---
###### Yuan-ti Nightmare Speaker
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Yuan-ti Nightmare Speaker.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Medium Monstrosity (warlock) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 14 (natural armor) |
> | :FasHeart: HP | 71 (13d8 + 13) |
> | :FasUserGroup: Race | Monstrosity (warlock) |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 14 | 13 | 14 | 12 | 16 |
| **Mod** | +3 | +2 | +1 | +2 | +1 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 11
**Languages:** Abyssal, Common, Draconic
**Saving Throws:** Wis +3, Cha +5
**Skills:** Deception +5, Stealth +4
**Damage Immunities:** poison
**Condition Immunities:** poisoned

---

### Traits

**Devil's Sight.** Magical darkness doesn't impede the yuan-ti's darkvision.

**Magic Resistance.** The yuan-ti has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The yuan-ti makes one Constrict attack and one Scimitar attack, or it makes two Spectral Fangs attacks.

**Constrict.** Melee Weapon Attack: +5 to hit, reach 10 ft., one target. *Hit:* 10 (2d6 + 3) bludgeoning damage, and the target is grappled (escape DC 14) if it is a Large or smaller creature. Until this grapple ends, the target is restrained. The yuan-ti can constrict only one creature at a time.

**Scimitar (Yuan-ti Form Only).** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 6 (1d6 + 3) slashing damage.

**Spectral Fangs.** Ranged Spell Attack: +5 to hit, range 120 ft., one target. *Hit:* 16 (3d8 + 3) necrotic damage.

**Invoke Nightmare (Recharges after a Short or Long Rest).** The yuan-ti taps into the nightmares of one creature it can see within 60 feet of it and creates an illusory, immobile manifestation of the creature's deepest fears, visible only to that creature.
The target must make a DC 13 Intelligence saving throw. On a failed save, the target takes 22 (4d10) psychic damage and is frightened of the manifestation, believing it to be real. The yuan-ti must concentrate to maintain the illusion (as if concentrating on a spell), which lasts for up to 1 minute and can't be harmed. The target can repeat the saving throw at the end of each of its turns, ending the illusion on a success or taking 11 (2d10) psychic damage on a failure.


---

### Bonus Actions

**Change Shape.** The yuan-ti transforms into a Medium snake or back into its true form. Its statistics are the same in each form. Any equipment it is wearing or carrying isn't transformed. If it dies, it stays in its current form.


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