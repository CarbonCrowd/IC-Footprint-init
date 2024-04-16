### Carbon crowd - IC footprint SNS

##### For sns_init

###### General

```
Name
...

Description
...

Logo (must be a PNG)
...

Frontend URL of the Dapp
https://...

Summary (recommend looking at earlier SNS'es)
...

Dapp canisters (canisters the SNS needs to control)
...

```

###### Token

```
Name (ex; IC footprint token)
...

Symbol (ex; ICFT)
...

Logo (must be a PNG)
...

```

###### Developer / Team neurons

Each neuron needs to be specified as below, if you want to drop multiple neurons to the same principal you need to iterate (+1) the memo.

Note:

- dissolve delay is the time it initially takes to dissolve the neuron
- vesting period is the time it takes before the neuron can start dissolving

```
principal: aaaaa-aa
stake: 20 tokens
memo: 0
dissolve_delay: 1 month
vesting_period: 2 years
```

###### Total tokens

```
governance: 57_000_000 tokens  (57m)
swap:       20_000_000 tokens  (20m)
neurons:    23_000_000 tokens  (23m)
total:     100_000_000 tokens (100m)
```
