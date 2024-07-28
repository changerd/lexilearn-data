# LexiLearn Vocabulary Data

This repository contains the vocabulary data used by the LexiLearn application. The vocabulary sets are stored in a JSON file, categorized by levels and themes.

## JSON Structure

The JSON file follows this structure:

```json
[
  {
    "name": "Vocabulary Set Name",
    "level": "Level Name",
    "theme": "Theme Name",
    "words": [
      { "word": "english_word", "translations": ["translation1", "translation2"] }
    ]
  }
]
```

## Usage

### Synchronization

The LexiLearn application can synchronize its local vocabulary data with the JSON file in this repository. This ensures that users always have the latest vocabulary sets available.

### Adding New Vocabulary Sets

1. Fork the repository.
2. Update the vocabulary.json file with the new vocabulary sets.
3. Submit a pull request with your changes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.
