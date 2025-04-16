# Kiota bug

## Command used

```sh
kiota generate -l CSharp -d ./openapi.json --exclude-backward-compatible --clean-output
```

## Generated bug location

[FileInfoInput.cs#L31](./output/Models/FilesInfoInput.cs#L31)
