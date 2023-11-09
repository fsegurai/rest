# Country Details API

Welcome to the Country Details API, an open-source project that allows users to fetch detailed information about countries for integration into their systems.

## Overview

The Country Details API provides a simple and efficient way to retrieve various details about countries, including but not limited to:

* Country name
* Capital
* Population
* Area
* Currency
* Language(s)
* Flag URL

## Usage

To integrate the Country Details API into your system, follow these steps:

1. **API Endpoint**:
    Base URL: https://api.countrydetails.com
    Endpoint for country details: `/country/{country_code}`

2. **Authentication**:
    The API is open and does not require authentication.

3. **Request**:
    Make a `GET` request to the country details endpoint, replacing `{country_code}` with the ISO 3166-1 alpha-2 country code (e.g., `US` for the United States).
    Example: https://api.countrydetails.com/country/US

4. **Response**:
    The API will respond with a JSON object containing the requested country details.

``` json
{
  "name": "United States",
  "capital": "Washington, D.C.",
  "population": 331002651,
  "area": 9833517,
  "currency": "USD",
  "languages": ["English"],
  "flag": "https://api.countrydetails.com/flags/us.png"
}
```

## Contributing

We welcome contributions from the community! If you find any issues or have suggestions for improvement, please feel free to open an issue or submit a pull request.

## Guidelines for Contributions:

* Follow the Contributor [Covenant Code of Conduct](https://www.contributor-covenant.org/).
* Fork the repository and create a branch for your contributions.
* Keep the code clean, well-documented, and maintainable.
* Test your changes thoroughly before submitting a pull request.

## License

This project is licensed under the [MIT License](https://opensource.org/license/mit/). Feel free to use, modify, and distribute the code in accordance with the license terms.