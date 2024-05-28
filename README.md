# Gelato VRF Consumer Test Template

This repository provides a template for testing VRF (Verifiable Random Function) consumer smart contracts using Foundry. The template is designed to be flexible and reusable, allowing developers to easily test their own VRF consumer contracts.

## Overview

The template includes:

- An interface (`IVRFConsumer.sol`) defining the required functions and events for a VRF consumer contract.
- An example test contract (`SimpleVRFContract`) that implements the interface and demonstrates how to use the `VRFConsumer` library to interact with the VRF coordinator.
- Example tests (`SimpleVRFContractTest`) that demonstrate how to test the VRF consumer contract using the `VRFConsumerTest` library.

## Prerequisites

- [Foundry](https://getfoundry.sh/) - A blazing fast, portable and modular toolkit for Ethereum application development written in Rust.

## Getting Started

### Clone the Repository

```bash
git clone https://github.com/yourusername/vrf-consumer-test-template.git
cd vrf-consumer-test-template
```

### Run the Tests

```bash
foundry test
```

This will compile the contracts and run the tests, providing you with feedback on the functionality of your VRF consumer contract.

Output

```bash
Ran 2 tests for test/SimpleVRFContract.t.sol:TestSimpleVRFContract
[PASS] testFulfillRandomness() (gas: 193126)
[PASS] testRequestRandomness() (gas: 88403)
Suite result: ok. 2 passed; 0 failed; 0 skipped; finished in 944.90µs (491.00µs CPU time)
```
