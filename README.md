# RISK

Artifact implementing:

1. Modeling 
2. Trace analysis 
3. TLTR
4. vPLC-style deterministic execution
5. Recovery classification 

## Build
```bash
dotnet restore RISK.sln
dotnet build RISK.sln -c Release
dotnet test RISK.sln -c Release
```

## Run
```bash
dotnet run --project src/RISK.Cli -- --out artifacts/run1
```


## .NET Dependencies

### Required SDK
- **.NET SDK 8.0** (or newer 8.x)

Check installed version:
```bash
dotnet --version
