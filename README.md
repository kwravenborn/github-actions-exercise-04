# Hello world docker

This action prints "Hello World"

## Inputs

## `who-to-greet`
**Required** The name of the person to greet. Default `"World"`.

## Outputs

## `time`

The time we greeted you

## Example usage
uses: actions/hello-world-docker-action@v1
with:
    who-to-greet: 'Mona the Octocat'