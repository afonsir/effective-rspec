# Commands

- To show the 2 slowest tests:

```bash
rspec --profile 2
```

- To re-run only failed specs:

```bash
rspec --only-failures
```

- To run just the focused specs, without configuring RSpec to do so by default:

```bash
rspec --tag focus
```
