# Runtime table creation best practices (iterative approach)


<p>This example demonstrates the differences in runtime table creation between the newest XtraReports version and its prior versions.</p>
<p>Please note that it is always required to call the <strong>XRTable.BeginInit</strong> and <strong>XRTable.EndInit</strong> methods if you modify <strong>XRTable.Rows</strong> and <strong>XRTableRow.Cells</strong> collections at runtime.</p>
<p>As for the height of a table, explicitly specify it only if cells' content is not expected to stretch the cells (e.g. this may happen when their <strong>CanGrow</strong> property is enabled).<br><br><strong>See also</strong>:<br><a href="https://www.devexpress.com/Support/Center/p/E108">How to convert an XtraGrid to an XtraReport at runtime</a></p>

<br/>

