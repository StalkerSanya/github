# Robo GitHub

Run GitHub commands from the Robo task runner.

### Getting Started

First, you'll need to download the Robo GibHub library using composer:

```bash
composer require droath/robo-github
```

Next, you'll need to create a personal access token on GitHub so you have access to your private repositories via a Robo task. Follow this [GitHub guide](https://help.github.com/articles/creating-a-personal-access-token-for-the-command-line/) to obtain your access token.

```php
<?php
    $token = 'OJuJcqaYiX5uL72Ky';
    $account = 'droath';
    $repository = 'robo-github';

    $response = $this
        ->taskGitHubIssueAssignees($token, $account, $repository)
        ...
        ...
        ->run();

    var_dump($response);
    ```
I am Master. I am Major programer

You are rab 1. And You are not major 

You are rab 2. And You are not major

You are rab 3. And You are not major
