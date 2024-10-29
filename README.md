# TSSSF-KR Card Definitions and Translations
To make editing easy, and to aid in the collaboration of translators, we translated the cards on a shared online spreadsheet. The contents of said spreadsheet is exported as a `.csv` file under `translation_data/` directory.

`translator.py` will read those `.csv` files along with the original `.pon` files to generate a translated `.pon` file.

## Running
This script does not require any special installation or dependencies.
Just run `python3 translator.py`.
