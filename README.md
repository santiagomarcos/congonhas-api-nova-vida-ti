# NovaVidaTI - API Consulta CPF e CNPJ.

## Requirements:
- PHP 7.0 (or higher)
- Composer

## Installation:

Follow the following steps:

```bash
composer install
```

## How To Use:

Open your browser and use the url to perform the data search.

```bash
http://you_url/api/?type=cpf&document=11111111111 - For CPF
http://you_url/api/?type=cnpj&document=11111111111111 - For CNPJ
```

## Configuration:

All sensible data configuration is located at config/config.php file , the file must be something like:
```ini
$user = "USUARIO";
$pass = "SENHA";
$customer = "CLIENTE";
```