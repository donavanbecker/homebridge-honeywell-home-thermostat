# Changelog

All notable changes to this project will be documented in this file. This project uses [Semantic Versioning](https://semver.org/)

## [Version 2.0.0](https://github.com/donavanbecker/homebridge-honeywell-home/compare/v1.1.0...v2.0.0) (2020-09-17)

### Major Changes

- Completely reworked the way that Thermostat and Leak Sensors are discovered.
  - Added Room Priority. This is for T9 & T10 Thermostats Only.

### Changes

- You can now set the Thermostat Setpoint Status to: NoHold, PermanentHold, or TemporaryHold.
- You can now set the Room Priority Type to: PickARoom, WholeHouse, or FollowMe.
- Fix for CurrentHeatingCoolingState not showing the correct state.

## [Version 1.1.0](https://github.com/donavanbecker/homebridge-honeywell-home-thermostat/compare/v1.0.1...v1.1.0) (2020-08-29)

### Changes

- Added the option to hide Fan service.

## [Version 1.0.1](https://github.com/donavanbecker/homebridge-honeywell-home-thermostat/compare/v1.0.0...v1.0.1) (2020-08-29)

### Changes

- Small cosmetic changes.

## [Version 1.0.0](https://github.com/donavanbecker/homebridge-honeywell-home-thermostat/releases/tag/v1.0.0 (2020-08-29)

### Major Changes

- Changed Homebridge Honeywell Home Plugin into an all in one plugin, that supports Thermostats, Room Sensors, and Leak Sensors.

### Changes

- Split off plugin to only support Thermostats and Thermostat Fans.
