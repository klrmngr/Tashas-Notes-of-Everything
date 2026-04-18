---
type: pc
race: "Plant"
class:
 - "Chamberlain of Zuggtmoy"
subClass:
 - "CR 2"
cover: "Chamberlain of Zuggtmoy.png"
campaign:
locations:
tags:
  - race/plant
  - affinity/hostile
  - type/plant
  - size/large
  - cr/2
  - source/oota
---
###### Chamberlain of Zuggtmoy
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Out of the Abyss
___

> [!infobox|no-t right]
> ![[Chamberlain of Zuggtmoy.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Large Plant |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 13 (natural armor) |
> | :FasHeart: HP | 45 (6d10 + 12) |
> | :FasUserGroup: Race | Plant |
> | :FasBook: Source | Out of the Abyss |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 17 | 7 | 14 | 11 | 8 | 12 |
| **Mod** | +3 | -2 | +2 | +0 | -1 | +1 |

**Speed:** 20 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 9
**Languages:** Abyssal, Undercommon
**Damage Resistances:** bludgeoning; piercing

---

### Traits

**Mushroom Portal.** The chamberlain counts as a mushroom for the Fungus Stride feature of the bridesmaid of Zuggtmoy.

**Poison Spores.** Whenever the chamberlain takes damage, it releases a cloud of spores. Creatures within 5 feet of the chamberlain when this happens must succeed on a DC 12 Constitution saving throw or be poisoned for 1 minute. A creature can repeat the saving throw at the end of each of its turns, ending the effect on a success.


---

### Actions

**Multiattack.** The chamberlain makes two slam attacks.

**Slam.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 10 (2d6 + 3) bludgeoning damage.

**Infestation Spores (1/Day).** The chamberlain releases spores that burst out in a cloud that fills a 10-foot-radius sphere centered on it, and the cloud lingers for 1 minute. Any flesh-and-blood creature in the cloud when it appears, or that enters it later, must make a DC 12 Constitution saving throw. On a successful save, the creature can't be infected by these spores for 24 hours. On a failed save, the creature is infected with a disease called the spores of Zuggtmoy and also gains a random form of indefinite madness (determined by rolling on the Madness of Zuggtmoy table in appendix D) that lasts until the creature is cured of the disease or dies. While infected in this way, the creature can't be reinfected, and it must be repeat the saving throw at the end of every 24 hours, ending the infection on a success. On a failure, the infected creature's body is slowly taken over by fungal growth, and after three such failed saves, the creature dies and is reanimated as a spore servant if it's a type of creature that can be (see the "Myconids" entry in the Monster Manual).


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