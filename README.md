# Tiny chess engine

A from-scratch chess engine in 4,096 bytes of Python: 0x88 board,
negamax alpha-beta with iterative deepening to a fixed 18,000-node
budget per move, quiescence over captures/promotions/check replies,
transposition table, killer moves and MVV-LVA ordering. Evaluation is
material plus piece-square tables and a bishop-pair bonus. No clock,
no randomness: every move is deterministic and replay-safe.

`main.py` is the `makefun compress` packing of the readable source;
the source travels with the entry's transcripts.
