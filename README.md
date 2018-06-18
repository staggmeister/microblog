## Translations

Create the .pot file (Extracting Text to Translate) :
* pybabel extract -F babel.cfg -k _l -o messages.pot .

Generating a Language Catalog
* pybabel init -i messages.pot -d app/translations -l fr

fr for french

Compile translations
* pybabel compile -d app/translations