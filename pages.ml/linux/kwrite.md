# kwrite

> KDE ഡെസ്ക്ടോപ് പ്രോജക്ടിന്റെ ടെക്സ്റ്റ് എഡിറ്റർ.
> കാണുക `kate`.
> കൂടുതൽ വിവരങ്ങൾ: <https://docs.kde.org/stable5/en/kate/kwrite/command-line-options.html>.

- ഒരു ടെക്സ്റ്റ് ഫയൽ ഓപ്പൺ ചെയ്യുവാൻ:

`kwrite {{ഫയലിലേക്കുള്ള/പാത}}`

- ഒന്നിൽ കൂടുതൽ ഫയലുകൾ ഓപ്പൺ ചെയ്യുവാൻ:

`kwrite {{ഫയൽ1 ഫയൽ2 ...}}`

- ഒരു പ്രത്യേക എൻകോഡിങ്ങിൽ ഫയൽ ഓപ്പൺ ചെയ്യുവാൻ:

`kwrite --encoding {{UTF-8}} {{ഫയലിലേക്കുള്ള/പാത}}`

- ഒരു ടെക്സ്റ്റ് ഫയലിന്റെ ആവശ്യമുള്ള ലൈനിലേക്കും കോളത്തിലേക്കും നാവിഗേറ്റ് ചെയ്യുവാൻ:

`kwrite --line {{ലൈൻ_നമ്പർ}} --column {{കോളം_നമ്പർ}} {{ഫയലിലേക്കുള്ള/പാത}}`
