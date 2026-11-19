# Changelog

## 2.1.0

### New Features

- Keytracking added for the filter cutoff frequency. When enabled, the filter frequency can be specified in number of scale steps above the sounding note.
- Demo version added.

### Fixes

- Presets or session states from earlier versions of Mutant Squelch do not specify a value for newly added controls; such controls now inherit the default values rather than keeping them from the previously loaded patch.
- A rare crash that could happen when saving/loading a project while preset controls were in use.

## 2.0.3

### New Features

- Panic button on the status bar to silence all notes
- Link to the customer portal for new versions

### Improvements

- Output Gain now goes up to +60 dB, so quiet patches can reach full scale

### Fixes

- Stuck notes when a host re-sends a note-on for a note that is already held
- MTS-ESP patches showing as Scale Files on session load in some situations

## 2.0.2

### Improvements

- Make all envelope generators sample-accurate
- Stop notes playing when switching presets
- Better pitch env defaults on Init

### Fixes

- Live retuning of partials on MTS-ESP scale morph

## 2.0.1

- Initial release