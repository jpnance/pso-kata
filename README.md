# PSO Kata
A kata based in the world of the Primetime Soap Operas fantasy football league.

## Objective
Learn and practice outside-in TDD by implementing some of the business rules that PSO must conform to.

## Phase 1
### Problem Description
PSO is a fantasy football league comprised of a player pool and several franchises. Each franchise has a roster of active football players that it owns the rights to. Franchises may add new players from the player pool and drop players that they already own back into the player pool.

In this phase, we'll start by implementing those basic register/add/drop transactions:

* Register a player into the league's player pool
* Add a player from the league's player pool to a franchise
* Drop a player from a franchise back into the league's player pool
* Maintain a transaction history for the league, preserving the order in which each transaction occurs

### Acceptance Criteria
Before any adds or drops have been made, printing the transaction history should result in:

```
No transactions.
```

and printing the player pool should result in:

```
No players.
```

After some registers, adds, and drops have been made, printing the transaction history should result in:

```
1. Luke added Willie Snead
2. Charles added Vince Young
3. Patrick added Joe Burrow
4. Luke dropped Willie Snead
5. Luke added David Montgomery
6. Charles added Willie Snead
```

and printing the player pool should result in:

```
David Montgomery [Luke]
Joe Burrow [Patrick]
Kadarius Toney
Vince Young [Charles]
Willie Snead [Charles]
```
