# Hyperfine

% Hyperfine - Command-Line Benchmarking Tool

## Basic Command Comparison
#plateform/linux,macos,windows #target/local #cat/UTILITY/BENCHMARKING/
```
hyperfine '<command_1>' '<command_2>'
```

## Benchmark with Warmup Runs
#plateform/linux,macos,windows #target/local #cat/UTILITY/BENCHMARKING/
```
hyperfine --warmup <N> '<command>'
```

## Set Minimum/Maximum Runs
#plateform/linux,macos,windows #target/local #cat/UTILITY/BENCHMARKING/
```
hyperfine --min-runs <N> --max-runs <M> '<command>'
```

## Set Exact Number of Runs
#plateform/linux,macos,windows #target/local #cat/UTILITY/BENCHMARKING/
```
hyperfine --runs <N> '<command>'
```

## Use Setup and Cleanup Commands
#plateform/linux,macos,windows #target/local #cat/UTILITY/BENCHMARKING/
```
hyperfine --setup '<setup_cmd>' --cleanup '<cleanup_cmd>' '<benchmark_cmd>'
```

## Parameter Scan
#plateform/linux,macos,windows #target/local #cat/UTILITY/BENCHMARKING/
```
hyperfine --parameter-scan <VAR_NAME> <MIN_VALUE> <MAX_VALUE> '<command_using_{VAR_NAME}>'
```

## Parameter Scan with Step Size
#plateform/linux,macos,windows #target/local #cat/UTILITY/BENCHMARKING/
```
hyperfine --parameter-scan <VAR> <MIN> <MAX> --parameter-step-size <STEP> '<command_using_{VAR}>'
```

## Ignore Command Failures
#plateform/linux,macos,windows #target/local #cat/UTILITY/BENCHMARKING/
```
hyperfine --ignore-failure '<potentially_failing_cmd>' '<stable_cmd>'
```

## Show Command Output
#plateform/linux,macos,windows #target/local #cat/UTILITY/BENCHMARKING/
```
hyperfine --show-output '<command_with_output>'
```

## Export Results Markdown (JSON, CSV)
#plateform/linux,macos,windows #target/local #cat/UTILITY/BENCHMARKING/
```
hyperfine --export-markdown <report.md> '<command1>' '<command2>'
```

## Change Output Style
#plateform/linux,macos,windows #target/local #cat/UTILITY/BENCHMARKING/
```
hyperfine --style <basic|full|color|nocolor|none> '<command>'
```
