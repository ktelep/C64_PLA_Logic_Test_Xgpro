# C64 PLA Testing Logic for Xgpro

Test basic functionality of a Commodore 64 PLA using Xgpro and a TL866ii+ reader/programmer.

## Description

There is a logic IC testing function in Xgpro, combined with a TL866ii+, you can leverage this functionality to test the LOGIC of a C64 PLA to validate 
some functionality.   This does not test any timing functionality, but I've found that only in rare conditions does a PLA pass this test, but is still failed.

This performs 25 tests, which map to the (well documented) PLA I/O patterns with associated don't care conditions.

## Getting Started

### Dependencies

* Exported from Xgpro v10.80, other versions may work?

### Installing

* Navigate to Device->Logic Test in Xgpro
* Click the "Import" button, and select the file

### Executing program

* Type C64 in the search box, and select the User-C64PLA_2 Option
* Insert your PLA into the TL866ii
* Click "TEST"

