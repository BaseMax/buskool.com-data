# Buskool Data

This repository contains the collected product data from the [Buskool website](http://www.buskool.com/) (باسکول). The data is stored in +20k JSON files, each containing detailed information about products available on the website.

## Structure
- Each JSON file represents a subset of the product catalog.
- Data fields include:
  - Product Name
  - Description
  - Price
  - Category
  - Additional metadata as available on the website.

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/BaseMax/buskool.com-data.git
   cd buskool.com-data
   ```

2. Load the JSON files in your preferred environment for analysis or integration:
  ```python
  import json
  
  with open('data/1.json', 'r', encoding='utf-8) as file:
      data = json.load(file)
      print(data)
  ```

## Data Source

The data in this repository was collected using the Buskool Crawler. It is intended for educational, research, and development purposes only.

## Contributing

Contributions, issues, and feature requests are welcome! Feel free to open an issue or submit a pull request.

## License

This project is licensed under the GNU General Public License v3.0. See the LICENSE file for details.

Copyright © 2024, Max Base
