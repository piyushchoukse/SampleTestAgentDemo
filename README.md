# SampleTestAgentDemo
Sample android project to be created for doing unit testing with Agentic approach

## Test Strategy Options

| Option | Test types | Estimated coverage | Effort | Critical paths |
|---|---|---:|---|---|
| Minimal | Unit tests only | 80%+ business logic | Low | Arithmetic operation correctness and overflow |
| Standard | Unit + integration-like flow tests | 80%+ logic, 70%+ flow layer | Medium | Logic correctness + formatting flow from logic to UI model |
| Comprehensive | Unit + integration + Android UI instrumentation | 80%+ logic, 70%+ ViewModel, 60%+ UI | High | End-to-end UI interaction and rendering |

Selected approach in this repository: **Standard** (smallest viable change with current non-Android scaffold).

## Implemented Example

- Mathematical operation: `2 + 2 = 4`
- Logic class: `Calculator.add(first, second)`
- UI layer formatting class: `CalculatorUiModel.renderAddition(first, second)`

## Run Tests

```bash
./gradlew test
```
