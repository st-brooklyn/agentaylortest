[logo]: https://cdn.recast.ai/brand/recast-ai-logo-inline.png "Recast.AI"

![alt text][logo]

# Recast.AI - SDK PHP
Recast.AI official SDK in PHP

## Synospis

This module is a wrapper around the [Recast.AI](https://recast.ai) API, and allows you to:
* [Analyse your text](https://github.com/RecastAI/SDK-PHP/wiki/01---Analyse-text)
* [Manage your conversation](https://github.com/RecastAI/SDK-PHP/wiki/02---Manage-conversation)
* [Receive and send messages](https://github.com/RecastAI/SDK-PHP/wiki/03--Receive-and-send-messages)


## Installation

Install the package using npm, as shown below:
```bash
composer require recastai/sdk-php
```

You can now use the sdk in your code.

Using the entire SDK:
```php
<?php
require_once __DIR__ . '/vendor/autoload.php';

use RecastAI\Client;

$client = new Client('YOUR_TOKEN');
```

Extracting one single API:
```php
<?php
require_once __DIR__ . '/vendor/autoload.php';

use RecastAI\Client;

$request = Client::Request('YOUR_TOKEN');
$connect = Client::Connect('YOUR_TOKEN');
```

## More

You can view the whole API reference at [man.recast.ai](https://man.recast.ai).

## Author

Marian André, marian.andre@recast.ai

You can follow us on Twitter at [@recastai](https://twitter.com/recastai) for updates and releases.

## License

Copyright (c) [2017] [Recast.AI](https://recast.ai)

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
