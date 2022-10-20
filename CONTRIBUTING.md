# Contribution Guidelines

Whether reporting bugs, discussing improvements and new word:
Contributions to it-gasy-dictionary are welcome! Here's how to get started:

1. Check for open issues or open a fresh issue to start a discussion around
   a feature idea or a bug
2. Fork `the repository <https://github.com/julkwel/it-gasy-dictionary/>`_ on GitHub
   and start making your changes
3. Send a pull request and bug the maintainer until it gets merged and
   published :)

## Code Conventions

it-gasy-dictionary follow this pattern for a word:

```json
  {
    "teny": "<word>",
    "valiny": [
      {
        "dikany": "<description>",
        "ilaivanaAzy": "<utiity example>",
        "heviny": {
          "en": "<english translation>",
          "fr": "<french translation>"
        }
      }
    ]
  },
```

If there is more than one meaning:

```json
  {
    "teny": "<word>",
    "valiny": [
      {  // first meaning
        "dikany": "<description>",
        "ilaivanaAzy": "<utiity example>",
        "heviny": {
          "en": "<english translation>",
          "fr": "<french translation>"
        }
      },
      {  // second meaning
        "dikany": "<description>",
        "ilaivanaAzy": "<utiity example>",
        "heviny": {
          "en": "<english translation>",
          "fr": "<french translation>"
        }
      },
      {  // third meaning
        "dikany": "<description>",
        "ilaivanaAzy": "<utiity example>",
        "heviny": {
          "en": "<english translation>",
          "fr": "<french translation>"
        }
      }
    ]
  },
```

* Indentation: 2 space
* Sorted [A-Z] by value of key `"teny"`
