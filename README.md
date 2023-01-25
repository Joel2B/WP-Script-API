# WP-Script API
This api allows you to use some wp-script products completely free of charge.

### How to use api
replaces the line in the plugin config.php file.

```php 
define( 'WPSCORE_API_URL', apply_filters( 'wpscore_api_url', 'https://www.wp-script.com/wp-json/wpsevsl/v2' ) );
```
to
```php 
define( 'WPSCORE_API_URL', apply_filters( 'wpscore_api_url', 'https://appsdev.cyou/wp-script-api/api' ) );
```
or, you can download the modified plugin which you can download below.

### Setup
place anything in the license field.

### How it works?
The API uses a valid wp-script license which includes in its plan certain products you can see [here](https://appsdev.cyou/wp-script-api/),
this works as an intermediary between the plugin and the wp-script services, always giving a successful answer to any query you make to it,
these queries are cached for 1 month as they do not usually change much, and if any query fails, the cache is updated, 
also avoids sending the license to their services.

### Downloads
Here are the plugins with the modified api.
> [https://appsdev.cyou/wp-script-api/](https://appsdev.cyou/wp-script-api/)
 
