# ChamaChain Dapp

ChamaChain is a simple blockchain project for Chama (informal savings group) where users can deposit and withdraw funds.

## Getting Started

These instructions will help you set up and run the ChamaChain Dapp on your local machine.

### Prerequisites

Make sure you have the [DFINITY SDK](https://sdk.dfinity.org/docs/index.html) installed on your machine.

### Installation

1. Clone the ChamaChain repository.

    ```bash
    git clone https://github.com/MwemaBlessed/ChamaChain.git
    ```

2. Change to the project directory.

    ```bash
    cd ChamaChain
    ```

### Running the Dapp

1. Build the project.

    ```bash
    dfx build
    ```

2. Deploy the canister.

    ```bash
    dfx canister create --all
    dfx canister install --all
    ```

3. Start the local development environment.

    ```bash
    dfx start
    ```

4. Open the ChamaChain Dapp in your browser.

    ```
    http://localhost:8000/?canisterId=<YOUR_CANISTER_ID>
    ```

    Replace `<YOUR_CANISTER_ID>` with the canister ID displayed after the deployment.

## Usage

- Deposit funds into your Chama account.
- Withdraw funds from your Chama account.

## Contributing

Feel free to contribute to the project by submitting issues or pull requests.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
