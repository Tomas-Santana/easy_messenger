# easy_messenger
The simplest Instagram/Facebook API wrapper out there.

## Installation
```bash
pip install easy_messenger
```

## Usage
```python
from easy_messenger import Instagram

instagram = Instagram(access_token="YOUR_PAGE_ACCESS_TOKEN", version="v17.0")

# send a message
instagram.send_message(
    recipient_id="USER_IGSID",
    message="Hello World!"
)
```

## License
MIT
