# ignite-cli

Ignite cli commands

```
ignite scaffold chain mychain

ignite scaffold module blog

ignite scaffold list post title body

ignite scaffold message write-comment

ignite chain serve

 ```

### Interacting with your blockchain

- Go client library: cosmosclient
- Typescript client generation

#### Generate a Typescript client specific to your blockchain

```
ignite generate ts-client

```

#### Sample application

```
ignite scaffold chain exchange

ignite chain serve

ignite s module dex --ibc

git add .
git commit -m <message>

ignite s list pool amount:coin height:int --module dex

ignite s message add-liquidity amount:coin denom --module dex

ignite chain serve -r

Add frank user in config.json file


```
