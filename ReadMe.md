# Subdomain Fetcher by GameofCode

Subdomain Fetcher is a Python tool designed to fetch and save all subdomains of a given domain using the SecurityTrails API. The first time the script is run, it prompts the user to enter their SecurityTrails API key, which is then saved for future use. The tool is easy to use and provides a clear and concise output of all subdomains related to the specified domain.

## Features

- Prompts the user for the SecurityTrails API key if not already provided.
- Fetches all subdomains of a given domain, including inactive ones.
- Saves the list of subdomains to a text file.

## Prerequisites

- Python 3.x
- `requests` library

## Installation

1. Clone the repository or download the script directly.
2. Ensure you have Python 3.x installed on your machine.
3. Install the `requests` library if you haven't already:

   ```bash
   pip install requests
   ```

## Usage

1. Save the script as `subdomain_fetcher.py`.
2. Run the script using the following command:

   ```bash
   python subdomain_fetcher.py
   ```

3. The first time you run the script, you will be prompted to enter your SecurityTrails API key. This key will be saved in a file named `securitytrails_api_key.txt` for future use.
4. Enter the domain name for which you want to fetch subdomains.
5. The script will fetch the subdomains and save them to a file named `<domain>_subdomains.txt`.

## Example

```bash
$ python subdomain_fetcher.py
```
