<h1 align="center">Welcome to Wily's Laravel Playground 👋</h1>
<br>

## About this playground

I make this repository for learning purpose and proof of concept for certain features. Feel free to request other feature to be documented here.

## Prerequisites

-   **[Docker](https://www.docker.com/)**

## Install

1. Setup **[Laravel Sail](https://laravel.com/docs/10.x/sail#installing-sail-into-existing-applications)**
2. Start the containers on the background:

    ```sh
    sail up -d
    ```

3. To make sure each container were running smoothly, run `sail ps` or view it on your Docker Desktop that you installed (optional)

## Playground's Features

1. PHP (8.2)
2. **[MySQL](https://hub.docker.com/_/mysql)** (8.0)
3. **[Redis](https://hub.docker.com/_/redis)** (alpine)
4. **[phpMyAdmin](https://hub.docker.com/_/phpmyadmin)** (latest)
5. **[Mailpit](https://hub.docker.com/r/axllent/mailpit)** (latest)

## Main Project Usage

1. Access http://localhost

## phpMyAdmin Usage

1. Access http://localhost:8080

## Mailpit Usage

1. Access http://localhost:8025, the inbox should be empty at first
2. Run in terminal

    ```sh
    sail artisan test-email
    ```

3. Check the inbox again at http://localhost:8025

## Feedbacks

If you discover any better practices or mistake, please send an e-email to [Wilyanto](mailto:wilyanto.dev@gmail.com).
