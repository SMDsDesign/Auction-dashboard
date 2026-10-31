# User guide

How to run an auction with the APL 2026 platform, role by role.

- [Before the event (admin)](#before-the-event-admin)
- [On the night — auctioneer](#on-the-night--auctioneer)
- [On the night — team owners](#on-the-night--team-owners)
- [Viewers](#viewers)
- [Rules the system enforces](#rules-the-system-enforces)
- [Running another auction](#running-another-auction)
- [Resets and recovery](#resets-and-recovery)

---

## Before the event (admin)

1. **Players.** On the **Players** page, import a list from Excel/CSV or add players one by one.
   - Each card holds the band (I–IV), role and four skills (bat, bowl, field, knowledge).
   - It also holds a pitch line, the photo and the jersey name and number.
   - Drag cards to set the lot order. Mark injured players **Retired hurt** to keep them out of the pool.
2. **Teams.** On the **Teams** page, double-click to edit:
   - each team's name and colour
   - its logo
   - its captain, picked from the player list
   - the captain's jersey name and number

   Then click **💾 Save team setup** so later resets keep it.
3. **Start screen.** Click **✎ Edit text** on the start screen to set the title, date and button labels.
4. **Rules.** Edit the Auction and On-Ground Match rules in place on the **Rules** page.

## On the night — auctioneer

1. Put the auctioneer screen on the projector and click **▶ Start Auction**.
2. Each lot opens on a **player intro**. Bidding stays locked while you introduce the player.
3. Click **▶ Start BID**. Bids then arrive from owners' phones, or you click a team button for a bid called out in the room.
4. **Undo bid** steps back one bid at a time.
5. Click **🔨 SOLD**. A 5-second *Going… going…* ring gives the room a last chance; any new bid cancels it.
6. The **SOLD!** celebration shows on every screen. Close it to bring up the next player.
7. **No bids?** You have two options:
   - **✕ Unsold** moves on. Unsold players can be re-auctioned at the end.
   - **🎲 Roll dice** gives the player to a random captain among those with the fewest players who can legally take them, at the base price.
8. **⚖️ Tie** handles tied calls: raise the price one step first, and draw only if nobody takes it.
9. **👁 Owner view** shows any captain's screen exactly as they see it. It's a preview only and can't bid.

## On the night — team owners

1. Open the link on your phone, wait for the auctioneer to start, then tap **Let's Bid**.
2. Pick **your** team once. The phone remembers it.
3. Your screen shows the live lot, your **max bid**, your purse and band slots, and one big **Bid** button.
4. If someone outbids you first, you'll see *Bid not accepted — the price moved* and can simply tap again.

## Viewers

Viewers get two pages:
- **Teams:** all six squads on one screen. Tap a captain to see the full squad.
- **Rules:** the on-ground match rules.

## Rules the system enforces

| Rule | Detail |
|---|---|
| Purse | 100 points per team. Anything unspent is lost. |
| Base price | 2 points for every player |
| Increments | +1 to 10 · +2 to 20 · +3 to 30 · +5 to 50 (ceiling 50) |
| 50% rule | Max bid = half your remaining purse, with a floor of the base price, never more than you have |
| Squad size | Captain + 6 to 8 bought players (7–9 in total) |
| Band limits | I ≤ 1 · II ≤ 2 · III ≤ 3 · IV ≥ 3 (captains count in their own band) |
| Dice | Uniformly random among the eligible captains with the fewest players |

## Running another auction

- **＋ New auction** (admin, bottom bar) creates a fresh auction:
  - every player back in the pool
  - the same teams and captains, with empty squads and 100 points each
- The finished auction stays exactly as it was.
- **🏏 Auction switcher** (bottom bar, or the start-screen pills) chooses which auction **this screen** follows. Different screens can follow different auctions at the same time.

## Resets and recovery

- **↻ Reset ▾** offers four options:
  - **Bid:** clears the current lot's bids.
  - **Auction:** clears all sales and returns to Lot 1.
  - **Team:** restores the saved team setup.
  - **All:** resets everything.
- The destructive ones ask you to type `RESET`.
- **Sync safety:** a screen that missed updates (asleep, offline) never overwrites newer data. It reloads the latest state and asks you to repeat your last action.
