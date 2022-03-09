# deployed-forecasts
JSON Forecast Configuration Files to be Deployed

## Upload your json file ##

Upload lake json file to this [repo](https://github.com/FLARE-forecast/deployed-forecasts)

The json file format needs to follow as below
```json=
{
  "forecast_code": "XXX",
  "config_set": "XXX",
  "function": "1",
  "configure_run": "configure_run.yml",
  "use_https": "XXX",
  "aws_default_region": "XXX",
  "aws_s3_endpoint": "XXX",
  "schedule": "0 */6 * * *"
}
```
* The "function" variable needs to be set to "1".
