# Principles
HTSL's syntax was designed to be easy to translate into and from housing actions, giving users an easy way to have a high-level view of their functions while being able to see the interactions at the lowest level for housing creators.

## Parameters
When referring to parameters, what we usually mean is the settings for each action. An **Apply Inventory Layout** action has a setting for which layout it is applying, and thus the name for the layout is considered a parameter.

A lot of settings for actions can be described in one word _(or some combination of numbers and letters that doesn't contain any spaces)_, but you may often find that you need multiple words for a parameter, especially for actions like **Send a Chat Message**. Whenever you have a parameter that must include spaces, enclose it in quotations, indicating to the compiler that it is one setting.
For an example where you want to have a setting be a greeting, you would have ``Hello World!`` -> ``"Hello World!"``.

> The main exception to the space rule is placeholders. For example, if you want a parameter to be the placeholder ``%random.whole/0 10%``, you can leave it as just that!

Read more about the different parameter types [here](https://github.com/redstone-llc/HTSLReborn/wiki/List-of-Parameter-Types).

## Keywords
Parameters aren't all that useful if we don't have a way to indicate what they are for. Keywords are most commonly used to indicate that following parameters _(spaced out by spaces)_ belong to a new action. For example, a **Send a Chat Message** action has the keyword ``chat``.
> If you wanted to create a **Send a Chat Message** action that says ``Hello World!``, it would look like ``chat "Hello World!"``. You can substitute whatever text you want in place of ``Hello World`` to send different messages.

## Actions
Most housing actions, such as **Send a Chat Message** are **Single-Line Actions**, meaning the mod considers one line of text in the script's file and converts that to one ingame action. To create multiple **Single-Line Actions**, you can put them on sequential lines and they will be added ingame in the order you write them.

> Code to send several chat messages would look like this:
> ```
> chat "This message sends first!"
> chat "This message will send second!"
> chat "This is the last message sent!"
> ```

Some **Single-Line Actions** allow for multiple parameters, such as the **Enchant Held Item** action. It takes in one parameter for the enchantment to apply, and another parameter for what level to apply it at. If you wanted to give the player Sharpness 5 on their item, you would write ``enchant Sharpness 5``
> Note that since neither parameter contains a space, you can write them without quotes! If you wanted an enchantment with a space in their name (e.g. Bane of Arthropods), you would write ``enchant "Bane of Arthropods" 5``

Knowing an action's given keyword and parameter order usually comes with practice, but while you learn we have a [wiki page](https://github.com/redstone-llc/HTSLReborn/wiki/List-of-Keywords) on every action.
