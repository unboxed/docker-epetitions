# UK Government and Parliament Petitions Docker Image

Docker image for the [alphagov/e-petitions][1] repository.


# Usage

In your `docker-compose.yml` file:

``` yaml
services
  web:
    image: unboxed/epetitions
    ports:
      - "3000:3000"
```

# License

MIT License - please see the project LICENSE file for details.

[1]: https://github.com/alphagov/e-petitions
