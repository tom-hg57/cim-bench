# Benchmark Report

**Generated from**: `results-docker/libcimpp_svedala_benchmark.json`

## Environment

- **CPU**: 11th Gen Intel(R) Core(TM) i7-11850H @ 2.50GHz
- **Cores**: 4
- **Python**: 3.14.6
- **System**: Linux 6.8.0-146-generic

## Results

### Libcimpp Load Svedala

- **Mean time**: 136.8 ms
- **Min time**: 134.8 ms
- **Max time**: 140.1 ms
- **Std dev**: 1.6 ms
- **Rounds**: 8

**Metrics**:
- Memory Mb: 9.5
- Lines: 97
- Generators: 39
- Loads: 73
- Substations: 57
- Dataset Size Mb: 7.3
- Cgmes Version: 3.0
- Library: libcimpp
- Library Version: 2.3.1
- Library Dependencies: {}
- Dataset: svedala
- Display Name: libcimpp
- Color: #000000
- Tags: ['parser', 'query', 'typed-model', 'c++']

### Libcimpp Get Lines

- **Mean time**: 413.9 μs
- **Min time**: 369.4 μs
- **Max time**: 1.3 ms
- **Std dev**: 34.4 μs
- **Rounds**: 2310

**Metrics**:
- Line Count: 97
- Query Type: get_lines
- Library: libcimpp
- Dataset: svedala
- Display Name: libcimpp
- Color: #000000

### Libcimpp Get Generators

- **Mean time**: 423.2 μs
- **Min time**: 350.5 μs
- **Max time**: 1.6 ms
- **Std dev**: 57.1 μs
- **Rounds**: 2370

**Metrics**:
- Generator Count: 39
- Query Type: get_generators
- Library: libcimpp
- Dataset: svedala
- Display Name: libcimpp
- Color: #000000

### Libcimpp Get Loads

- **Mean time**: 1.2 ms
- **Min time**: 1.1 ms
- **Max time**: 2.1 ms
- **Std dev**: 63.7 μs
- **Rounds**: 880

**Metrics**:
- Load Count: 73
- Query Type: get_loads
- Library: libcimpp
- Dataset: svedala
- Display Name: libcimpp
- Color: #000000

### Libcimpp Get Substations

- **Mean time**: 421.8 μs
- **Min time**: 353.4 μs
- **Max time**: 1.2 ms
- **Std dev**: 31.9 μs
- **Rounds**: 2393

**Metrics**:
- Substation Count: 57
- Query Type: get_substations
- Library: libcimpp
- Dataset: svedala
- Display Name: libcimpp
- Color: #000000
