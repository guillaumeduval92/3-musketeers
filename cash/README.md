# Cash 

> A library money converter

## Installation

You must have downloaded the cash library first

```
❯ cd /path/cash
❯ npm i
```

Cash is ready to be used !

## Getting started

```
❯ cd bin
❯ node index.js
```

Index.js converts 1 USD in the 3 default currencies set (EUR,GBP,JPY)

## Commands

```
❯ $ cash <amount> <from> <to>
```

Examples :

```
❯ 10 usd eur pln
```

It converts 10 USD in EUR and PLN

```
❯ 10 eur
```

It converts 10 EUR in the 3 default currencies set


#### Changing the default currencies :

```
❯ index.js -s <defaultFrom> <defaultTo>
```

Example :

```
❯ index.js -s usd aud
```

Index.js converts now by default 1 USD to AUD.
