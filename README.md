# XSS-Fury
Automatically check your endpoints to see if they are vulnerable to XSS injections.

## Usage:
```bash
git clone https://github.com/ism8el/XSS-Fury.git
cd XSS-Fury/
chmod +x ./XSS-Fury.py
cat endpoints.txt | ./XSS-Fury.py
```

## Example:
### On a single endpoints:
```bash
echo "https://example.com/?message=hello" | ./XSS-Fury.py
```

### On bulk endpoints:
```bash
cat endpoints.txt | ./XSS-Fury.py
```

## Screenshot:
![Screenshot](/image.png "Screenshot").
