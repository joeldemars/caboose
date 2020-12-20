# Caboose
App for TI-83+ and TI-84+ calculators that adds "Ans" to the end of applicable entries.
## About
After enter is pressed, Caboose looks at the entry and adds `Ans` whenever it makes sense, such as when it ends in `-`, `sin(`, or an empty entry box.
## Usage
To activate, simply run the app. It will be deactivated (but not uninstalled) by a RAM clear, and so must be run after one occurs to reactivate it.
## Installation
[Download](https://github.com/SueDoenim/caboose/releases) or build `caboose.8xk` and use [TI Connect](https://education.ti.com/en/products/computer-software/ti-connect-sw) or [TiLP](http://lpg.ticalc.org/prj_tilp) to install onto your calculator.
## Building
Download or build [spasm](https://github.com/alberthdev/spasm-ng) and build using the command `spasm caboose.z80 caboose.8xk`.
