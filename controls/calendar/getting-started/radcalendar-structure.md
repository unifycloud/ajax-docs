---
title: RadCalendar Structure
page_title: RadCalendar Structure | UI for ASP.NET AJAX Documentation
description: RadCalendar Structure
slug: calendar/getting-started/radcalendar-structure
tags: radcalendar,structure
published: True
position: 1
---

# RadCalendar Structure



## 

The diagram below shows the element structure of __RadCalendar__. The control elements are described below.![RadCalendar structure](images/RadcalendarStructure.png)

* __Title Bar__ - displays the selected date range (month and year) as well as the navigation buttons. The appearance of both the [title]({%slug calendar/radcalendar/title-settings%}) and [navigation buttons]({%slug calendar/radcalendar/navigation-controls-settings%}) can be customized.

* __Navigation Buttons__ - allow you to move to the previous or next month or jump multiple steps forward or backward.

* __Title and Navigation Popup Zone__ - the title area can be set as a navigation popup zone,so that when the user clicks it, it displays the month/year navigation popup:![Overview of RadCalendar structure](images/calendar_overviewstructure_002.png)

* __Main Calendar Area__ - renders the calendar views, whether single or[multiple]({%slug calendar/radcalendar/multi-view-mode%}). Each calendar view in the maincalendar area includes a view selector, row and column headers, and the day matrix.

* __View Selector__ - allows the user to select all the dates displayed in the day matrix.This control can optionally be omitted, using the __EnableViewSelector__ property.

* __Row Headers__ - label the rows of the calendar. Depending on the calendar orientation,they either display the week of the year, or the day of the week. The __ShowRowHeaders__property controls whether they appear in the calendar, and the __UseRowHeadersAsSelectors__property specifies whether they can be used to toggle the selection on a row of dates.

* __Column Headers__ - label the columns of the calendar. Depending on the calendar orientation,they either display the day of the week, or the week of the year. The __ShowColumnHeaders__property controls whether they appear in the calendar, and the __UseColumnHeadersAsSelectors__property specifies whether they can be used to toggle the selection on a row of dates.

* __Day Matrix__ - displays the dates of the month in a particular calendar view. The __ShowOtherMonthDays__ property controls whether the day matrix includes the last days of the previous month and the first days of the next month when they fall on the same week as the first or last day of the month. You can [customize the layout of the day matrix]({%slug calendar/radcalendar/customizing-the-day-matrix%}).

If you use [templates]({%slug calendar/templates/radcalendar-header-and-footer-templates%}), the calendar can also include header and footer regions:![Customized RadCalendar](images/calendar_overviewstructure_003.png)

* __Header__ - falls between the Title Bar and the Main Calendar Аrea. It is used mainly for visual customization.

* __Footer__ - falls below the Main Calendar Area. It can be used for visual customization or for displaying additional information about the selected item.

# See Also

 * [RadDatePicker, RadTimePicker, and RadDateTimePicker Structure]({%slug calendar/getting-started/raddatepicker,-radtimepicker,-and-raddatetimepicker-structure%})

 * [RadTimeView Structure]({%slug calendar/getting-started/radtimeview-structure%})