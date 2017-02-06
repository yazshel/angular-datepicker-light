# AngularJS datepicker plugin

`bower install angular-datepicker-light-zz`

### Customizations (v1.2.5+)

This plugin is heavily customized as per my need. But keeping in mind that this remains re-usable. If it's pull request gets accepted i might delete this repo, otherwise this repo/plugin will remain use-full(at-least for us).

Below is intro of main customizations:

* Change positioning logic for non-inline usage(to solve problme in our complex view where previous logic was failing)
* Prevent calender pop-up from being closed when a month or year is select from drop-down, to let users select full date in one go.
* Add support for <a href="https://github.com/angular-ui/ui-select">ui-select</a> drop-down to facilitate projects using ui-select as standard drop-down
* nextYeras, prevYears, hideTodayDate, useAngularUiSelect options added(see below for details).
* Some style enhancements/adjustments.
* Other minor adjustments

### Additional options details:

* useAngularUiSelect:
    Default: false
    Description: "Specifies if ui-select should be used for drop-downs. Note that we assume if this is true, than ui-select is already included in project."

* hideTodayDate:
    Default: false
    Description: "If true, hides bottom panel(containing today's date) from calender display."

* prevYers:
    Default: 5
    Description: "Sets number of previous years(from current year) to display in year drop-down. NOTE if minDate is defined, this will be ignored in minDate's favor."

* nextYears:
    Default: 5
    Description: "Sets number of next years(from current year) to display in year drop-down. NOTE if maxDate is defined, this will be ignored in maxDate's favor"

* toggleTarget: (added in 1.2.6)
    Default: null,
    Description: "A JQuery selector, on click of which, calender will toggle display(show/hide)."


#### Requirements

* Angular v1.5.3+
* Moment v2.12.0+

<b>Demo(Of original gem):</b> http://vickramravichandran.github.io/angular-datepicker-light/

<a href="https://github.com/vickramravichandran/angular-datepicker-light/archive/demo.zip">Download Demo zip</a>
