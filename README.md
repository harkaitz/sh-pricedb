# SH-PRICEDB

Update prices for [ledger](https://www.ledger-cli.org/).

## Help

pricedb

    Usage: pricedb [-s]
    
    Maintain the prices of "commodities" "ledger(1)" in ~/.pricedb updated
    by executing commands listed in ~/.pricedb.cfg or ${PRICEDB_CFG}.

    The format of ~/.pricedb.cfg is:
    
        COMMODITY CURRENCY COMMAND...
    
    The format of the generated file in ~/.pricedb is:
    
        P DATE COMMODITY NUMBER CURRENCY
    
    The program supports the following flags:
    
        -v : Show configuration.
        -s : Print today prices to standard output.
        -w : Save prices to `~/.pricedb`.

## Collaborating

For making bug reports, feature requests and donations visit
one of the following links:

1. [gemini://harkadev.com/oss/](gemini://harkadev.com/oss/)
2. [https://harkadev.com/oss/](https://harkadev.com/oss/)

