# Sales Summary Test

This static web app implements a single-page site that fetches `data.csv` from attachments, sums its sales column, sets the title to "Sales Summary Test", displays the total inside `#total-sales`, and loads Bootstrap 5 from jsdelivr.

## Summary

This simple web app fetches sales data from `data.csv`, calculates the total sales, and presents the information in a user-friendly manner.

## Setup

To deploy this web app on GitHub Pages:
1. Fork this repository.
2. Upload `data.csv` as an attachment.
3. Enable GitHub Pages for the repository with the `index.html` as the source.

## Usage

To access the page, visit the deployed GitHub Pages URL. You can also pass query params to customize the behavior of the page.

Example query params:
- `?sort=asc`: sorts the sales data in ascending order.
- `?sort=desc`: sorts the sales data in descending order.

## Code Explanation

The HTML of this web app is structured to fetch `data.csv`, calculate the total sales, and display it in the designated element `#total-sales`. The JavaScript code handles the fetching of data, parsing it, summing the sales column, and dynamically updating the page with the total.

## License

This project is licensed under the MIT License.