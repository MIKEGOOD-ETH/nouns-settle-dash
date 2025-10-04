# Nouns Settler Dashboard

Static dashboard that visualizes who has been settling Nouns auctions and how often.

## Data sources

* [Nouns DAO subgraph](https://thegraph.com/hosted-service/subgraph/nounsdao/nouns-subgraph) – settlement data indexed from the Nouns Auction House contract (`0x830BD73E4184ceF73443C15111a1DF14e495C706`).
* [ENS Ideas resolver](https://ensideas.com/) – resolves settlement addresses to ENS names when available.

## Development

Serve the project locally (for example with `python3 -m http.server`) and open `index.html` in your browser.
