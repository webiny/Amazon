Amazon Component
=================

Amazon component serves as a wrapper for Amazon Web Services SDK. Currently only S3 component is being used.

Resources
---------
To run unit tests, you need to use the following command:

    $ cd path/to/Webiny/Component/Amazon/
    $ composer.phar install
    $ phpunit

Make sure that you also set your S3 API details in `Test/AmazonS3Test.php` before running the tests.