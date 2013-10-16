# Sorting with the UCA in Python

Sorting using the Unicode Collation Algorithm (UCA) is available with PyPi
package [PyICU](https://pypi.python.org/pypi/PyICU).

    from PyICU import Collator

    collator = Collator.createInstance()
    sorted = sorted(unsorted, cmp=collator.compare)

## Linguistic tailoring

The PyICU package also supports linguistic tailoring.

    from PyICU import Collator, Locale

    collator = Collator.createInstance(Locale('de'))
    sorted = sorted(unsorted, cmp=collator.compare)
