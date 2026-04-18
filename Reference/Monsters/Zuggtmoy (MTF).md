---
type: pc
race: "Fiend (demon)"
class:
 - "Zuggtmoy"
subClass:
 - "CR 23"
cover: "Zuggtmoy.png"
campaign:
locations:
tags:
  - race/demon
  - affinity/hostile
  - type/fiend
  - size/large
  - cr/23
  - source/mtf
---
###### Zuggtmoy
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen's Tome of Foes
___

> [!infobox|no-t right]
> ![[Zuggtmoy.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 23 (50,000 XP) |
> | :RiSwordFill: Type | Large Fiend (demon) |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 18 (natural armor) |
> | :FasHeart: HP | 304 (32d10 + 128) |
> | :FasUserGroup: Race | Fiend (demon) |
> | :FasBook: Source | Mordenkainen's Tome of Foes |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 22 | 15 | 18 | 20 | 19 | 24 |
| **Mod** | +6 | +2 | +4 | +5 | +4 | +7 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** truesight 120 ft., passive Perception 21
**Languages:** all, telepathy 120 ft.
**Saving Throws:** Dex +9, Con +11, Wis +11
**Skills:** Perception +11
**Damage Resistances:** cold; fire; lightning
**Damage Immunities:** poison; bludgeoning, piercing, slashing that is nonmagical
**Condition Immunities:** charmed; exhaustion; frightened; poisoned

---

### Traits

**Legendary Resistance (3/Day).** If Zuggtmoy fails a saving throw, she can choose to succeed instead.

**Magic Resistance.** Zuggtmoy has advantage on saving throws against spells and other magical effects.

**Magic Weapons.** Zuggtmoy's weapon attacks are magical.


---

### Actions

**Multiattack.** Zuggtmoy makes three pseudopod attacks.

**Pseudopod.** Melee Weapon Attack: +13 to hit, reach 10 ft., one target. *Hit:* 15 (2d8 + 6) bludgeoning damage plus 9 (2d8) poison damage.

**Infestation Spores (3/Day).** Zuggtmoy releases spores that burst out in a cloud that fills a 20-foot-radius sphere centered on her, and it lingers for 1 minute. Any flesh-and-blood creature in the cloud when it appears, or that enters it later, must make a DC 19 Constitution saving throw. On a successful save, the creature can't be infected by these spores for 24 hours. On a failed save, the creature is infected with a disease called the spores of Zuggtmoy and also gains a random form of madness (determined by rolling on the Madness of Zuggtmoy table) that lasts until the creature is cured of the disease or dies. While infected in this way, the creature can't be reinfected, and it must repeat the saving throw at the end of every 24 hours, ending the infection on a success. On a failure, the infected creature's body is slowly taken over by fungal growth, and after three such failed saves, the creature dies and is reanimated as a spore servant if it's a type of creature that can be (see the "Myconids" entry in the Monster Manual).

**Mind Control Spores (Recharge 5–6).** Zuggtmoy releases spores that burst out in a cloud that fills a 20-foot-radius sphere centered on her, and it lingers for 1 minute. Humanoids and beasts in the cloud when it appears, or that enter it later, must make a DC 19 Wisdom saving throw. On a successful save, the creature can't be infected by these spores for 24 hours. On a failed save, the creature is infected with a disease called the influence of Zuggtmoy for 24 hours. While infected in this way, the creature is charmed by her and can't be reinfected by these spores.


---

### Reactions

**Protective Thrall.** When Zuggtmoy is hit by an attack, one creature within 5 feet of Zuggtmoy that is charmed by her must use its reaction to be hit by the attack instead.


---

### Legendary Actions

### 

**Attack.** Zuggtmoy makes one pseudopod attack.

**Exert Will.** One creature charmed by Zuggtmoy that she can see must use its reaction to move up to its speed as she directs or to make a weapon attack against a target that she designates.


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