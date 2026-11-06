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
- The map runs the full width of each boss card, with tanks and healers underneath. **◂** at the top of the roster folds it away for even more room (**Roster ▸** brings it back).
- **Steps** animate a fight. In the map editor, **+ Add step** (top of the map) adds a step: drag tokens to where they go next, and they glide there when you press **▶ Play**. Each step can have a caption, a move time and a pause. Anything you change or delete on a later step only affects that step and the ones after it; earlier steps stay as they were (deleting on **Start** removes it everywhere). Add something new on a later step and it appears there. **Move** and **Hold** in the Steps bar (− / +) set how long things glide into the step and how long ▶ Play stays on it. Raiders get **‹ ›** and **▶ Play** on every boss card (Space plays, `,` and `.` step).
- **Spell effects** (left panel of the editor) are animated: Fireball, Frostbolt, Shadow Bolt, Lightning, Charge and Beam fly from the start dot to the end dot; Fear, Explosion, Fire, Poison, Frost nova, Heal, Knockback, Whirlwind, Cleave, Stun, Shadow zone and Pulse play where you drop them. Drop a Whirlwind or Cleave on a boss or player and it **follows** them between steps (any area effect can follow something, under **Follow** in its settings); a Whirlwind can also **spin** the picture it follows. Aim a Cleave with its rotate dot. **Cast bar** is a resizable bar that fills over the cast time with the spell name; tick **Interrupted** to have it stop part way, flash red and say INTERRUPTED (optionally "Kicked by …"). Drop it on a boss and it sits above them. Cones and zones also have a **Pulse** option.
- **AQ40 maps**: all three Temple of Ahn'Qiraj floors are built in (Hive, Temple Gates, C'Thun's chamber), with a starter map for every AQ40 boss and room crops in **Map & crop…** and **+ Add page**.
- **Strategy maps** shows the whole board with every encounter.
- Map edits save into the raid plan and travel in the share link (images you upload onto a map stay in your browser).
- **Talking strats** (under each boss map) is what you say on the pull. They are **private**: kept only in the browser you write them in, never in share links or live plans, and hidden from view-only links. **Save to file** / **Load file** in the pop-out back them up or move them to another computer. **⤢ Pop out** opens a big editor: click a tag such as `{Main Tank}`, `{MT Healers}`, `{Raid Healers}` or `{Time Lapse Tank}` to insert it, and the name assigned to it fills in. Tags match a row on that boss card first, then a role on Tanks, healers & marks (short codes like `{MT}` and `{OT1}` work too), then a group (`{Tanks}`, `{MT Healers}`, `{Raid Healers}`, `{Healers}`). **+ Add** makes a new raid-wide role, and **Who's in this strat** lets you pick who fills each tag. `{skull}` and the other marks stay as raid icons. **Copy** gives the text with names filled in for raid chat or Discord.
- **Copy text** on a boss gives a one-paste summary for raid chat or Discord (`{skull}` shows as the icon in WoW chat).

## Saving and sharing

The page is static, so there is no shared server copy. Your plan saves in your own browser automatically.
To share it, press **Copy share link**: the whole plan is packed into the link, and anyone who opens it sees exactly that plan.
After more changes, copy a fresh link.

The planner lives in `index.html`; the map board is `board.html` (its built-in maps and starting layouts are embedded in that file).
