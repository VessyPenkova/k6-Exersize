# k6 Performance Testing Exercises

A collection of educational performance-testing scripts written in **JavaScript using Grafana k6**.

## Technologies
- JavaScript
- Grafana k6
- HTTP testing

## Test Scenarios

- **Smoke Testing** — Basic application availability under minimal load.
- **Load Testing** — Simulating increasing numbers of virtual users.
- **Spike Testing** — Testing sudden increases in traffic.
- **Soak Testing** — Exploring sustained traffic over an extended period.
- **Breakpoint Testing** — Experimenting with high virtual-user counts.
- **Response Checks** — Validating HTTP status codes and response content.
- **Performance Thresholds** — Defining acceptable response times and failure rates.

## Running the Tests

Install [Grafana k6](https://grafana.com/docs/k6/latest/set-up/install-k6/) and run a script:

```bash
k6 run 0.first_script.js
```

Most examples use the public demonstration website `https://test.k6.io`.

## Purpose

These exercises demonstrate foundational performance-testing concepts, including virtual users, load stages, response validation and performance metrics.

**Note:** This is an educational repository. Some scripts may require corrections before execution, and the configured load levels should not be used against systems without permission.
  
  ![alt text](https://github.com/VessyPenkova/k6-Exersize/blob/main/0.png)
  ![alt text](https://github.com/VessyPenkova/k6-Exersize/blob/main/1.png)
  ![alt text](https://github.com/VessyPenkova/k6-Exersize/blob/main/2.png)
  ![alt text](https://github.com/VessyPenkova/k6-Exersize/blob/main/3.png)
  ![alt text](https://github.com/VessyPenkova/k6-Exersize/blob/main/4.png)
  ![alt text](https://github.com/VessyPenkova/k6-Exersize/blob/main/5.png)
  ![alt text](https://github.com/VessyPenkova/k6-Exersize/blob/main/6.png)
