# Simple Group Analysis
Decomposes a set of expressions into a group expression.
The toolkit currently offers enrichment analysis, hierarchical
enrichment analysis, PLS regression, Shape alignment or clustering
as well as  rudimentary factor analysis.
The expression regulation can be studied via a statistical
test that relates it to the observables in the journal file.
The final p values are then FDR corrected and the resulting
adjusted p values are produced.


Visit the active code via :
https://github.com/richardtjornhammar/impetuous

Visit the published code : 
https://doi.org/10.5281/zenodo.2594690

Cite using :
DOI: 10.5281/zenodo.2594690

# Pip installation with :
pip install impetuous-gfa

# Version controlled installation of the Impetuous library

The Impetuous library

In order to run these code snippets we recommend that you download the nix package manager. Nix package manager links from Oktober 2020:

https://nixos.org/download.html

$ curl -L https://nixos.org/nix/install | sh

If you cannot install it using your Wintendo then please consider installing Windows Subsystem for Linux first:

https://docs.microsoft.com/en-us/windows/wsl/install-win10

In order to run the code in this notebook you must enter a sensible working environment. Don't worry! We have created one for you. It's version controlled against python3.7 and you can get the file here:

https://github.com/richardtjornhammar/rixcfgs/blob/master/code/environments/impetuous-shell.nix

Since you have installed Nix as well as WSL, or use a Linux (NixOS) or bsd like system, you should be able to execute the following command in a termnial:

$ nix-shell impetuous-shell.nix

Now you should be able to start your jupyter notebook locally:

$ jupyter-notebook impetuous_finance.ipynb

and that's it.
