## Installation

```
$ go install ./cmd/...
```

## Run command

```
# list balances
$ tbb balances list --datadir /path/to/datadir

# transaction
$ tbb tx add --from andrej --to tieu --value 20000 --datadir /path/to/datadir

# version
$ tbb version
```

* Params:
`--datadir`:  Required, is folder that include `database` folder

```
./<datadir>/database
├── block.db
└── genesis.json

```
