# Aminatou's Enchantment Discount
List of rules that should enable Aminatou, Veil Piercer to discount enchantment cards with {X} values. Taken from the Magic Judge Rules Resources website <https://blogs.magicjudges.org/rules/>. Items within "< >" are my own deductions. Irrelevant parts of some rulings were truncated and replaced by "[...]". Github formatting ended up broken for me, I do not know how to fix it, sorry.<br/>
<br/>
### Each enchantment card in your hand has miracle. Its miracle cost is equal to its mana cost reduced by {4}.
##### < This is a Static ability – written as a statement >
* 604.1 Static abilities do something all the time rather than being activated or triggered. They are written as statements, and they’re simply true.<br/>
<br/>

* 611.3 A continuous effect may be generated by the static ability of an object.<br/>
* 611.1 A continuous effect modifies characteristics of objects, modifies control of objects, or affects players or the rules of the game, for a fixed or indefinite period.<br/>
* 109.3 An object’s characteristics are name, mana cost, […] abilities, […].<br/>
##### < Aminatou's static ability provides a continuous effect ><br/>
<br/>

* 611.3a A continuous effect generated by a static ability isn’t “locked in”; it applies at any given moment to whatever its text indicates.<br/>
* 611.3b The effect applies at all times that the permanent generating it is on the battlefield or the object generating it is in the appropriate zone.<br/>
* 611.2d If a resolving spell or ability that creates a continuous effect contains a variable such as X, the value of that variable is determined only once, on resolution. See rule 608.2g.<br/>
##### < Via aminatou's ability, X is not locked in before the spell/miracle ability resolves, so it does NOT lock at hand ><br/>
<br/>

* 121.1 A player draws a card by putting the top card of their library into their hand. [...]<br/>
##### < Miracle is applied to the card in hand ><br/>
* 702.93a Miracle is a static ability linked to a triggered ability. (See rule 603.11). “Miracle [cost]” means “You may reveal this card from your hand as you draw it if it’s the first card you’ve drawn this turn. When you reveal this card this way, you may cast it by paying [cost] rather than its mana cost.”<br/>
* 118.9 Some spells have alternative costs. An alternative cost is a cost listed in a spell’s text, or applied to it from another effect, that its controller may pay rather than paying the spell’s mana cost. […] Note that some alternative costs are listed in keywords; see rule 702.<br/>
* 702.1b An effect that grants an object a keyword ability may define a variable in that ability, such as X or its “[keyword ability] cost,” based on characteristics of that object or other information about the game state. For these abilities, the value of that variable is constantly reevaluated.<br/>
##### < Relevant here is “[keyword ability] cost”. Mana cost is an object’s characteristic and thus, the miracle cost should be constantly reevaluated ><br/>
<br/>

* 118.9c An alternative cost doesn’t change a spell’s mana cost, only what its controller has to pay to cast it. Spells and abilities that ask for that spell’s mana cost still see the original value.<br/>
* 107.3a If a spell or activated ability has a mana cost, alternative cost, additional cost, and/or activation cost with an {X}, [-X], or X in it, and the value of X isn’t defined by the text of that spell or ability, the controller of that spell or ability chooses and announces the value of X as part of casting the spell or activating the ability. (See rule 601, “Casting Spells.”) While a spell is on the stack, any X in its mana cost or in any alternative cost or additional cost it has equals the announced value. While an activated ability is on the stack, any X in its activation cost equals the announced value.<br/>
##### < Aminatou will still look at the original mana cost to discount. All X instances will be whatever is announced ><br/>
###### < Interesting side ruling: ><br/>
* 202.3e When calculating the converted mana cost of an object with an {X} in its mana cost, X is treated as 0 while the object is not on the stack, and X is treated as the number chosen for it while the object is on the stack.<br/>
<br/>

* 601.2a To propose the casting of a spell, a player first moves that card (or that copy of a card) from where it is to the stack. It becomes the topmost object on the stack. It has all the characteristics of the card (or the copy of a card) associated with it, and that player becomes its controller. The spell remains on the stack until it’s countered, it resolves, or an effect moves it elsewhere.<br/>
##### < The card has changed zones and is not on the hand anymore ><br/>
* 400.7 An object that moves from one zone to another becomes a new object with no memory of, or relation to, its previous existence. There are eight exceptions to this rule:<br/>
* 400.7f If an effect grants a nonland card an ability that allows it to be cast, that ability will continue to apply to the new object that card became after it moved to the stack as a result of being cast this way.<br/>
##### < The enchantment card will remember it received miracle from Aminatou’s ability when it moves to the stack. The cost was never locked in, so the statement “its miracle cost is equal to its mana cost reduced by {4}” remains true ><br/>
<br/>

* 601.2b […] If the spell has alternative or additional costs that will be paid as it’s being cast […], the player announces their intentions to pay any or all of those costs (see rule 601.2f). […] If the spell has a variable cost that will be paid as it’s being cast (such as an {X} in its mana cost; see rule 107.3), the player announces the value of that variable. If the value of that variable is defined in the text of the spell by a choice that player would make later in the announcement or resolution of the spell, that player makes that choice at this time instead of that later time.<br/>
* 601.2f The player determines the total cost of the spell. Usually this is just the mana cost. Some spells have additional or alternative costs. Some effects may increase or reduce the cost to pay, or may provide other alternative costs […]. <br/>
##### < At this point Aminatou’s reduction should apply ><br/>
* 601.2f (continuation) The total cost is the mana cost or alternative cost (as determined in rule 601.2b), plus all additional costs and cost increases, and minus all cost reductions. If multiple cost reductions apply, the player may apply them in any order […].<br/>
##### < This is when regular cost reductions apply, such as that of Inquisitive Glimmer ><br/>
* 601.2f (continuation) Once the total cost is determined, any effects that directly affect the total cost are applied. Then the resulting total cost becomes “locked in.” If effects would change the total cost after this time, they have no effect.<br/>
##### < This is the point where the rules ever state the cost should be locked in ><br/>
