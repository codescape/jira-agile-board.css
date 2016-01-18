# jira-agile-board.css

By default the visual separation between stories on the JIRA Agile sprint backlog is not as good as it could and should be. This custom CSS works as a solution for this issue with the following adjustments:

* open stories are displayed with a blue background
* completed stories are displayed with a green background
* swimlanes that have no completion status are still displayed with a white background
* minimum height of tasks has been reduced to improve amount of visible stories on the board

## How to install

1. Open the System Administration of your JIRA installation
2. Locate the menu option `Announcement Banner` in the `User Interface` section
3. Add the code from the file `src/announcement-banner.html` from this repository into the announcement textarea

The CSS is successfully tested against JIRA 6.4.11 and 7.0.4.
