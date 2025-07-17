# checkde
Its a very basic project of playwright and nodejs to check the status of a website.
# Installation
```bash
npm install
```
# Usage
```bash
npm run check
```
# Configuration
You can configure the website to check in the `config.json` file. The default configuration is
```json
{
  "url": "https://example.com",
    "timeout": 5000,
    "retry": 3,
    "retryDelay": 1000,
    "outputFile": "output.txt"
}
```
# Output
The output will be written to the `output.txt` file. The output will be in the following format:
```
Website: https://example.com
Status: UP
Response Time: 123ms
```
If the website is down, the output will be:
```
Website: https://example.com
Status: DOWN

Response Time: N/A
```
# License
This project is licensed under the MIT License - see the [LICENSE]{Harmeet} file for details
# Contributing
Contributions are welcome! Please open an issue or submit a pull request.
# Author
This project is maintained by [Harmeet](
    