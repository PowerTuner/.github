## PowerTuner

[Patreon](https://www.patreon.com/c/PowerTuner)

**PowerTuner** is a multi-platform tuning app that uses the Client-Daemon model.

Multiple clients are available:

- Classic desktop UI
- Gamepad first and touch friendly UI, with Text To Speech accessibility feature, for couch gaming and handheld devices
- CLI client, that outputs in json format, for your scrips

The daemon can be run as:

- systemd service (implementing systemd notifications), or standalone daemon, in Linux
- full Windows service, or standalone daemon, in Windows.

The daemon runs a TCP server, that means, you can connect to the daemon remotely! You no longer need to alt-tab while gaming!

The console client act as an overlay app, that can be activated with a gamepad key combo.

See features overview in [PowerTuner Daemon](https://github.com/PowerTuner/PowerTunerDaemon#powertunerdaemon)

## Contributing

- Please follow PowerTuner code style.
- Do not open pull requests with untested and hard to read AI generated code, those will be rejected.
