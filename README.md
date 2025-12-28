# cpy_autoprofiler

## Description
This is a FiveM resource that automatically captures profiling data when a hitch warning occurs. It uses the `profiler` command to generate a profiling report and saves it to a specified file. The resource also includes a command to manually trigger the profiler and save the report.

## Features
- Automatically captures profiling data on hitch warnings
- Saves profiling data to a specified file

## Installation
1. Download the resource from the repository.
2. Place the resource folder in your FiveM resources directory.
3. Add `start cpy_autoprofiler` and `add_ace resource.cpy_autoprofiler command allow` to your server configuration file (server.cfg).

## Usage
- The resource will automatically start capturing profiling data when a hitch warning occurs.
- You can view the profiling data by typing in console `profiler view <auto_profiler_xxxx>.bin` where `xxxx` is the timestamp of the hitch warning. E.g. `profiler view auto_profiler_2023-10-01_12-00-00.bin`.

## Community & Support
- Join our Discord server for support and community discussions: https://discord.gg/ASFuAS6h

## Credits
- Author: Curt & Rryban
