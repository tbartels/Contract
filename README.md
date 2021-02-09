# CSS Wizardry Ltd. contract

This is the standard contract to which I — acting as Opticgait Ltd. — operate.
This contract can be amended and updated to be tailored to individual clients
and projects, this is merely my boilerplate.

## Using this contract

In keeping with my sharing and open-source nature, I am making this contract
freely available for you to modify and use for yourself on your client projects.
I do, however, accept absolutely **zero liability for anything at all**. Use
entirely at your own risk.

## Contributions, suggestions and improvements

I, as you’ve probably already guessed, am not a lawyer. This is a simple,
layman’s contract that I have drawn up purely to manage the expectations of both
myself and my clients. If you have an suggestions, improvements or criticisms,
please [open an issue](https://github.com/tbartels/Contract/issues) or
[submit a pull request](https://github.com/tbartels/Contract/pulls).

## Basic PDF creation

    # npm install -g markdown-pdf
    # sed 's/{{theclient}}/Client Name/g;s/{{myaddress}}/My Address, 12345/g;s/{{clientaddress}}/Client Address, 54321/g;s/{{currency}}/GBP/g;s/{{devrate}}/60/g;s/{{nondevrate}}/40/g;s/{{thecompany}}/Client Company/g' Contract.md > newclient-hourly.md
    # markdown-pdf -f A4 newclient-hourly.md

## Thank you

With special thanks to [Andrew Clarke](https://twitter.com/Malarkey), [Anna
Debenham](https://twitter.com/anna_debenham), and [Harry
Roberts](https://github.com/csswizardry).
