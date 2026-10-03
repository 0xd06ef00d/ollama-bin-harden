# ollama-bin-harden
Fighting clankers with clankers

# What is this?
This is a WIP, exploratory project to explore using clankers to harden arbitrary binaries, at the binary level (no source code required).

The plan is to force other clankers to waste more tokens in 
- reverse engineering
- vulnerability discovery
- exploitation (of N-days or otherwise)

Ideally, an incremental increase of usage in defensive clanking tokens leads to an exponential increase in the adversary's clanking tokens.

# How do you (hopefully) intend to do this?
0. Clank.
1. Initially, reverse engineer whatever that's easy and conveniently doable.
2. Insert generated asm to patch, create fake (unexploitable) "vulns", and other redundant junk
3. Find appropriate points to chain the inserted code with the actual initial code
4. Apply other anti RE "tricks"
5. Repeat 1-4, in different order, until satisfied
6. Enjoy burning additional CPU cycles to achieve baseline functionality (but with **some** defensive armour)

# Great! When can I get some code in this repo?
When I'm satisfied with the outcome.
