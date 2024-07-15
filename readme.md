## RUST BASIC


## INSTALL
```
curl https://sh.rustup.rs -sSf | sh
```

## CREATE PROJECT

```
cargo new rust_basic 
```

## RUN 
```
cargo build
```

### lunch.json
```
{
    // Use IntelliSense to learn about possible attributes.
    // Hover to view descriptions of existing attributes.
    // For more information, visit: https://go.microsoft.com/fwlink/?linkid=830387
    "version": "0.2.0",
    "configurations": [
        {
            "type": "lldb",
            "request": "launch",
            "name": "Debug",
            "program": "${workspaceFolder}/target/debug/rust_basic",
            "args": [],
            "cwd": "${workspaceFolder}"
        }
    ]
}

```