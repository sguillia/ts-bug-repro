# TS

```
git clone https://github.com/sguillia/ts-bug-repro
cd ts-bug-repro
tsc -p . # Ignore error about missing .d.ts
tsc -p .
```

```
error TS5055: Cannot write file '/home/user/ts-bug-repro/dist/main.d.ts' because it would overwrite input file.

Found 1 error.
```
