# Brazil Fixes
Should work with open beta 1.14.3

Adds a 5th Research Slot for all ideologies, fixed some bugs and tuned some focuses be more interesting for Brazil in the Trials of Allegiance DLC. <br>
Democratic Brazil is mostly finished. You can actually get most of South America in the United States of South America path. <br>
Non-Aligned is about a third finished. <br>
Communist & Fascist is barely touched. <br>

Has no changes to the AI and doesn't add any new focuses, meaning it should be compatible with anything compatible with vanilla. <br>

Feel free to do whatever you want with this code. It should probably be in the actual game. Feel free to hire me as well, and maybe give me a million dollars. <br>

## <ins> DEMOCRATIC BRAZIL 🗽 </ins> <br>
---
### **The International Crisis** (Focus) [Bugfix] <br>

```diff
+ Added can Send Volunteers Rule` <br>
+ Focus now takes 35 days instead of 70.` <br>
```

**Summary** : Democracies can't send volunteers making this previously useless. <br>

[h3][b]War Bonds[/b] (Focus) [Bugfix] [/h3]
Replaced all requirements with:
[list]
[*]War support > 0.50
[*]Stability > 0.50
[/list]
War Bonds (National Spirit)
[list]
[*]-Consumer Goods Factor from -15% to -10%.
[*]-War support factor removed = +20%
[*]+Weekly war support = 0.10%.
[*]+Weekly stability = 0.10%.
[/list]

[h1][u]GOOD NEIGHBOR POLICY PATH > DEMOCRATIC BRAZIL & NON-ALIGNED 'ESTADO NOVO' & NON ALIGNED MONARCHISM [/u][/h1]

[h3][b]American-Brazilian Technology Exchange[/b] (Focus) [Balance] [/h3]
[list]
[*] Adds 1 Extra Research Slot.
[*] Focus now takes 70 days instead of 35.
[/list]
Summary: I have genetically enhanced all Brazilians. You're welcome.

[h3][b]Latin American Research Council[/b] (Focus) [Balance] [/h3]
[list]
[*] Adds 1 Extra Research Slot.
[/list]
Summary: I have genetically enhanced all Brazilians. You're welcome.

[h3][b]Good Neighbor Policy[/b] (Focus) [Balance, Depth] [/h3]
Requirements:
[list]
[*]Now requires Brazil to not be engaged in any offensive wars with countries in North America, South America or the Caribbean.
[/list]

Now has three outcome for event.
[list]
[*]Option A will give a 30 Opinion Bonus & 100 Trade Influence for 48 months.
[*]Democratic Brazil: only Democratic nations will choose this.
[/list]
[list]
[*]Option B will give a 10 Opinion Bonus & 30 Trade Influence for 24 months.
[*]Democratic Brazil: only Communist & Non-Aligned nations will choose this.
[*]Non-Aligned Brazil: only Non-Aligned, Fascist & Democratic nations will choose this.
[/list]
[list]
[*]Option C. Gives nothing, the nation rejects Brazil. Status quo.
[*]Democratic Brazil: Fascist nations will choose this, making a deal with them impossible.
[*] Non-Aligned Brazil: Communist nations will choose this, making a deal with them impossible.
[/list]
Other Changes:
[list]
[*]Now event also sent to countries in North America.
[*]Opinion bonus is now mutual. Trade Influence added is also mutual.
[/list]
Summary: Reward is far greater with Trade Influence gain potential, particularly with the USA. Now has more depth by checking for ideologies. Actually requires you to be a good neighbour and not be elbow dropping your cousins.

[h3][b]The Washington Accords[/b] (Focus) [Balance, Depth] [/h3]
Requirements:
[list]
[*]Now requires the major that USA is at war with to not be Democratic or a nation that holds elections.
[*]Now requires USA to not be justifying on Brazil.
[*]Now requires USA to not have capitulated.
[*]Now requires USA must hold elections.
[*]Now requires USA to not be fascist.
[*]Now requires USA to not be justifying on Brazil.

