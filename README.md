# API Performance Test Report

## Overview

This document provides a comprehensive overview of the performance testing conducted on the frequently used APIs of our test application. The tests were executed on server `000.000.000.00`.

## Test Scenarios

The following HTTP methods were tested:

- **POST Method**: Create new booking
- **GET Method**: Get booking with ID
- **POST Method**: Authentication for token
- **PUT Method**: Update booking info
- **DELETE Method**: Delete booking info

## Performance Test Summary

### Test Execution Details:

- **Server Address**: `000.000.000.00`
- **Test Environment**: [Describe the test environment]

### Test Results:

1. **1500 Concurrent Requests (1 Loop Count)**
   - Average TPS (Transactions Per Second) for Total Samples: ~125
   - Total Concurrent API Requests: 7500

2. **1600 Concurrent Requests (1 Loop Count)**
   - Average TPS for Total Samples: ~100
   - Total Concurrent API Requests: 8000

3. **1700 Concurrent Requests (1 Loop Count)**
   - Average TPS for Total Samples: ~95
   - Total Concurrent API Requests: 8500

4. **1800 Concurrent Requests (1 Loop Count)**
   - Average TPS for Total Samples: ~98
   - Total Concurrent API Requests: 9000
   - Notable Findings: 42 requests experienced connection timeouts, resulting in an error rate of 0.47%.

5. **1850 Concurrent Requests (1 Loop Count)**
   - Average TPS for Total Samples: ~61
   - Total Concurrent API Requests: 9250

### Conclusion:

- The server is capable of handling nearly 9100 concurrent API calls with almost zero (0%) error rate.

## Additional Information

- For detailed test results and analysis, please refer to the attached report.
- If you have any further queries or require additional details, feel free to contact us.

---

*This report is generated based on the performance tests conducted on [Date]. Results may vary based on network conditions and server configurations.*
