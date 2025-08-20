# Lapwings Lessons

A comprehensive stenography dictionary project focused on building and organizing dictionaries for the Lapwing stenographic theory.

## Overview

This project contains stenographic dictionaries and word lists organized for learning and practicing stenography using the Lapwing theory. The dictionaries map English words to their stenographic chord representations, helping stenographers build muscle memory and improve their typing speed.

## Project Structure

### Ready-to-Use Dictionaries (`ready/`)
These are completed, organized dictionary files ready for use:

- **`auxiliary-verbs.tsv`** - Common auxiliary verbs (am, are, be, been, being, etc.)
- **`compound-adverbs.tsv`** - Complex adverbs (abroad, aground, alike, etc.)
- **`conjunctions.tsv`** - Connecting words (also, and, as, but, if, etc.)
- **`demonstrative-interrogative-pronouns.tsv`** - Demonstrative and question words (this, that, who, etc.)
- **`indefinite-pronouns.tsv`** - Non-specific pronouns (all, any, another, etc.)
- **`personal-pronouns.tsv`** - Personal pronouns (I, you, he, she, it, etc.)
- **`possessive-reflexive-pronouns.tsv`** - Possessive and reflexive forms (mine, yours, myself, etc.)
- **`simple-adverbs.tsv`** - Basic adverbs (about, above, across, after, etc.)

### Work in Progress (`under-construct/`)
Word lists being developed and organized:

- `action_verbs.txt` - Action and movement verbs
- `additional_nouns.txt` - Extended noun vocabulary
- `adjectives.txt` - Descriptive words
- `american_top_100.txt` - Most frequently used American English words
- `auxiliary-constractions-forms-verb.txt` - Contracted auxiliary verb forms
- `common_nouns.txt` - Everyday nouns
- `common_verbs.txt` - Frequently used verbs
- `descriptive_words.txt` - Adjectives and descriptors
- `function_words.txt` - Grammatical function words
- `numbers_and_misc.txt` - Numbers and miscellaneous terms
- `prepositions.txt` - Prepositions and spatial words

### Core Files

- **`lapwing_base.tsv`** - Main reference dictionary with 114,867+ entries
- **`practice.tsv`** - Curated practice vocabulary (28 entries) for focused learning
- **`todo.org`** - Development notes and improvement ideas

## Dictionary Format

The dictionary files use TSV (Tab-Separated Values) format:
```
word	STENO_CHORD
```

For example:
```
I	EU
you	U
go	TKPWOE
make	PHAEUBG
```

## Usage

1. **For Practice**: Start with `practice.tsv` for focused vocabulary building
2. **By Category**: Use files in the `ready/` directory to focus on specific word types
3. **Complete Reference**: Use `lapwing_base.tsv` for comprehensive stenographic coverage

## Development Goals

The project aims to:

- Build custom Lapwing theory dictionaries that reduce conflicts
- Organize words by grammatical categories for systematic learning
- Develop consistent suffix and prefix patterns
- Create practice sets for efficient skill building

### Planned Improvements

- Standardize suffix patterns (e.g., `*Z` for plurals, `*S` for reflexives)
- Resolve dictionary conflicts and optimize chord choices
- Expand vocabulary coverage in specialized domains
- Create progressive difficulty practice sets

## Contributing

This is an active development project. Contributions, suggestions, and feedback on stenographic chord choices are welcome.

## File Statistics

- **Main Dictionary**: 114,867+ entries (`lapwing_base.tsv`)
- **Ready Dictionaries**: 8 categorized files
- **Under Construction**: 11 word list files
- **Practice Set**: 28 carefully selected entries

## License

This project contains stenographic dictionaries and educational materials for the Lapwing stenographic theory.