You can concat all the pdf files in the current directory using the following command.

```
"/System/Library/Automator/Combine PDF Pages.action/Contents/Resources/join.py" -o ./combined-document.pdf ./*pdf
```

***I have aliased `"/System/Library/Automator/Combine PDF Pages.action/Contents/Resources/join.py"` to `pdfconcat`***

***Note*** May have to use `source ~/.bash_profile` to persist aliases and actually make the `pdfconcat` command available
