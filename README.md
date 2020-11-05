microkorg midi codez

program select
- 192, N (0 -> 127)
- 8 on the wheel, 8 numbers, 2 sides (a and b) == 8*8*2

arpeggiator
- turn on:
  - 176, 99, 0
  - 176, 98, 2
  - 176, 6, 127
- turn off:
  - 176, 99, 0
  - 176, 98, 2
  - 176, 6, 0

timbre select
- 1
  - 176, 95, 0
- 2
  - 176, 95, 127

knobs
- not-vocoder
  - ES1: filter, ES2: filter
    - 1/cutoff
      - 176, 74, N (0 -> 127)
    - 2/resonance
      - 176, 71, N (0 -> 125)
    - 3/eg attack
      - 176, 23, N (0 -> 127)
      - 176, 73, N (0 -> 127)
    - 4/eg release
      - 176, 26, N (0 -> 127)
      - 176, 72, N (0 -> 127)
    - 5/tempo
      - noop

