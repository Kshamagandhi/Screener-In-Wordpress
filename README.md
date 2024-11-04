## Features

- **Dynamic Filtering**: Users can filter screener data using various criteria such as greater than, less than, or equal to specific values.
- **DataTables Integration**: Utilizes DataTables for interactive data display, including sorting and pagination.
- **Select2 Dropdowns**: Implements Select2 for improved dropdown usability.
- **CSV Data Handling**: Loads screener data and lists from CSV files, making it easy to update and manage data.
- **AJAX Support**: Uses AJAX to filter data without refreshing the page, providing a smooth user experience.

## Installation

1. Download or clone the repository to your local machine.
2. Upload the **screener-filter-plugin** directory to your WordPress plugins directory (`wp-content/plugins/`).
3. Activate the plugin through the **Plugins** menu in WordPress.
4. Use the shortcode `[screener_filter]` to display the filter and table on any post or page.

## Usage

Once the plugin is activated, you can add the `[screener_filter]` shortcode to any post or page where you want the screener filter to appear. Users can then interact with the dropdowns to filter the displayed screener data.

## Data Files

Ensure that you have the following CSV files in the `data` directory of the plugin:

- **screener_list.csv**: Contains the list of metrics for filtering.
- **screener_data.csv**: Contains the actual screener data to be filtered.
