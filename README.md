knockout-razor-helper-methods
=============================
Put KO.cshtml in App_Code folder in web app root. And include StringExt.cs

##Example
    @KO.EditRow("DriverLicenseNumber", "Driver License Number")
    @KO.DropdownRow("DriverLicenseState", "States", "Driver License State")
    @KO.DateRow("DateInactive", "Date Inactive")
    @KO.TextAreaRow("Notes")
    @KO.CheckBoxRow("IsCdlHolder", "Is CDL Holder")
