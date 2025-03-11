# fastcuts-json

A JSON repository providing quick access to relevant websites for the Fastcuts website.

## Overview

This repository contains the primary data file `fastcuts.json`, which powers the Fastcuts website. Fastcuts is a web application that provides users with fast, searchable shortcuts to relevant websites.

## Features

- Simple JSON structure for easy editing and maintenance
- Powers the searchable interface of the Fastcuts website
- Enables users to quickly find and access websites by name or description

## Usage

The `fastcuts.json` file is automatically loaded by the Fastcuts website and provides the data for all website shortcuts displayed on the platform.

### JSON Structure

Each website entry follows this format:

```json
{
  "name": "Website Name",
  "description": "Brief description of the website",
  "link": "https://example.com"
}
```

## Contributing

Want to add a useful website to the collection?

1. Fork the repository
2. Add your website entry to the `fastcuts.json` file
3. Submit a pull request

Please ensure your entry includes a descriptive name, helpful description, and correct URL, do NOT end an url with a /, this breaks the json formatting.

## Implementation

The Fastcuts website fetches this JSON file and renders interactive buttons for each website entry. Users can:

- Search websites by name or description
- Expand entries to see full descriptions
- Visit websites directly with a single click

## License

[MIT License](LICENSE)

## Contact

Issues and pull requests welcome! 

Current temp-hosted website can be checked-out [here](http://fate.rf.gd/)
