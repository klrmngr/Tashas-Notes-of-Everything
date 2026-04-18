---
type: pc
race: "Elemental"
class:
 - "Tlexolotl"
subClass:
 - "CR 10"
cover: "Tlexolotl.png"
campaign:
locations:
tags:
  - race/elemental
  - affinity/hostile
  - type/elemental
  - size/huge
  - cr/10
  - source/jttrc
---
###### Tlexolotl
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: JttRC
___

> [!infobox|no-t right]
> ![[Tlexolotl.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 10 (5,900 XP) |
> | :RiSwordFill: Type | Huge Elemental |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 104 (11d12 + 33) |
> | :FasUserGroup: Race | Elemental |
> | :FasBook: Source | JttRC |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 25 | 10 | 17 | 7 | 13 | 9 |
| **Mod** | +7 | +0 | +3 | -2 | +1 | -1 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., tremorsense 120 ft., passive Perception 11
**Languages:** Ignan
**Damage Immunities:** fire; poison
**Condition Immunities:** paralyzed; petrified; poisoned

---

### Traits

**Fire Aura.** At the start of each of the tlexolotl's turns, each creature within 10 feet of it takes 7 (2d6) fire damage, and flammable objects in that aura that aren't being worn or carried ignite. A creature that touches the tlexolotl or hits it with a melee attack while within 5 feet of it takes 7 (2d6) fire damage.

**Illumination.** The tlexolotl sheds bright light in a 30-foot radius and dim light for an additional 30 feet.

**Regeneration.** The tlexolotl regains 10 hit points at the start of its turn. If the tlexolotl takes cold damage or is immersed in water, this trait doesn't function at the start of the tlexolotl's next turn. The tlexolotl dies only if it starts its turn with 0 hit points and doesn't regenerate.


---

### Actions

**Multiattack.** The tlexolotl makes one Bite attack and one Tail attack.

**Bite.** Melee Weapon Attack: +11 to hit, reach 10 ft., one target. *Hit:* 12 (1d10 + 7) piercing damage plus 18 (4d8) fire damage.

**Tail.** Melee Weapon Attack: +11 to hit, reach 10 ft., one target. *Hit:* 11 (1d8 + 7) bludgeoning damage plus 14 (4d6) fire damage. If the target is a Large or smaller creature, it must succeed on a DC 19 Strength saving throw or be pushed up to 10 feet away from the tlexolotl and knocked prone.

**Pyroclasm (Recharge 5–6).** Gouts of molten lava erupt from the tlexolotl's body. Each creature in a 30-foot-radius sphere centered on the tlexolotl must make a DC 15 Dexterity saving throw. On a failed saving throw, a creature takes 21 (6d6) fire damage and 21 (6d6) bludgeoning damage. On a successful saving throw, a creature takes half as much damage.


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