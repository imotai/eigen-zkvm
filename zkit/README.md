# eigen zkit

A universal commandline for [plonky](../plonky) and [starky](../starky).

## Usage

```
zkit 0.1.6

USAGE:
    zkit <SUBCOMMAND>

FLAGS:
    -h, --help       Prints help information
    -V, --version    Prints version information

SUBCOMMANDS:
    aggregation_prove                      Proof aggregation for plonk
    aggregation_verify                     Verify aggregation proof
    compile                                Compile circom circuits to r1cs, and generate witness
    export_aggregation_verification_key    Export aggregation proof's verification key
    export_verification_key                Export proof's verification key
    generate_aggregation_verifier          A subcommand for generating a Solidity aggregation verifier smart
                                           contract
    generate_verifier                      Generate solidity verifier
    help                                   Prints this message or the help of the given subcommand(s)
    prove                                  Prove by Plonk
    setup                                  Trust setup for Plonk
    stark_prove                            Prove and verify all in one
    verify                                 Verify the Plonk proof
```

The recursive proof example can be found [here](../starkjs).
