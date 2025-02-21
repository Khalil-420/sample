# Selis Runtime Quality Gateway (DAST)

Selis Runtime Quality Gateway is a layer added to the pipeline as a weekly or daily job to test the application at runtime. It is an automated pentest tool that applies OWASP top 10 security checks.

**NOTE**
- Testing backend APIs with automation is challenging. Importing OpenAPIs and using randomly generated values may not be applicable in our case. To work around this limitation, manual active attacks must be applied to return the report. These active attacks may take more than 1 to 2 days and use intercepted HTTP requests and responses to manipulate the data, enabling actual API testing with the correct payload. Additionally, you can assist the ZAP tool in testing functionality by entering specific domains. The report should be imported into DefectoDojo.
- please use the active scan with extreme caution as it may break something in the process


## License

This project is licensed under the [Calx](LICENSE).
