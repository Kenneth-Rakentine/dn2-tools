# DN2 Tools

Browser tools for the Digitone II mod (sample machines, recorder, Machinedrum PERC).

**Open it:** https://kenneth-rakentine.github.io/dn2-tools/

## DN2 Sample Import

Send WAV files to the Digitone II's sampler mod over USB, from Chrome or Edge (Web MIDI).

- Connect the Digitone II by USB, with **USB CONFIG** set to USB MIDI or Overbridge.
  Close Elektron Transfer first.
- Pick the Digitone II's MIDI ports and click **Connect**. The tool shows what is on the
  instrument now and how much room there is.
- Drop or browse WAVs. Choose how they go in:
  - **Replace all, in list order**: your samples become SAMP 1, 2, 3... (recordings stay);
  - **Replace all, choose each slot**;
  - **Add**: only the new samples are sent, into the slots you choose; what is already
    there stays (needs one Replace all from this browser first).
- **Send.** The samples go to the +Drive and load at every power-on.

**Install it as an app:** in Chrome, open the page and choose **Install DN2 Import**
(the icon in the address bar, or the menu). It gets its own window and desktop icon.

Nothing here is Elektron's: no firmware, no tables. The tool talks to the mod's own SysEx
commands (manufacturer ID 00 20 3C, device 7D).
