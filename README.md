# About

Basic and raw PHP scriopt to create Amazon S3 Expiring URL's

## Usage

Very simple PHP script to create time expiring URL's for Amazon S3.

- Set your public and secret keys in key.php
- Set your bucket name in s3-expiring-url.php @ line 8. The file delivering from bucket should not need any special permissions.
- Set your link expire time in s3-expiring-url.php @ line 51. To test, set line 51 to a value of 1.
- Set your filename from specified bucket in download.php (a href area).
- Navigate to download.php and test link. Wait for time to expire and click link again. Should get expire message from Amazon.

## Not for Production

I do not recommend you use this script as is. We have found it safe for our needs but has never been tested in rouge environment.  We are using for educational purposes. Use at your own risk.

### Credits

I have had this script for years and honestly cannot remember where the main code came from. It was updated and sent back to me few months ago so decided to share here and make easier to maintain. Most is based on code directly from Amazon examples. I believe in giving credit where credit is due but in this case, I haven't clue to origin.

If you have improvements, they are welcome and looking forward to pull request, so fork it!
