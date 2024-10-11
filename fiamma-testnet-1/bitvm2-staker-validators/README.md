# Fiamma Network Validator Information Registry

This is the validator registration guide for the first phase of the Fiamma testnet.

## Background

The Fiamma network is a blockchain developed using the Cosmos SDK, incorporating an innovative BitVM2 challenge mechanism. To become a validator on the Fiamma network, candidates must first stake BTC in our developed committee program. This unique staking mechanism is designed to support the BitVM2 challenge mechanism.

In this phase, we invite participants interested in becoming Fiamma network validators to submit their information. We will review this information and send test coins to eligible candidates, enabling them to formally join the network.

## Registration Eligibility Criteria

To ensure the security and quality of the network, we have established strict eligibility criteria. To be considered an eligible validator candidate, you need to meet the following requirements:

- Having a specified number of testnet BTC for bitvm2 challenge program staking.
- Possess the technical capability to run a validator node
- Submit complete and accurate validator information
- Submit a Pull Request before the specified deadline (date to be determined)

## Registration Steps

1. Fork this repository
2. Create a new file in the `validators` directory, named `<your-validator-name>.json`
3. Copy the contents of `validator-template.json` into your new file
4. Fill in all necessary information
5. Submit a Pull Request

## Validator Information Template

Please use the following template to fill in your validator information: [validator-template.json](vaildator-template.json)


## Creating a Pull Request

When you're ready to submit your validator information, please create a Pull Request using the [new_validator.md](../..//.github/PULL_REQUEST_TEMPLATE/new_validator.md) template. 

Please ensure you:

1. Use the correct template when creating your Pull Request.
2. Fill in all required information as specified in the template.
3. Review your submission for accuracy before submitting.

Following this template is crucial for a quick review of your submission. If you have any questions, please contact the project maintainers.

## Review Process

1. After submitting a Pull Request, our automated scripts will check if your provided information meets the basic requirements.
2. If the automatic check passes, our team will conduct a manual review.
3. Upon approval, we will send test coins to the Fiamma address you provided.
4. After receiving the test coins, you can start setting up your validator node.
5. Once your node is successfully set up, your Pull Request will be merged, and your information will be added to the validator list.

## Missed the Registration?

After the initial registration period ends, we may open additional registration windows based on network needs. However, we strongly encourage interested participants to submit their applications during the first registration period.

Candidates who fail to register at this stage may still be able to participate in the network but may not enjoy certain privileges or rewards reserved for early participants.

## Modifying Validator Information

During the first phase of the Fiamma testnet, validators can update the following information:

- ✅ Website
- ✅ Description
- ✅ Contact information

The following information cannot be changed during this phase:

- ❌ Validator name
- ❌ Fiamma address
- ❌ Fiamma validator address

To update allowed information, please submit a new Pull Request following the initial registration steps.

## Important Notes

- Ensure all information you provide is accurate and up-to-date.
- Safeguard your private keys and mnemonics, as these are crucial for your validator identity.
- If you encounter any issues during the registration process, please contact us through [contact@fiammachain.io](mailto:contact@fiammachain.io).

We look forward to your participation in building the future of the Fiamma network!