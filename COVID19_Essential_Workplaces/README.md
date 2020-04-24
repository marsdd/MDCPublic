# Essential Workers - NAICS Crosswalk
> This crosswalk maps the Ontario’s Essential Workplaces to 4-digit NAICS industry groups.

The [Essential Workplaces list](https://www.ontario.ca/page/list-essential-workplaces) identifies workplaces whose physical locations are legally allowed to remain open as others are required to close in order to mitigate the spread of COVID-19 through the province of Ontario. The list was first published by the Government of Ontario on March 24, 2020, and later updated on April 3. This crosswalk is based on the April 3 updated version.

The crosswalk maps Essential Workplaces to 4-digit industry groups based on the [North American Industry Classification System (NAICS) Canada 2017 Version 3.0](https://www23.statcan.gc.ca/imdb/p3VD.pl?Function=getVD&TVD=1181553) used by Statistics Canada. 

MaRS Data Catalyst is providing this crosswalk free of charge as a resource for people looking to understand how COVID-19 is impacting Ontarians.
<br />

## Getting started

To access the data, simply clone the repository to your machine and access the data table directly:

```
git clone https://github.com/MDCPublic/COVID19_Essential_Workplaces.git
cd COVID19_Essential_Workplaces/
```

## Usage Notes

* A given Essential Workplace may be mapped to multiple industry groups.
* The ‘entirely_essential’ column indicates whether all industries under a 4-digit industry group are considered essential workplaces (which is the case when entirely_essential = 1), or whether only some  industries under the industry group are considered essential workplaces (which is the case when entirely_essential = 0).

## Contributing

To contribute to this project, follow these steps:

1. Fork this repository
2. Create a branch `git checkout -b <branch_name>`
3. Make your changes and commit them: `git commit -m '<commit_message>'`
4. Push to the original branch: `git push origin <project_name>/<location>`
5. Create a pull request.

Alternatively, see the GitHub documentation on creating a [pull request](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request).
<br />   

## Contributors

Thanks to the following people who have contributed to this project:

* 
*
<br />  

## Related Links

- [Government of Ontario's List of Essential Workplaces](https://www.ontario.ca/page/list-essential-workplaces)
- [North American Industry Classification System (NAICS) Canada 2017 Version 3.0](https://www23.statcan.gc.ca/imdb/p3VD.pl?Function=getVD&TVD=1181553)
- Report exploring [COVID-19 exposure risk for Ontario's essential service workers](https://www.marsdd.com/research-and-insights/covid-19-and-ontarios-sales-and-service-workers-who-is-most-vulnerable/)

## Licensing

Contains information licensed under the Open Government Licence – Ontario.

Adapted from Statistics Canada, North American Industry Classification System (NAICS) Canada 2017 Version 3.0. This does not constitute an endorsement by Statistics Canada of this product.

The code in this project is licensed under CC BY-SA 2.0 license. Please acknowledge MaRS Data Catalyst when using it.
