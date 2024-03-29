# Data Visualization Projects: Visualize Data with a Choropleth Map


#### Fulfill the below user stories and get all of the tests to pass. Give it your own personal style. You can use HTML, JavaScript, CSS, and the D3 svg-based visualization library. Required (non-virtual) DOM elements are queried on the moment of each test. If you use a frontend framework (like Vue for example), the test results may be inaccurate for dynamic content. We hope to accommodate them eventually, but these frameworks are not currently supported for D3 projects.

1. User Story: My choropleth should have a title with a corresponding id="title".
2. User Story: My choropleth should have a description element with a corresponding id="description".
3. User Story: My choropleth should have counties with a corresponding class="county" that represent the data.
4. User Story: There should be at least 4 different fill colors used for the counties.
5. User Story: My counties should each have data-fips and data-education properties containing their corresponding fips and education values.
6. User Story: My choropleth should have a county for each provided data point.
7. User Story: The counties should have data-fips and data-education values that match the sample data.
8. User Story: My choropleth should have a legend with a corresponding id="legend".
9. User Story: There should be at least 4 different fill colors used for the legend.
10. User Story: I can mouse over an area and see a tooltip with a corresponding id="tooltip" which displays more information about the area.
11. User Story: My tooltip should have a data-education property that corresponds to the data-education of the active area.

#### Here are the datasets you will need to complete this project:

* US Education Data: https://raw.githubusercontent.com/no-stack-dub-sack/testable-projects-fcc/master/src/data/choropleth_map/for_user_education.json
* US County Data: https://raw.githubusercontent.com/no-stack-dub-sack/testable-projects-fcc/master/src/data/choropleth_map/counties.json
