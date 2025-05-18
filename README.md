# Library of soviet logic symblos (mostly for retrocomputers)

Made by Software & Computer Museum in Ukraine<br />
Symbols and footrprints library.

# Footprints. Pitch 2.50 mm

<pre><code>
201.14-8.kicad_mod   - DIP-14
201.16.5.kicad_mod   - DIP-16
2140.20-1.kicad_mod  - DIP-20
239.24-2.kicad_mod   - DIP-24 Wide
2121.28-4.kicad_mod  - DIP-28 Wide
2123.40-6.kicad_mod  - DIP-40 Wide 
429.42-5.kicad_mod   - 42 PIN footprint for KR1801VP1
</code></pre>

# Symbols.

## Digital logic

Lib: USSR_logic.kicad_sym

<pre><code>
АГ3   | 74123  - Dual retriggerable monostable multivibrators
АП2   | DP8226 - 4-bit Bidirectional Bus Transceiver
АП6   | 74245  - Octal bus transceiver
ИД4   | 74155  - Dual 2-to-4 line decoder/demultiplexer, inverting outputs
ИД7   | 74138  - 1-of-8 Decoder/Demultiplexer
ИЕ7   | 74193  - Synchronous presettable up/down 4-bit binary counter
ИE10  | 74161  - Synchronous 4-bit counter
ИЕ17  | 74169  - Synchronous presettable 4-bit up/down binary counter
ИР16  | 74295  - 4-Bit right-shift left-shift registers with 3-state outputs
ИР22  | 74373  - Octal D-Type Transparent Latches And Edge-Triggered Flip-Flops
КП11  | 74257  - Quad 2-line to 1-line data selector/multiplexer, non-inverting outputs
КП12  | 74253  - Dual 4-input multiplexer 3-state
КП14  | 74258  - Quad 2-line to 1-line data selector/multiplexer, inverting outputs
ЛА3   | 7400   - Quad 2-input NAND gate
ЛА4   | 7410   - Triple 3-input NAND gate
ЛА9   | 7403   - Quad 2-input NAND gate
ЛА13  | 7438   - Quad 2-input NAND buffer
ЛИ1   | 7408   - Quad 2-input AND gate
ЛЛ1   | 7432   - Quadruple 2-Input Positive-OR Gates
ЛН1   | 7404   - Quad 2-input NOR gate
ЛН2   | 7405   - Hex inverter gate
ЛН3   | 7406   - Hex inverter gate
ЛП5   | 7486   - Quad 2-input XOR gate
ТЛ2   | 7414   - Hex Inverter with Schmitt Trigger inputs
ТМ2   | 7474   - Dual D positive edge triggered flip-flop, asynchronous preset and clear
ТМ8   | 74175  - Quad D edge-triggered flip-flop, complementary outputs and asynchronous clear
ТМ9   | 74174  - Hex D flip-flop, common asynchronous clear
</code></pre>


## Digital Misc

Lib: USSR_Digital.kicad_sym

<pre><code>
К556РТ4    | 82S126     - 256x4 PROM
КР580ВТ42  | Intel 3242 - Address multiplexer and refresh counter for 16K DRAM.
КР1818ВГ93 | MB8877A    - FDD Controller
</code></pre>


## КР1801 Kit

Lib: USSR_1801.kicad_sym  - 1801 series lib

<pre><code>
КМ1801ВМ1     |  KM1801VM1      CPU        Процессор
КР1801ВП1-033 |  KR1801VP1-033             Многофункциональный контроллер внешних устройств
КР1801ВП1-065 |  KR1801VP1-033  UART       Последовательный интерфейс со скоростью до 115200 бод
КР1801РЕ2     |  KR1801RE2      ROM 4kx16  ПЗУ 4Кx16
КР1802ВВ1     |  KR1802VV1                 Cхема обмена информацией
КР1802ИР1     |  KR1802IR1                 Двухадресный регистр общего назначения, 16×4.
</code></pre>