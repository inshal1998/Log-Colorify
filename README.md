# 🎨 Colored Logger

A lightweight and easy-to-use logger utility to add colors to your console logs in the browser. Perfect for debugging with visual clarity.




## ✨ Features

- ✅ Green-colored logs for success messages
- ❌ Red-colored logs for error/danger messages
- ℹ️ Yellow-highlighted logs for informational messages




## 📖 Documentation

- **Logger**: The main class for logging messages.
- **Methods**:
  - `success(message: string)`: Logs a success message in green.
  - `danger(message: string)`: Logs a danger message in red.
  - `info(message: string)`: Logs an informational message in yellow.




## 📦 Installation

```bash
npm install colored-logger
```



# 🚀 Usage

```javascript
import { Logger } from 'colored-logger';

const logger = new Logger();

logger.success('Operation completed successfully!');
logger.danger('An error occurred!');
logger.info('This is some information.');
```
