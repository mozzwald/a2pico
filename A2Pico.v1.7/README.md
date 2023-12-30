Version 1.7 is a direct successor of v1.4. Changes are replacing the 7408 by a 7411, data direction is controlled now by the Pico, which allows for all memory locations to be emulated, ENBL has an option to be is driven by a voltage divider for minimum latency, a USB "back power" option is included.

The RPI usage is as follows:

| GPIO    | Usage     |
|:--------|:----------|
| 0       |  UART TX  |
| 1       |  DATA dir |
| 2 - 13  | A0 - A11  |
| 14      | R/W       |
| 15 - 22 | D0 - D7   |
| 26      | ENBL      |
| 27      | IRQ       |
| 28      | RES       |

