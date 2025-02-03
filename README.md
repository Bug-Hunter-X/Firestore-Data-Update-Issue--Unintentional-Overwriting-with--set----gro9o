# Firebase Firestore Data Update Bug
This repository demonstrates a common error in Firebase Firestore where using `set()` unintentionally overwrites existing document data instead of updating specific fields.
The `firestoreBug.js` file shows the incorrect implementation leading to data loss. The `firestoreBugSolution.js` file provides the corrected code using the `update()` method for updating only specific fields, preserving existing data.

## Setup
1. Install Firebase:
   ```bash
   npm install firebase
   ```
2. Configure your Firebase project.
3. Replace placeholders with your Firebase configuration details in the code files.

## Usage
Run the code examples to reproduce and fix the problem. The differences clearly show how to update fields correctly in Firestore without data loss.