[*]No longer requires USA to be Democratic
[*]No longer requires Brazil to not be in a faction.
[/list]
Other Changes:
[list]
[*]From 35 Days to 70.
[*]Now shows what happens if USA refuses deal in tooltip. Brazil will have -50 opinion of USA.
[*]Now any major country at war with the USA will get a -50 negative opinion of Brazil.
[*]Now Brazil and USA will get +100 Trade Influence with each other.
[*]Now any major country at war with the USA will get -100 Trade Influence with Brazil.
[/list]
[list]
The Washington Accords (National Spirit):
[*]-War support factor removed = +5%
[*]-Democracy drift removed = +0.01
[*]+Offensive War Stability Factor = +20%
[*]+Defensive War Stability Factor = +20%
[*]+Mobilization Speed = +0.30
[/list]
Summary: Now actually aligns you with the USA with greater reward (Trade Influence) and bonuses that will help you in a war, at the expensive of alienating yourself from USA's major enemies. Can now align with more than just Democratic USA; Communist USA and I think Non-Aligned can be aligned with, as long as they hold elections. 

[h3][b]No Fascism In South America[/b] (Focus) [Bugfix, Balance] [/h3]
[list]
[*] Added Additional Puppet Wargoals against all Non-Aligned countries in South America.
[*] No longer locked if the USA is fascist.
[*] Instead of specifically selecting some countries to not be included, now specifies that Strategic Region of 34 (Central America), 205 (Yucatan Peninsula) and 53 (Caribbean Sea) are not included. Meaning you get wargoals for countries only in South America. 
[/list]
Summary: Now as the United States of South America you can actually get all of South America. Previously Non-Aligned wouldn't join your faction and you couldn't invade them.

Also, before this you could get wargoals on countries in Central America and the Caribbean but not El Salvador,  Panama, Mexico or the Dominican Republic, leading to very weird and inconsistent wargoals.

[h3][b]No Communism In South America [/b](Focus) [Bugfix, Balance] [/h3]
[list]
[*]Focus now takes 35 days instead of 70.
[*]No longer locked if the USA is communist.
[*]Now specifies that Strategic Region of 34, 205 and 53 are not included. Meaning you get wargoals for countries only in South America.
[/list]

[h1][u]DOMINATION OF THE AMERICAS PATH > FASCIST BRAZIL & NON-ALIGNED 'ESTADO NOVO' & NON ALIGNED MONARCHISM [/u][/h1]
[h3][b]America De Sul[/b] (Focus) [Balance] [/h3]
[list]
[*] Adds 1 Extra Research Slot.
[/list]
Summary: I have genetically enhanced all Brazilians. You're welcome.

[h1][u]COMMUNIST BRAZIL[/u][/h1]
[h3][b]Establish ULASR [/b](Focus) [Balance][/h3]
[list]
[*] Adds 1 Extra Research Slot.
[/list]
Summary: I have genetically enhanced all Brazilians. You're welcome.


[h3][b]End South American Capitalism [/b](Focus) [Bugfix][/h3]
[list]
[*] Instead of specifically selecting some countries to not be included, now specifies that Strategic Region of 34, 205  and 53 are not included. Meaning you get wargoals for countries only in South America. 
[*] Focus can now be activated if a Non-Aligned nation is a viable target.
[/list]
Summary: Previously, this focus wouldn't be activatable if only Non-Aligned targets were available, as it only checked for Democracies.

Also, same problems as "No Fascism In South America" with El Salvador,  Panama, Mexico or the Dominican Republic.

[h3][b]Smash South American Fascism [/b] (Focus) [/h3]
[list]
[*] Instead of specifically selecting some countries to not be included, now specifies that Strategic Region of 34, 205 and 53 are not included. Meaning you only get wargoals for countries in South America.
[/list]
Same problems as "No Fascism In South America" with El Salvador,  Panama, Mexico or the Dominican Republic.
