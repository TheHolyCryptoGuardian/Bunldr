# Commands to install [**Bundlr node**](https://github.com/TheHolyCryptoGuardian/Bunldr/blob/main/BundlrNode)

Use `curl -s https://raw.githubusercontent.com/TheHolyCryptoGuardian/Bunldr/main/BundlrNode.sh > bundlr.sh && \
chmod +x bundlr.sh && \
bash bundlr.sh` to start installing Bundlr node.

Use `cd $HOME/bundlr/validator-rust && \
docker-compose restart` to restart your node.

Use `cd $HOME/bundlr/validator-rust && \
docker-compose stop` to stop your node.

Use `cd $HOME/bundlr/validator-rust && \
docker-compose up -d` to start docker.

Use `cd $HOME/bundlr/validator-rust && \
docker-compose down -v` to delete docker.

Use `cd $HOME/bundlr/validator-rust && \
docker-compose logs -f --tail 10` to check node logs.

Use `cd $HOME/bundlr/validator-rust && \
cargo run --bin wallet-tool show-address \
--wallet wallet.json | jq ".address" | tr -d '"'` to check wallet address.

Use `cd $HOME/bundlr/validator-rust && \
testnet-cli balance ${BUNDLR_ADDRESS}` to check wallet balance.

---
Special thanks to [Kallen-c](https://github.com/Kallen-c) for his guide <3

# Bundlr
Bundlr is building the future of data storage by bringing the speed and ease of web2 to web3 technology. We are a decentralized storage scaling platform, powered by Arweave. We make it easy for developers and businesses to store their data permanently, for just a one-time fee.

# Features
- **Blockchain agnostic**. Upload your data from any major blockchain

- **Pay with any token**. Pay in any major token including ETH, SOL, MATIC, and more

- **Pay once, stored forever**. Pay once and have your data stored forever on Arweave

- **Own your data**. With no singular entity holding your data, you are always in control of your data

- **Unlimited storage**. Unlimited storage on Arweave means you’ll never be restricted by data limits again

- **Guaranteed seeding**. Your data is guaranteed to be uploaded to Arweave

- **Instant data**. From the moment you upload, your data is instantly accessible

- **Free Transactions**. Free for data uploads under 100 kb

- **True Decentralization**. Once on Bundlr, your data is always stored on a decentralized platform
