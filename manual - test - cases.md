# Manual Test Cases - WhatsApp Mobile App

## Test Case 1: Login with valid phone
Steps:
1. Open WhatsApp
2. Enter valid phone number
3. Enter OTP
Expected: User logs in successfully

## Test Case 2: Send message without internet
Steps:
1. Turn off internet
2. Try send message
Expected: Shows clock icon / failed to send

## Test Case 3: App Rotation
Steps:
1. Open chat
2. Rotate phone
Expected: App should not crash, chat remains

## Bugs Found Example
Bug ID: BUG-001
Severity: Medium
Description: App crashes when uploading 100MB video
