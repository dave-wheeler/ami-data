## AMI Sample Data
This is sample data for use with [AMI](https://github.com/dave-wheeler/ami)

## Getting your own data
Login at [IREA's AMI site](https://irea.coop/ami/). On the account details page, under the section titled 'Additional Consumption Information for AMI Customers,' click the 'MyPower Site' link. In the left panel, expand the Reports section, and click 'Meter Usage Chart.' Set the parameters you want, and then BEFORE submitting the parameters, open the network tab in your browser's dev tools. After submission, find the POST request, and copy it as a CURL request to the clipboard. You can modify the parameters in the request if you want (e.g., if you want 15-min meter usage readings over a long period of time). When you're satisified with the request's parameters, submit the request from a shell (this assumes you have Curl installed!) You can then save those results to use with [AMI](https://github.com/dave-wheeler/ami)
