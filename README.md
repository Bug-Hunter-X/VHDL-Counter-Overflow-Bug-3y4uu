This repository contains a VHDL code example demonstrating a common error: integer overflow in a counter without proper rollover handling.  The `buggy_counter.vhdl` file showcases the flawed code. The `fixed_counter.vhdl` file provides the corrected version.  The bug arises from an incorrectly specified range that doesn't account for the wrap-around condition. When the counter reaches 15, incrementing it results in undefined behavior.  The solution demonstrates how to properly handle the overflow using the modulo operator.