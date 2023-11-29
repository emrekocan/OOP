echo "# Bank Account Management System

This Python script implements a simple Bank Account Management System using Object-Oriented Programming (OOP) concepts.

## Features

- **Account Class:**
  - Initializes an account with a name, account number, and initial balance.
  - Displays account information.
  - Allows withdrawal and deposit operations.

- **SavingsAccount Class (Inheritance):**
  - Inherits from the Account class.
  - Adds the ability to calculate and add interest to the account balance.

## Usage

\`\`\`python
# Create a SavingsAccount instance
savings_account = SavingsAccount(\"Emre Koçan\", 123456, 1000, 0.05)

# Display account information
print(savings_account)

# Deposit money into the account
savings_account.deposit(800)

# Add interest to the savings account
savings_account.add_interest()
\`\`\`

## How to Run

1. Clone the repository:
   \`\`\`bash
   git clone https://github.com/your-username/bank-account-management.git
   \`\`\`

2. Navigate to the project directory:
   \`\`\`bash
   cd bank-account-management
   \`\`\`

3. Run the script:
   \`\`\`bash
   python main.py
   \`\`\`

## Contributions

Contributions are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or create a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details." > README.md
