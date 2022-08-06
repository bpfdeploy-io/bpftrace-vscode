<div align="center">
  <img src="https://raw.github.com/bpfdeploy-io/bpftrace-vscode/master/assets/header.png" />
  <br>
  <h2>VS Code extension for bpftrace</h2>
</div>

The goal of this plugin is to aid eBPF developers with their bpftrace scripts from their VS Code environment.
Use this with your favorite VS Code theme!

We have started with syntax highlighting, but we aim to add more features that leverage VS Code's plugin API.
If you have any ideas, please let us know!

Syntax highlight features:

- Understands probes and predicates
- Labels bpftrace builtins
- Highlights escape sequences within strings

<!-- Link to plugin page -->

<!-- Image to syntax highlighting example -->

## Installation

You can search directly for "bpftrace" in the [Visual Studio Marketplace](https://marketplace.visualstudio.com/) or install directly through your command line:

```shell
$ ext install bpfdeploy.bpftrace
```

## Contributing

The possibilities are endless with VS Code extensions so we encourage all ideas and contributions.

Bug reports may be filed on our [Github issue tracker](https://github.com/bpfdeploy-io/bpftrace-vscode/issues).

## Testing

Our testing strategy is currently [manual](https://github.com/bpfdeploy-io/bpftrace-vscode/issues/1), unfortunately.

The official bpftrace repo contains a set of tools that we confirm our changes against as we make changes.
We have added a git submodule of the version of the bptrace repo we have tested our latest changes on.

If you see an issue, please send us the bpftrace script if possible so we can add it in our test cases!

## License

In alignment with bpftrace, we've licensed this plugin under the Apache License, Version 2.0.

[https://www.apache.org/licenses/LICENSE-2.0](https://www.apache.org/licenses/LICENSE-2.0)

## Acknowledgements

We want to say thank you to the [bpftrace](https://github.com/iovisor/bpftrace) community for providing the high-level tracing tool and continuing to keep their documentation up to date.

Maintained by [bpfdeploy.io](https://bpfdeploy.io)