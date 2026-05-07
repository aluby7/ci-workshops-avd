# ANTA Report

**Table of Contents:**

- [ANTA Report](#anta-report)
  - [Test Results Summary](#test-results-summary)
    - [Summary Totals](#summary-totals)
    - [Summary Totals Device Under Test](#summary-totals-device-under-test)
    - [Summary Totals Per Category](#summary-totals-per-category)
  - [Test Results](#test-results)

## Test Results Summary

### Summary Totals

| Total Tests | Total Tests Success | Total Tests Skipped | Total Tests Failure | Total Tests Error |
| ----------- | ------------------- | ------------------- | ------------------- | ------------------|
| 22 | 0 | 0 | 22 | 0 |

### Summary Totals Device Under Test

| Device Under Test | Total Tests | Tests Success | Tests Skipped | Tests Failure | Tests Error | Categories Skipped | Categories Failed |
| ------------------| ----------- | ------------- | ------------- | ------------- | ----------- | -------------------| ------------------|
| s1-brdr1 | 3 | 0 | 0 | 3 | 0 | - | System |
| s1-brdr2 | 3 | 0 | 0 | 3 | 0 | - | System |
| s1-leaf1 | 3 | 0 | 0 | 3 | 0 | - | System |
| s1-leaf2 | 3 | 0 | 0 | 3 | 0 | - | System |
| s1-leaf3 | 2 | 0 | 0 | 2 | 0 | - | System |
| s1-leaf4 | 2 | 0 | 0 | 2 | 0 | - | System |
| s1-spine1 | 3 | 0 | 0 | 3 | 0 | - | System |
| s1-spine2 | 3 | 0 | 0 | 3 | 0 | - | System |

### Summary Totals Per Category

| Test Category | Total Tests | Tests Success | Tests Skipped | Tests Failure | Tests Error |
| ------------- | ----------- | ------------- | ------------- | ------------- | ----------- |
| System | 22 | 0 | 0 | 22 | 0 |

## Test Results

| Device Under Test | Categories | Test | Description | Custom Field | Result | Messages |
| ----------------- | ---------- | ---- | ----------- | ------------ | ------ | -------- |
| s1-brdr1 | System | VerifyCPUUtilization | Verifies whether the CPU utilization is below 75%. | - | failure | Device has reported a high CPU utilization -  Expected: < 75% Actual: 97.0% |
| s1-brdr1 | System | VerifyFileSystemUtilization | Verifies that no partition is utilizing more than 75% of its disk space. | - | failure | Mount point: overlay          60G   47G   14G  78% / - Higher disk space utilization - Expected: 75% Actual: 78%<br>Mount point: /dev/sda2        60G   47G   14G  78% /mnt/flash - Higher disk space utilization - Expected: 75% Actual: 78% |
| s1-brdr1 | System | VerifyMemoryUtilization | Verifies whether the memory utilization is below 75%. | - | failure | Device has reported a high memory usage - Expected: < 75% Actual: 90.31% |
| s1-brdr2 | System | VerifyCPUUtilization | Verifies whether the CPU utilization is below 75%. | - | failure | Device has reported a high CPU utilization -  Expected: < 75% Actual: 93.5% |
| s1-brdr2 | System | VerifyFileSystemUtilization | Verifies that no partition is utilizing more than 75% of its disk space. | - | failure | Mount point: overlay          60G   47G   14G  78% / - Higher disk space utilization - Expected: 75% Actual: 78%<br>Mount point: /dev/sda2        60G   47G   14G  78% /mnt/flash - Higher disk space utilization - Expected: 75% Actual: 78% |
| s1-brdr2 | System | VerifyMemoryUtilization | Verifies whether the memory utilization is below 75%. | - | failure | Device has reported a high memory usage - Expected: < 75% Actual: 90.31% |
| s1-leaf1 | System | VerifyCPUUtilization | Verifies whether the CPU utilization is below 75%. | - | failure | Device has reported a high CPU utilization -  Expected: < 75% Actual: 77.3% |
| s1-leaf1 | System | VerifyFileSystemUtilization | Verifies that no partition is utilizing more than 75% of its disk space. | - | failure | Mount point: overlay          60G   47G   14G  78% / - Higher disk space utilization - Expected: 75% Actual: 78%<br>Mount point: /dev/sda2        60G   47G   14G  78% /mnt/flash - Higher disk space utilization - Expected: 75% Actual: 78% |
| s1-leaf1 | System | VerifyMemoryUtilization | Verifies whether the memory utilization is below 75%. | - | failure | Device has reported a high memory usage - Expected: < 75% Actual: 90.11% |
| s1-leaf2 | System | VerifyCPUUtilization | Verifies whether the CPU utilization is below 75%. | - | failure | Device has reported a high CPU utilization -  Expected: < 75% Actual: 94.1% |
| s1-leaf2 | System | VerifyFileSystemUtilization | Verifies that no partition is utilizing more than 75% of its disk space. | - | failure | Mount point: overlay          60G   47G   14G  78% / - Higher disk space utilization - Expected: 75% Actual: 78%<br>Mount point: /dev/sda2        60G   47G   14G  78% /mnt/flash - Higher disk space utilization - Expected: 75% Actual: 78% |
| s1-leaf2 | System | VerifyMemoryUtilization | Verifies whether the memory utilization is below 75%. | - | failure | Device has reported a high memory usage - Expected: < 75% Actual: 90.24% |
| s1-leaf3 | System | VerifyFileSystemUtilization | Verifies that no partition is utilizing more than 75% of its disk space. | - | failure | Mount point: overlay          60G   47G   14G  78% / - Higher disk space utilization - Expected: 75% Actual: 78%<br>Mount point: /dev/sda2        60G   47G   14G  78% /mnt/flash - Higher disk space utilization - Expected: 75% Actual: 78% |
| s1-leaf3 | System | VerifyMemoryUtilization | Verifies whether the memory utilization is below 75%. | - | failure | Device has reported a high memory usage - Expected: < 75% Actual: 89.61% |
| s1-leaf4 | System | VerifyFileSystemUtilization | Verifies that no partition is utilizing more than 75% of its disk space. | - | failure | Mount point: overlay          60G   47G   14G  78% / - Higher disk space utilization - Expected: 75% Actual: 78%<br>Mount point: /dev/sda2        60G   47G   14G  78% /mnt/flash - Higher disk space utilization - Expected: 75% Actual: 78% |
| s1-leaf4 | System | VerifyMemoryUtilization | Verifies whether the memory utilization is below 75%. | - | failure | Device has reported a high memory usage - Expected: < 75% Actual: 90.24% |
| s1-spine1 | System | VerifyCPUUtilization | Verifies whether the CPU utilization is below 75%. | - | failure | Device has reported a high CPU utilization -  Expected: < 75% Actual: 94.8% |
| s1-spine1 | System | VerifyFileSystemUtilization | Verifies that no partition is utilizing more than 75% of its disk space. | - | failure | Mount point: overlay          60G   47G   14G  78% / - Higher disk space utilization - Expected: 75% Actual: 78%<br>Mount point: /dev/sda2        60G   47G   14G  78% /mnt/flash - Higher disk space utilization - Expected: 75% Actual: 78% |
| s1-spine1 | System | VerifyMemoryUtilization | Verifies whether the memory utilization is below 75%. | - | failure | Device has reported a high memory usage - Expected: < 75% Actual: 89.87% |
| s1-spine2 | System | VerifyCPUUtilization | Verifies whether the CPU utilization is below 75%. | - | failure | Device has reported a high CPU utilization -  Expected: < 75% Actual: 93.5% |
| s1-spine2 | System | VerifyFileSystemUtilization | Verifies that no partition is utilizing more than 75% of its disk space. | - | failure | Mount point: overlay          60G   47G   14G  78% / - Higher disk space utilization - Expected: 75% Actual: 78%<br>Mount point: /dev/sda2        60G   47G   14G  78% /mnt/flash - Higher disk space utilization - Expected: 75% Actual: 78% |
| s1-spine2 | System | VerifyMemoryUtilization | Verifies whether the memory utilization is below 75%. | - | failure | Device has reported a high memory usage - Expected: < 75% Actual: 90.20% |
