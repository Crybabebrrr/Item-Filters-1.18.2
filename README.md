## Item Filters is a library mod that is used by mods like FTB Quests, Modular Pipes and QNet. It adds a single item, "Item Filter" which allows advanced filtering/item selection. You can easily add your own filters with the API.

 

## If you want to use it in quests, cheat in any filter (or you can use existing one and sneak-right-click to change type) and right-click to edit it. Then in item task, select item from your inventory. Icon will be created automatically as scrolling list of valid items, but you have to change task title yourself.

 

## Currently available filters:

    NOT - Inverts child filter (not Apple)
    OR - Matches if any child filter matches (Apple or Carrot)
    AND - Matches if all children filters match (Diamond Sword and enchanted)
    XOR - Matches if either of filters A and B match, but not both ("dyeBlue" or "gemLapis" ore names but not both)
    Ore Dictionary Name - Matches if item has ore name ("ingotCopper")
    Creative Tab - Matches if item is in creative tab ("Building Blocks")
    Mod - Matches if item is from mod ("YABBA")

## NOT, OR, AND & XOR don't have GUIs currently.
