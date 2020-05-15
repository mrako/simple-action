# Simple Github Action using Docker

This action prints "Hello World" or "Hello" + the name of a person to greet to the log.

## Inputs

### `who-to-greet`

**Required** The name of the person to greet. Default `"mrako"`.

## Outputs

### `time`

The time we greeted you.

## Example usage

uses: mrako/simple-action@v1
with:
  who-to-greet: 'mrako'
