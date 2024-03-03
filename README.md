# XRP CLI Price Ticker

A simple command-line interface (CLI) tool to check XRP (Ripple) prices and changes. This tool fetches data from the cryptonator.com APIs.

## Installation

Make sure you have Node.js version 6 or higher installed. You can download it [here](https://nodejs.org/dist/latest-v6.x/).

Install the `xrpcli` globally using npm:

```bash
npm install -g xrpcli
```

## Usage

### Get average price and prices on exchanges:

```bash
xrp
```

### Get average price, prices on exchanges, and total price for a given quantity:

```bash
xrp <number>
```

## Example

```bash
# Get average price and prices on exchanges
xrp
```

### Example using watch:

You can use the `watch` command to run the CLI continuously and stay up to date:

```bash
watch -d xrp
```

## Output Example

```plaintext
-----------------------------------------------
  Symbol     Avg Price (USD)    Change (1H)
-----------------------------------------------
  XRP        $1.9299            -3.00%
-----------------------------------------------
------------------------------
  Exchange     Price (USD)
------------------------------
  BitFinex     $1.9154
------------------------------
  Bittrex      $1.9320
------------------------------
  Exmo         $2.1100
------------------------------
  Hitbtc       $1.9200
------------------------------
  Kraken       $1.9700
------------------------------
  Poloniex     $1.9120
------------------------------

```

---

**Note:** This tool is for informational purposes only, and all data is sourced from cryptonator.com APIs.

If you encounter any issues or have suggestions for improvement, please open an issue on the [GitHub repository](https://github.com/yourusername/xrpcli).

Thank you for using XRP CLI Price Ticker!
