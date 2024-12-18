Bear Granulator - Pure Data Granular Synthesizer
A granular synthesis sampler built in Pure Data. Record audio, manipulate it with granular synthesis, and perform with MIDI control.
Current Features

Real-time granular processing
Record and playback functionality
Sample loading and saving
Adjustable parameters:

Grain size
Playback speed
Grain speed


Hanning window envelope
Basic GUI with visual feedback

To-Do List
High Priority

Fix file handling system

Implement better file naming conventions
Add date/time stamps to recordings
Create organized sample directory structure
Add file overwrite protection


MIDI Implementation

Test with Arturia BeatStep
Map controls:

Knobs to granular parameters
Pads for transport control
Add preset storage/recall


Implement MIDI learn functionality


Raspberry Pi 3 Port

Test performance on RPi 3
Optimize for resource usage
Setup headless operation
Configure auto-start
Test audio interfaces



Future Enhancements

Audio Processing

Multiple grain streams
Grain parameter modulation (LFOs)
Additional window shapes
Position control and randomization
Per-grain filtering
Effects (reverb, delay)


Interface Improvements

Grain statistics display
CPU usage monitoring
Better visual feedback
Preset management system


Hardware Integration

Small screen support
Custom MIDI controller mapping
CV/Gate integration options
USB drive sample import



Dependencies

Pure Data Vanilla
Required externals (list TBD)

Installation
bashCopy# Installation instructions to be added
Usage

Clone repository
Open modules.pd in Pure Data
Connect MIDI controller if available
Load sample or record new audio
Adjust parameters via GUI or MIDI

Development Status

 Basic granular engine
 Recording functionality
 Parameter control
 File system improvements
 MIDI implementation
 Raspberry Pi port
 Extended features

Contributing
Contributions welcome! Please read the contributing guidelines before making a pull request.
License
[License type to be determined]
Acknowledgments

Thanks to all Pure Data community members who shared granular synthesis knowledge
Inspired by various hardware and software granular synthesizers
