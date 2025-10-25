# Ghidra TopSM

[![Build](https://github.com/antoniovazquezblanco/GhidraTopSM/actions/workflows/main.yml/badge.svg)](https://github.com/antoniovazquezblanco/GhidraTopSM/actions/workflows/main.yml)
[![CodeQL](https://github.com/antoniovazquezblanco/GhidraTopSM/actions/workflows/codeql.yml/badge.svg)](https://github.com/antoniovazquezblanco/GhidraTopSM/actions/workflows/codeql.yml)

This repository contains the sources of a Ghidra plugin that enables reverse engineering of TopSM binaries.

TopSM architecture is used in Texas Instruments CC13XX and CC26XX RF Cores.

This is a fork into a separate repo of the original Ghidra TopSM architecture plugin that can be found at the [Beyond BLE Tools](https://github.com/rjp5th/beyond-ble-tools/tree/main/ghidra_topsm) repo originally released as part of the [Beyond BLE](https://events.ccc.de/congress/2024/hub/en/event/beyond-ble-cracking-open-the-black-box-of-rf-microcontrollers/) 38C3 talk.
The repo was forked for maintenance and and to provide easely installable releases for a wide range of Ghidra versions.

## Installing

This extension is available for installation via the [Ghidra Extension Manager](https://github.com/antoniovazquezblanco/GhidraExtensionManager).

You may also install this extension by going to the [releases page](https://github.com/antoniovazquezblanco/GhidraTopSM/releases) and downloading the latest version for your Ghidra distribution. In order to install from the release, in Ghidra main window go to `File` > `Install extensions...`. In the new window press the `+` icon to import the downloaded zip.
