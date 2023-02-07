
# WTHOLD: A Tax Withholding Calculator

WTHOLD is a simple tax withholding calculator that provides you with the amount
of tax that will be withheld from your income based on a specified tax rate. It
provides an easy-to-read output that breaks down the calculation.

By default, WTHOLD computes tax withholding based on a 24% tax rate. However,
you can specify a different tax rate by providing a number as an argument. The
tax rate must be a number between 1 and 100.

## How to use WTHOLD
1. Clone the repository: `git clone https://github.com/lefmanos/wthold.git`
2. Change into the directory: cd wthold
3. Make the script executable: chmod +x wthold
4. Install the [fzf](https://github.com/junegunn/fzf) utility 
5. Run the script: ./wthold [tax-percentage]

If you provide a tax percentage and an income as arguments, WTHOLD will compute
the tax withholding based on those values. If no argument is provided, WTHOLD
will use the default 24% tax rate.

## Sample output

```sh
> 75                      ╭──────────────────────────────────────────────────────────────╮
  0/2 ─────────────────── │ price 75                                                     │
                          │ taxrate 24%                                                  │
                          │                                                              │
                          │ 75 is 24% of 312.50                                          │
                          │ 75's  24% is 18.00                                           │
                          │                                                              │
                          │ 75 is 98.68 - 24%                                            │
                          │ 75 - 24% is 57.00                                            │
                          │                                                              │
                          ╰──────────────────────────────────────────────────────────────╯
  ```

## Features

* Quick and easy tax withholding calculations
* Ability to specify a custom tax rate and income
* Clear and concise output that breaks down the calculation

## Requirements

WTHOLD requires the following utilities to be installed on your system:

* `bc`: A command-line calculator
* `fzf`: A command-line fuzzy finder


## Contributing

We welcome contributions to WTHOLD! If you have a bug fix or a new feature,
please open a pull request. If you have any questions or feedback, please open
an issue.

