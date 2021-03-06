# YAMV

Yet Another Mü Variant WIP rules

## Preliminaries

**Players** 4, 5, or 6 in variable partnership

**Objective** Be the first to score 500 points

### Cards

4 suits. Aces are low as 1s.

There are two copies of every *odd* ranked card. For example, there are two ♠5
and a total of eight 5s across all suits, but there is only one ♠4 and a total
of four 4s across all suits.

- 4 players: ranks 1-8, 48 cards
- 5 players: ranks 1-10, 60 cards
- 6 players: ranks 1-12, 72 cards

### Trump

The trump suit is determined after the auction. Unlike in most traditional games
where trump is defined as a suit, eg spades, here trump is defined by a suit and
a rank. For example, if trump is defined as spades and 5s, then the trump suit
would look as follows in a 5-player game:

> (low) ♠1s, ♠2, ♠3s, ♠4, ♠6, ♠7s, ♠8, ♠9s, ♠10, [♦5s, ♥5s, ♣5s], ♠5s (high)

In this case, it contains 21 cards in total. The cards of the trump rank (5s)
are elevated above the suit (♠), and the cards that have both characteristics
(♠5s) are the highest. All of the non-spade 5s are treated as if they are the
same rank.

It is possible for the trump suit to be comprised of two ranks instead of a
rank and a suit.

For clarity, the following are examples from a 5-player game of every possible
permutation of the trump suit:

- Suit (♠) + odd rank (5)
  - ♠1s, ♠2, ♠3s, ♠4, ♠6, ♠7s, ♠8, ♠9s, ♠10, [♦5s, ♥5s, ♣5s], ♠5s
  - Total: 21 cards
- Suit (♠) + even rank (4)
  - ♠1s, ♠2, ♠3s, ♠5s, ♠6, ♠7s, ♠8, ♠9s, ♠10, [♦4, ♥4, ♣4], ♠4
  - Total: 18 cards
- Suit (♠) + no rank:
  - ♠1s, ♠2, ♠3s, ♠4, ♠5s, ♠6, ♠7s, ♠8, ♠9s, ♠10
  - Total: 15 cards
- No suit + odd rank (5):
  - [♦5s, ♥5s, ♠5s, ♣5s]
  - Total: 8 cards
- No suit + even rank (4):
  - [♦4, ♥4, ♠4, ♣4]
  - Total: 4 cards
- Odd rank (5) + odd rank (7):
  - [♦5s, ♥5s, ♠5s, ♣5s], [♦7s, ♥7s, ♠7s, ♣7s]
  - Total: 16 cards
- Odd rank (5) + even rank (4):
  - [♦4, ♥4, ♠4, ♣4], [♦5s, ♥5s, ♠5s, ♣5s]
  - Total: 12 cards
- Even rank (4) + even rank (6):
  - [♦4, ♥4, ♠4, ♣4], [♦6, ♥6, ♠6, ♣6]
  - Total: 8 cards

### Deal

12 cards to each player.

## Bidding

Starting with the forehand each player in turn order may place any number of
cards from their hand face up in front of them on the table to represent their
bid. The number of cards in front of them represents the number of tricks they
need to win with the help of a partner. One card is a bid to take **5 tricks**,
and each additional card increases the number of tricks they need to take by
one.

Players are not required to head the auction when they bid. For example, if the
forehand opens by bidding two cards, then the next player does not have to bid 3
and may choose to bid a single card. You cannot win the auction by underbidding,
but doing so is useful to signal a potential partnership.

A player who does not wish to bid may pass. Passing does not remove the player
from the auction, and they may choose to bid on a later turn. The auction
continues until every player has passed consecutively.

On subsequent turns, a player who has already bid may increase their bid by
adding additional cards from their hand to the table.

The suit and rank of the cards bid matters. The declarer and head defender may
only name a trump characteristic that is represented in a card that they bid.
For example, if they did not bid any hearts, then they cannot name hearts as the
trump suit. Or, if they did not bid any 5s, then they cannot name 5s as the
trump rank.

