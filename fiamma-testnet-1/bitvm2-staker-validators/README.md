# Fiamma Chain Validator Information Registry

This is the validator registration guide for the first phase of the Fiamma testnet.

## Background

The Fiamma chain is a blockchain developed using the Cosmos SDK, incorporating an innovative BitVM2 challenge mechanism. To become a validator on the Fiamma chain, candidates must first stake BTC in our developed committee program. This unique staking mechanism is designed to support the BitVM2 challenge mechanism.

In this phase, we invite participants interested in becoming Fiamma chain validators to submit their information. We will review this information and send test coins to eligible candidates, enabling them to formally join the network.

Please note that our first round of public testnet is limited to 21 nodes, operating on a first-come, first-served basis.

## Registration Eligibility Criteria

To ensure the security and quality of the network, we have established strict eligibility criteria. To be considered an eligible validator candidate, you need to meet the following requirements:

- Having at least 1 signet BTC for bitvm2 challenge program staking.
- Possess the technical capability to run a validator node
- Submit complete and accurate validator information
- Submit a Pull Request before the specified deadline (date to be determined)

## Obtaining Fiamma Addresses

Before proceeding with the registration, you'll need to obtain your Fiamma address and Fiamma validator address. Please follow the instructions in these guides:

- [How to obtain a Fiamma address](https://docs.fiammachain.io/user-guides/manage-keys#list-keys)
- [How to obtain a Fiamma validator address](https://docs.fiammachain.io/developer-guides/run-a-fiamma-node/become-a-validator#id-5-verify-your-validator)

Make sure you have these addresses ready before proceeding with the registration steps.

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

During the first phase of the Fiamma testnet, the following information cannot be changed during this phase:

- ❌ Fiamma address
- ❌ Fiamma validator address
- ❌ BTC address

To update allowed information, please submit a new Pull Request following the initial registration steps.

## After Submission

Once your Pull Request is submitted, our team will review your application. If your PR is merged, it means your application has been accepted. Here's what happens next:

1. We will send a notification to the contact email you provided in your application.
2. You will receive Fiamma testnet tokens to the Fiamma address you specified.
3. You can then proceed with staking these tokens and setting up your validator node.

For any questions or support, please refer to our [documentation](https://docs.fiammachain.io) or contact us through [contact@fiammachain.io](mailto:contact@fiammachain.io).

We wish you success in your staking journey on the Fiamma testnet!