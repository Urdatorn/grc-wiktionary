# grc-wiktionary

This git aims to make easily machine-accessible the roughly 40k entries in Ancient Greek (grc) Wiktionary.

Titles were extracted from the dump ```enwiktionary-latest-pages-articles.xml.bz2``` dated 6 november 2024, filtering for pages with ```==Ancient Greek==```. All such pages are saved in ```grc.xml```. Full articles scraped on 13-14 november 2024 and saved to the ```htmls``` folder.

For the latest title dump, always refer to https://dumps.wikimedia.org/enwiktionary/latest/
Information about the Wiktionary dumps is found at https://en.wiktionary.org/wiki/User:Amgine/Wiktionary_data_%26_API


Since the modules grc-decl and grc-conj are are only called but not loaded in the dump pages, all pages needed to be dynamically scraped to include full conjugation and declination information. 