# Example Of Use Golang Package fixedwidth
## Infer Column Widths of a Fixed-Width Text File
A fixed-width file use a fixed column width for each column (though not all columns necessarily have the same width) and pads the remaining space on the left or on the right, usually with spaces:

```
   287540 Smith  Jones  Accountant         $55,000
   204878 Ross   Betsy  Senior Accountant  $66,000
   208417 Arthur Wilbur CEO               $123,000
```

---
This example use golang package [github.com/davidburil/fixedwidth](https://github.com/davidburil/fixedwidth)