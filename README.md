# Ashen Raid Planner

Drag-and-drop raid assignments for Blackwing Lair and AQ40: tanks, healers, raid marks, boss jobs and raid groups.

**Live page:** https://tracer96.github.io/ashen-raid-planner/

## How to use it

- Drag a name from the roster onto any slot. On a phone, tap a name, then tap a slot.
- Drag a name back onto the roster to clear a slot, or use the ×.
- Drag between two slots on the same boss (or two group slots) to swap them.
- **Tanks, healers & marks** fills every boss by default. A dotted border means the slot is using that default; ↺ puts it back.
- **Add member** (top of the roster panel) adds a player with a class and role.
- **Roster & bosses** edits class, role and status, marks who is out this week, and picks which bosses each player is in for. Anyone sitting out a boss shows crossed out on that boss.
- Click any job name or section heading on a boss to rename it. **+ Add row** adds a job, and − removes one (**Restore rows** brings the built-in ones back).
- **Edit** under a boss's strategy rewrites it (one point per line). ↑ and ↓ on a boss move it in the kill order.
- **Buffs** assigns Fortitude, Spirit, Intellect, Mark of the Wild, blessings, auras, totems, soulstones, innervates and world buffs.
- Drag the ⠿ handle on a boss row to reorder rows in that section.
- Drag tabs to reorder them. Right-click a tab (long-press on a phone) to move or hide it; ⋯ at the end of the tabs brings hidden ones back.
- **Pull marks** (on Tanks, healers & marks) sets a tank, a puller and a CC (sheep, trap, hibernate…) for each mark.
- **Player** shows everything one person is assigned. Double-click a name to open it, and "Copy link" sends them a link straight to their page.
- Every boss card has its **strategy map** (the Ashen Banner board). Drag to pan, Ctrl + scroll to zoom, and use the arrows for phases. **✎ Edit map** opens the full map editor; **Done** brings you back. Bosses without a map get a **+ Build a map** button.
- **Strategy maps** shows the whole board with every encounter.
- Map edits save into the raid plan and travel in the share link (images you upload onto a map stay in your browser).
- **Copy text** on a boss gives a one-paste summary for raid chat or Discord (`{skull}` shows as the icon in WoW chat).

## Saving and sharing

The page is static, so there is no shared server copy. Your plan saves in your own browser automatically.
To share it, press **Copy share link**: the whole plan is packed into the link, and anyone who opens it sees exactly that plan.
After more changes, copy a fresh link.

The planner lives in `index.html`; the map board is `board.html` (its built-in maps and starting layouts are embedded in that file).
