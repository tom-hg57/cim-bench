# Benchmark Report

**Generated from**: `results-docker/libcimpp_realgrid_benchmark.json`

## Environment

- **CPU**: 11th Gen Intel(R) Core(TM) i7-11850H @ 2.50GHz
- **Cores**: 4
- **Python**: 3.14.6
- **System**: Linux 6.8.0-146-generic

## Results

### Libcimpp Load Realgrid

- **Mean time**: 4.86 s
- **Min time**: 4.74 s
- **Max time**: 4.95 s
- **Std dev**: 83.6 ms
- **Rounds**: 5

**Metrics**:
- Memory Mb: 132.3
- Lines: 7561
- Generators: 1347
- Loads: 6687
- Substations: 4875
- Dataset Size Mb: 86.5
- Cgmes Version: 2.4.15
- Library: libcimpp
- Library Version: 2.3.1
- Library Dependencies: {}
- Dataset: realgrid
- Display Name: libcimpp
- Color: #000000
- Tags: ['parser', 'query', 'typed-model', 'c++']

### Libcimpp Get Lines

- **Mean time**: 12.6 ms
- **Min time**: 11.4 ms
- **Max time**: 14.3 ms
- **Std dev**: 688.0 μs
- **Rounds**: 73

**Metrics**:
- Line Count: 7561
- Query Type: get_lines
- Library: libcimpp
- Dataset: realgrid
- Display Name: libcimpp
- Color: #000000

### Libcimpp Get Generators

- **Mean time**: 13.5 ms
- **Min time**: 11.6 ms
- **Max time**: 16.0 ms
- **Std dev**: 1.1 ms
- **Rounds**: 81

**Metrics**:
- Generator Count: 1347
- Query Type: get_generators
- Library: libcimpp
- Dataset: realgrid
- Display Name: libcimpp
- Color: #000000

### Libcimpp Get Loads

- **Mean time**: 24.4 ms
- **Min time**: 23.5 ms
- **Max time**: 26.1 ms
- **Std dev**: 547.7 μs
- **Rounds**: 40

**Metrics**:
- Load Count: 6687
- Query Type: get_loads
- Library: libcimpp
- Dataset: realgrid
- Display Name: libcimpp
- Color: #000000

### Libcimpp Get Substations

- **Mean time**: 13.4 ms
- **Min time**: 12.2 ms
- **Max time**: 15.6 ms
- **Std dev**: 802.3 μs
- **Rounds**: 73

**Metrics**:
- Substation Count: 4875
- Query Type: get_substations
- Library: libcimpp
- Dataset: realgrid
- Display Name: libcimpp
- Color: #000000
