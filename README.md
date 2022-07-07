# Infomax-fingerprint
300 bit Infomax fingerprint from SMILEs code.

## Usage

you need to be careful about the failed calculation, in case there is a mis match between output df and smiles list.

```
from infofunction import smi2infomax

smiles = any_df_contains_SMILE['CanonicalSMILES']
df = smi2infomax(smiles)
# df is a 300 bit fingerprint DataFrame

```
