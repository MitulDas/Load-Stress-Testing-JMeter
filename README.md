# Performance Test Report for Test App API 🚀

## API Methods Overview 🌐
- `POST` Method: Create a new booking
- `GET` Method: Get booking with id
- `POST` Method: Authentication for token
- `PUT` Method: Update booking info
- `DELETE` Method: Delete booking info

---

📢 **Dear Viewers,**

I’ve completed a comprehensive performance test on frequently used APIs for the Test App. These tests were conducted on the server with IP `000.000.000.00`.

### Test Scenarios and Result📊

> 🔹 **1500 Concurrent Requests**
> - **Loop Count:** 1
> - **Average TPS:** ~125
> - **Total Concurrent API Requests:** 7500

> 🔹 **1600 Concurrent Requests**
> - **Loop Count:** 1
> - **Average TPS:** ~100
> - **Total Concurrent API Requests:** 8000

> 🔹 **1700 Concurrent Requests**
> - **Loop Count:** 1
> - **Average TPS:** ~95
> - **Total Concurrent API Requests:** 8500

> 🔹 **1800 Concurrent Requests**
> - **Loop Count:** 1
> - **Average TPS:** ~98
> - **Total Concurrent API Requests:** 9000
> - **Observation:** 42 requests experienced connection timeout, resulting in an error rate of 0.47%.

> 🔹 **1850 Concurrent Requests**
> - **Loop Count:** 1
> - **Average TPS:** ~61
> - **Total Concurrent API Requests:** 9250

### Summary and Conclusion 📝

- The server can handle approximately 9100 concurrent API calls with an almost zero (0) error rate.
- The optimal performance was observed at 1800 concurrent requests, with minimal error rates.

---

📎 **Attached Details**
Please find the detailed report in the attachment for an in-depth analysis. Should you have any further queries, feel free to reach out.

---
