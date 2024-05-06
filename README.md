# Rental Contract using Soroban SDK

This repository contains a smart contract implementation for managing rental agreements using the Soroban SDK.

## Overview

The Rental Contract smart contract allows users to create and manage rental agreements between asset owners and renters on a blockchain platform. It provides functionalities for creating new rental agreements and checking the status of existing agreements.

## Features

- **Create New Agreements**: Users can create new rental agreements by providing details such as asset information, renter details, rental duration, and fees.
- **Check Agreement Status**: The contract allows users to verify if a rental agreement is currently active or not based on the current timestamp.

## Dependencies

To use the Rental Contract smart contract, you need to have the following dependencies installed:

- [Soroban SDK](https://github.com/soroban/soroban): A blockchain development framework.

## Usage

To integrate the Rental Contract smart contract into your project, follow these steps:

1. **Install Dependencies**: Ensure that you have the Soroban SDK installed. You can install it using Cargo:

   ```bash
   cargo install soroban_sdk


1. **Clone the Repository**: 
   ```bash
   git clone https://github.com/your-username/rental-contract.git
2. **Build** :
   ```bash
   cd rental-contract
   cargo build
3. **Integrate in your project** :
   Import the RentalContract module into your project and start using its functions as needed.


## Contributing

Contributions are welcome! If you encounter any issues or have ideas for improvements, please open an issue or submit a pull request.

Please make sure to update tests as appropriate.

## License

This project is licensed under the MIT License.
[MIT](https://choosealicense.com/licenses/mit/)