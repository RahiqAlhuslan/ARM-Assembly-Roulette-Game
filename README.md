Interactive roulette game implemented in ARMv7 Assembly
Language on the DE1-SoC platform. The game simulates a spinning roulette wheel using ten LEDs that
illuminate sequentially. Players place bets by selecting one of ten switches (SW0-SW9) before gameplay
begins. The LED sequence cycles continuously until the player presses KEY0 to stop the wheel. The final
illuminated LED determines the game outcome—if it matches the player's chosen switch, "YES" displays
on the 7-segment displays; otherwise, "END" appears. The corresponding LED number (0-9) is shown on
the HEX3 display. This project demonstrates key embedded systems programming concepts including
memory-mapped I/O, bit-level operations, and direct hardware control.
