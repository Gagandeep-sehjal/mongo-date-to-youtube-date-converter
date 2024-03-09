# Mongo Date to YouTube Date Converter


## Usage

To use this module, follow these steps:

1. Install the package via npm:
    ```bash
    npm install mongo-date-to-youtube-date-converter
    ```

2. Import the function into your Node.js application:
    ```javascript
    // Import the function
    const { convertMongoDateToYouTubeDate } = require('mongo-date-to-youtube-date-converter');
    ```

3. Define a MongoDB date string:
    ```javascript
    const mongoDate = '2024-03-09T12:00:00Z';
    ```

4. Convert the MongoDB date to YouTube-like format:
    ```javascript
    const youtubeDate = convertMongoDateToYouTubeDate(mongoDate);
    ```

5. Print the result:
    ```javascript
    console.log(youtubeDate); // Output: '2 hours ago'
    ```
