
# 5dive Plugin Hello

A minimal example plugin for 5dive. It adds one skill that prints a greeting.

Run the greeting without installing:

```sh
bash hello/skills/hello/scripts/hello.sh
```

```text
Hello from 5dive.
```

The plugin format is in the [Plugins section of the 5dive README](https://github.com/5dive-ai/5dive/blob/main/README.md#plugins).

Passes `claude plugin validate`. Its one warning is the `fivedive` block, which 5dive requires and Claude Code ignores.
