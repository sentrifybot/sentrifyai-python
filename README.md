# SentrifyAI Python Package

SentrifyAI is a Python package that provides a client for interacting with the SentrifyAI API.

## Installation

You can install the package via pip:

```
pip install sentrifyai
```

## Usage

```
from sentrifyai import api
import json

emotions = api.Emotions()

results = emotions.emotion(model_slug='Emotion-1.0', message='This is a sample message.')

json_results = json.dumps(results, indent=4)

print(json_results)
```

## Documentation

For more detailed usage instructions and API reference, please refer to the [documentation](https://github.com/sentrifybot/sentrifyai-python).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
