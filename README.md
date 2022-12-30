# PSO Kata
A kata based in the world of the Primetime Soap Operas fantasy football league.

## Objective
Learn and practice outside-in TDD by implementing some of the business rules that PSO must conform to.

## Phase 1
### Problem Description
PSO is a fantasy football league comprised of several franchises. Each franchise has a roster of active football players that it owns the rights to. Franchises may add new players, drop existing players, and trade players with other franchises.

In this phase, we'll start by creating notions of a league, a franchise, and a player and implement those add, drop, and trade actions. Specifically, we'll support the following features:

* Register a player with the league
* Add a player to a franchise
* Drop a player from a franchise
* Trade two players from one franchise to another
* Maintain a transaction history for the league in the order in which they occur

### Acceptance Criteria
Before any adds, drops, or trades have been made, printing the transaction history should result in:

```
No transactions.
```

After some adds, drops, and trades have been made, printing the transaction history should result in:

```
1. Charles adds Vince Young
2. Luke adds Willie Snead
3. Patrick adds Joe Burrow
4. Charles trades Vince Young to Patrick; Patrick trades Joe Burrow to Charles
5. Luke drops Willie Snead
```