When the auction ends, the player who bid the most cards wins and becomes the
**declarer**. The player who bid the second most cards becomes the **head
defender**.

If there is a tie for the most cards bid, then the declarer is the tied player
who is closest to the **dealer** in turn order, meaning the forehand has highest
preference and the dealer has lowest preference.

If there is a tie for the second most cards bid, then the head defender is the
tied player who is closest to the **declarer** in *reverse* turn order. For
example, in a 5-player game, if the forehand is the declarer and the dealer is
tied with another player for second, then the dealer is the head defender
because they are the closest player on the declarer's right-hand side.

All of the cards that were bid remain face up on the table.

### Defining Trump

The declarer now must name one characteristic of the trump suit. They may either
name a suit, a rank, or no trump. Then, the head defender must name the other
characteristic. However, the head defender is not allowed to name a suit and may
only name a rank or no trump. The two characteristics are combined to form the
trump suit as described above.

### Picking a Partner

The declarer next names one of the other players as their partner. They may not
pick the head defender. The remaining players are on a team together as the
defense.

### Exchange

Finally, the declarer takes the talon into their hand, and then discards 2
cards. They may choose to discard cards on the table, but, if they do so, they
must replace the cards from the table with an equivalent number of cards that
they drew from the talon.

## Play

The **declarer** leads the first trick. Standard trick-taking rules apply.
Players may either play cards from their hand or from their face up cards on the
table. If multiple cards of the same rank tie to win a trick, then the card that
was played first wins.

## Scoring

The declarer's team wins the hand if the succeed in taking at least the number
of tricks that they bid, 4 plus the number of cards the declarer bid. Otherwise,
the defense wins.

If the declarer's team wins, then each partner receives 10 points per trick bid
plus 5 points for every overtrick. For example, if the declarer took the bid
with 4 cards, then they would need to take at least 8 tricks to win. If they end
up taking 9 tricks, then they would each score 80 points for the tricks bid plus
5 for the overtrick for a total of 85 points.

If they fail to take the necessary tricks, the declarer loses 10 points per
_trick bid_, and their partner loses 10 points per _undertrick_. Reusing the
previous example, if they instead only took 6 of the needed 8 tricks, then the
declarer loses 80 points and their partner loses 20.

Each defender always receives 5 points for each trick that they take
individually, not collectively, regardless of the outcome.

Finally, there is a flat bonus based on the trump characteristic selected by the
winning team.

Selection | Declarer | Defender 
--------- | -------- | --------
Suit      | 0        | NA
Odd rank  | 20       | 0
Even rank | 40       | 40
No trump  | 80       | 80

For example, if trump is spades and 5s, then neither team would get a bonus
regardless of the outcome. If instead trump is 5s (declarer's pick) and 6s (head
defender's pick), then the declarer's team would get a 20 point bonus if they
won, and the defenders would each get a 40 point bonus if they won.

## Game

First player to 500 wins, or 300 for a shorter game. If multiple players cross
the threshold at the same time, then the player with the highest score wins. If
there's a tie, they both win.

## Variants

### Ranked Suits

Normally, all suits apart from the suit that is named as trump are ranked the
same, this results in 6 cards with the same rank when an odd rank is picked as
trump. An alternative, to reduce the number of cards with the same rank, is to
rank the suits (low) ♣, ♦, ♥, ♠ (high). This ranking only applies to trump, and
does not affect non-trump cards. The following are a few examples:

- Suit (♦) + odd rank (5)
  - ♦1s, ♦2, ♦3s, ♦4, ♦6, ♦7s, ♦8, ♦9s, ♦10, ♣5s, ♥5s, ♠5s, ♦5s
  - Total: 21 cards
- Odd rank (5) + odd rank (7)
  - ♣5s, ♦5s, ♥5s, ♠5s, ♣7s, ♦7s, ♥7s, ♠7s
  - Total: 18 cards

## TODO

- Head defender may pick a suit (still not sure if I like the possibility of
  there only being 3 suits)
- Within the trump suit, duplicate cards are ranked by suit
- Change deck composition? Fewer duplicate ranks? 
