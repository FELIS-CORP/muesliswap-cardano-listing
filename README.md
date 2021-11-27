# MuesliSwap token listing 🥣

The official repository to request a token listing @ AdaMuesliSwap

This list includes all the tokens listed at [ada.muesliswap.com](https://ada.muesliswap.com).
In order to request a coin to be listed, follow our contribution guide.

## Structure

The folder `tokens` contains [JSON](https://en.wikipedia.org/wiki/JSON) files that describe each token listed at AdaMuesliSwap.
Each file contains information on what the coin is called, its supply and other important information.
The name of the file is the string `<policy_id>.<name>.json`.

In the folder `images`, an image is listed for each token that should be traded.
This is required so that an image can be displayed for the token on the website.
The name of the file is the string `<policy_id>.<name>.png`.

### Contents of the listing file

| Field | Description | Example |
| ----- | ----------- | ------- |
| `policyId` | The policy id of the token | `8a1cfae21368b8bebbbed9800fec304e95cce39a2a57dc35e2e3ebaa` |
| `name` | The asset name of the token | `MILK` |
| `symbol` | A trading symbol of the token | `MILK` or `CDOG` |
| `website` | Homepage of the corresponding token | `https://ada.muesliswap.com` |
| `description` | A very short description of the token | `Your favorite pre-sale token, making you stronger` |
| `totalSupply` | The total minted amount of the token | `100000000` |
| `amounts` | A list of integers of the trade size options |`[1000, 5000, 10000]` |

See [tokens/8f52f6a88acf6127bc4758a16b6047afc4da7887feae121ec217b75a.SNOW.json](tokens/8f52f6a88acf6127bc4758a16b6047afc4da7887feae121ec217b75a.SNOW.json) for an example file.
Also check the token on [cardanoscan.io](https://cardanoscan.io/token/8a1cfae21368b8bebbbed9800fec304e95cce39a2a57dc35e2e3ebaa4d494c4b) if you are unsure about some values.

## How to contribute

Submit a Pull Request to this repository  that adds both the correct JSON token description in the [tokens](tokens) folder and an image for the token in the [images](images) folder.

Looking forward to your coin suggestions! 🥣
