# PHP Snippets for Zed IDE

A collection of PHP 8+ snippets for the [Zed IDE](https://zed.dev) to improve your development speed and productivity.

## Features

This extension provides a comprehensive set of snippets for modern PHP (PHP 8+), including:

* Array and data structure helpers
* Control structures (if, switch, loops)
* Function and class templates
* Object-oriented patterns (interfaces, enums, constructors)
* Error handling utilities
* Common PHP helpers and utilities

## Installation

### Method 1

1. Go to Extensions menu in Zed IDE
2. Search for "php snippets"
3. Click "Install"

### Method 2

1. Clone this repo:

```
git clone https://github.com/tejasashinde/php-zed-snippets
```

2. Go to `Extensions` menu in Zed IDE
3. Click `Install Dev Extension`
4. Select the folder you cloned

## Usage

To make snippets appear at the top of the completion list in Zed, add this setting to your Zed settings file:

```json
{
    "snippet_sort_order": "top"
}
```

Start typing the snippet prefix (e.g., `php-fn`) in a PHP file and press `Tab` to expand the snippet.

## Available Snippets

| Prefix            | Description                         |
| ----------------- | ----------------------------------- |
| `php-array`       | Array short syntax                  |
| `php-arraykv`     | Associative array                   |
| `php-dowhile`     | Do-while loop                       |
| `php-enum`        | Enum definition (PHP 8.1+)          |
| `php-exit`        | Exit script                         |
| `php-file-ns`     | PHP file with namespace             |
| `php-if`          | If statement                        |
| `php-ifelse`      | If-else statement                   |
| `php-switch`      | Switch statement                    |
| `php-interface`   | Interface definition                |
| `php-fn`          | Function definition                 |
| `php-pubfn`       | Public function definition          |
| `php-prifn`       | Private function definition         |
| `php-constfn`     | Constructor with property promotion |
| `php-redirect`    | HTTP redirect                       |
| `php-requireonce` | Require once                        |
| `php-isset`       | isset() function                    |
| `php-empty`       | empty() function                    |
| `php-count`       | count() function                    |
| `php-trycatch`    | Try-catch block                     |
| `php-ternary`     | Ternary operator                    |
| `php-while`       | While loop                          |
| `php-fl`          | For loop                            |
| `php-fekv`        | Foreach key => value loop           |
| `php-class`       | PHP class                           |
| `php-absclass`    | Abstract class                      |
| `php-use`         | Use statement                       |
| `php-pubsf`       | Public static function              |
| `php-prisf`       | Private static function             |
| `php-prosf`       | Protected static function           |
| `php-comment-blk` | Simple comment block                |

## Example of Snippets

### Function definition

Type `php-fn` and press Tab:

```php
function name(mixed $param): void {
    // Your code here
}
```

---

### If statement

Type `php-if` and press Tab:

```php
if ($condition) {
    // Your code here
}
```

---

---

### Constructor with property promotion

Type `php-constfn` and press Tab:

```php
public function __construct(
    private readonly ?Type $var = null
) {
    // Your code here
}
```

---

### Foreach loop

Type `php-fekv` and press Tab:

```php
foreach ($items as $key => $value) {
    // Your code here
}
```

---

### Try-catch block

Type `php-trycatch` and press Tab:

```php
try {
    // Your code here
} catch (\Throwable $e) {
    echo $e->getMessage();
}
```

---

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/my-amazing-feature`)
3. Commit your changes (`git commit -m 'Add my amazing feature'`)
4. Push to the branch (`git push origin feature/my-amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the GNU General Public License v3.0 - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

This extension is inspired by community-driven snippet collections and aims to provide a clean, modern PHP development experience in Zed IDE.