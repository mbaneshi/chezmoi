# `promptStringOnce` *map* *key* *prompt* [*default*]

`promptStringOnce` returns *map*.*key* if it exists and is an string value,
otherwise it prompts the user for a string value with *prompt* and an optional
*default* using `promptString`.

!!! example

    ```
    {{ $email := promptStringOnce . "email" "What is your email address" }}
    ```
