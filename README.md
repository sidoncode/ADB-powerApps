# ADB-powerApps

```

SortByColumns(
    Filter(
        WorkforceAvailability,
        IsBlank(dteFilterDate.SelectedDate) || WorkDate = dteFilterDate.SelectedDate,
        IsBlank(txtSearch.Text) || txtSearch.Text in Title,
        IsBlank(drpTeamFilter.Selected.Result) || TeamOrUnit = drpTeamFilter.Selected.Result
    ),
    "Title",
    SortOrder.Ascending
)


```
