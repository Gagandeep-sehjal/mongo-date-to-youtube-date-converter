# Mongo Date to YouTube Date Converter

This Node.js module converts MongoDB date strings into a YouTube-like date format, providing a convenient way to display relative time durations.

## Installation

You can install the package via npm:

```bash
npm install mongo-date-to-youtube-date-converter

## Usage


```bash
// Import the function
const { convertMongoDateToYouTubeDate } = require('mongo-date-to-youtube-date-converter');
// Define a MongoDB date string
const mongoDate = '2024-03-09T12:00:00Z';
// Convert the MongoDB date to YouTube-like format
const youtubeDate = convertMongoDateToYouTubeDate(mongoDate);
console.log(youtubeDate); // Output: '2 hours ago'

## Function
convertMongoDateToYouTubeDate(mongoDate: string): string
mongoDate: A MongoDB date string in ISO 8601 format.
Returns a string representing the difference between the provided MongoDB date and the current date in a YouTube-like format.

## Example
Input: '2024-03-09T12:00:00Z'
Output: '2 hours ago'

## License
This project is licensed under the MIT License - see the LICENSE file for details.
