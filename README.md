# yalint(Yet Another Lint For Go)

We want to keep team code style consistent in Go, like:

* The const name MUST be all uppercase and split with the underscore
* First letter should be capitalized in the logging message
* First letter should NOT be capitalized in the error message
* Don't use `fmt.Print`
* append function MUST have the receiver

but none of linter is intended to solve this scenario, so yalint is born to do this.
