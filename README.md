# 🌲 Crypto Ecosystems
Crypto Ecosystems is a taxonomy of open source blockchain, web3, cryptocurrency, and decentralized ecosystems and their code repositories.

This dataset is not complete, and hopefully it never will be as there are new ecosystems and repositories created every day.

## How to use this taxonomy
The taxonomy can be used to generate the set of crypto ecosystems, their corresponding sub ecosystems, and repositories at a particular time.

You can export the taxonomy to a json format by using the following command:


If you want to export a single ecosystem, its sub ecosystems, and its repositories, you can use the `-e` parameter to specify a particular ecosystem.


The export format is one json entry per line like the following:

By using the branch attribute, you can see how particular repos are attributed to the parent ecosystem.

## How to update the taxonomy
There is a domain specific language (DSL) containing the keywords that can make changes to the taxonomy.  You specify migrations by using files of the format


The datetime format is a loosely ISO8601 but without the ':' characters to make them valid files on Windows.

Some examples migration filenames could be:


Simply create your new migration and add changes to the taxonomy using the keywords discussed below.

## Data Format

### Example: Adding an ecosystem and connecting it.

## How to Give Attribution For Usage of the Electric Capital Crypto Ecosystems

The repository is licensed under [MIT license with attribution](https://github.com/electric-capital/crypto-ecosystems/blob/master/LICENSE).

To use the Electric Capital Crypto Ecosystems Map in your project, you will need an attribution.

Attribution needs to have 3 components:

1. Source: “Electric Capital Crypto Ecosystems”
2. Link: https://github.com/electric-capital/crypto-ecosystems
3. Logo: [Link to logo](static/electric_capital_logo_transparent.png)

Optional:
Everyone in the crypto ecosystem benefits from additions to this repository.
It is a help to everyone to include an ask to contribute next to your attribution.

Sample request language: "If you’re working in open source crypto, submit your repository here to be counted."

<ins>Sample attribution</ins>

Data Source: [Electric Capital Crypto Ecosystems](https://github.com/electric-capital/crypto-ecosystems)

If you’re working in open source crypto, submit your repository [here](https://github.com/electric-capital/crypto-ecosystems) to be counted.

Thank you for contributing and for reading the contribution guide! ❤️
