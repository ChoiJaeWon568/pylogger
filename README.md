# pylogger
Pretty Logger for Python from repository at "https://github.com/cueo/pylogger"

# Download
```
curl https://raw.githubusercontent.com/ChoiJaeWon568/pylogger/main/log.py -o utils/log.py

mkdir -p utils; curl https://raw.githubusercontent.com/ChoiJaeWon568/pylogger/main/log.py -o utils/log.py
```

# Usage
```python
from log import get_logger

logger = get_logger(__name__)

logger.info('This is an info log.')
logger.warning('This is a warning log.')
logger.error('This is an error log.')
```

## Result
<img width="817" alt="image" src="https://user-images.githubusercontent.com/13873846/181698620-72489b61-454c-4360-be74-65a57953d61e.png">
