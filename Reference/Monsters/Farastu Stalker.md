---
type: pc
race: "Fiend"
class:
 - "Farastu Stalker"
subClass:
 - "CR 7"
cover: "Farastu Stalker.png"
campaign:
locations:
tags:
  - race/fiend
  - affinity/hostile
  - type/fiend
  - size/medium
  - cr/7
  - source/mabjov
---
###### Farastu Stalker
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MaBJoV
___

> [!infobox|no-t right]
> ![[Farastu Stalker.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 7 (2,900 XP) |
> | :RiSwordFill: Type | Medium Fiend |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 71 (11d8 + 22) |
> | :FasUserGroup: Race | Fiend |
> | :FasBook: Source | MaBJoV |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 13 | 14 | 8 | 12 | 16 |
| **Mod** | +4 | +1 | +2 | -1 | +1 | +3 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 11
**Languages:** Abyssal
**Saving Throws:** Str +7, Con +5
**Skills:** Athletics +7
**Damage Resistances:** cold; fire; bludgeoning, piercing, slashing from nonmagical attacks that aren't silvered
**Damage Immunities:** acid; poison
**Condition Immunities:** poisoned

---

### Traits

**Adhesive Slime.** The farastu secretes a thick, tar-like slime and it can choose to use this slime to secure enemies that it has grappled or to make weapons become attached to it. It is able to end the adhesion with a bonus action, causing all items and creatures secured to it to be released. The adhesion also ends after the farastu dies.

**Devil's Sight.** Magical darkness doesn't impede the farastu's darkvision.

**Keen Smell.** The farastu has advantage on Wisdom (Perception) checks that rely on smell.

**Magic Resistance.** The farastu has advantage on saving throws against spells and other magical effects.

**Magic Weapons.** The farastu's weapon attacks are magical.

**Reckless.** At the start of its turn, the farastu can gain advantage on all melee weapon attack rolls it makes during that turn, but attack rolls against it have advantage until the start of its next turn.


---

### Actions

**Multiattack.** The farastu makes one Bite attack and two Claws attacks.

**Bite.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 11 (2d6 + 4) piercing damage.

**Claws.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 7 (1d6 + 4) slashing damage. The target is held fast by the farastu's adhesive slime (grappled condition, escape DC 15) if the farastu isn't already grappling a creature.


---

### Reactions

**Adhesive Hide.** After taking damage from a melee weapon, the farastu uses its reaction to attach the weapon to its hide. The attacker must make a DC 15 Dexterity saving throw. On a failure, the weapon becomes attached to the farastu's adhesive hide until the farastu dies or releases the weapon. A creature can also use an action to make a DC 15 Strength check, prying the weapon free from the farastu, if successful.


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