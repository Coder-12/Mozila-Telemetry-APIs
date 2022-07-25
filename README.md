# Mozila-Telemetry-APIs
APIs for easier telemetry collections. Contains the C++ data validation and conversion routines. The Converter class, which is used to convert a JSON payload from the raw form submitted by Firefox to the more compact storage format for on-disk storage and processing.

You can run the main method in this file to process a given data file (the expected format is one record per line, each line containing an id followed by a tab character, followed by a json string).
