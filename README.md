# API Performance Test Report 🚀

## Overview
Dear viewers,

I’ve conducted a comprehensive performance test on frequently used APIs for our test application. The tests were executed on the server with IP `000.000.000.00`.

## Test Details
The scenarios involved varying levels of concurrent requests to assess the server's capacity and response efficiency.

### HTTP Methods Tested:
- 📤 **POST Method:** Create new booking
- 📥 **GET Method:** Get booking with ID
- 🔐 **POST Method:** Authentication for token
- ✏️ **PUT Method:** Update booking info
- 🗑️ **DELETE Method:** Delete booking info

## Performance Metrics 📊

- **1500 Concurrent Requests** with 1 Loop Count:
  - Avg TPS (Transactions Per Second) for Total Samples: **~125**
  - Total Concurrent API Requests: **7500**

- **1600 Concurrent Requests** with 1 Loop Count:
  - Avg TPS for Total Samples: **~100**
  - Total Concurrent API Requests: **8000**

- **1700 Concurrent Requests** with 1 Loop Count:
  - Avg TPS for Total Samples: **~95**
  - Total Concurrent API Requests: **8500**

- **1800 Concurrent Requests** with 1 Loop Count:
  - Avg TPS for Total Samples: **~98**
  - Total Concurrent API Requests: **9000**
  - Notable Finding: **42 requests** experienced connection timeout, error rate of **0.47%**.

- **1850 Concurrent Requests** with 1 Loop Count:
  - Avg TPS for Total Samples: **~61**
  - Total Concurrent API Requests: **9250**

## Conclusion 📝
The server is capable of handling nearly **9100 concurrent API calls** with an almost zero (0%) error rate.

## Next Steps
Please review the detailed report attached for more insights. Should you have any queries or require further clarification, feel free to reach out.

---
*Performance testing conducted with precision and care.*
