# Automated-classroom-Attendence-sysytem
<!DOCTYPE html>
<html lang="en">
    <head>
        <style>
                body{
	background-image:url(htmlpage.jpg);
	background-size:1800px 800px;
	background-repeat: no-repeat;

}
        </style>
        <script src="script.js"></script>
        <meta charset="UTF-8" />
        <meta name="viewport"
              content="width=device-width, initial-scale=1.0" />
        <title>Students Attendance</title>
    </head>
    <body>

        <!-- Here a loader is created which
             loads till response comes  -->
        <center><h1>Students Attendance </h1></center>
        <div class="d-flex justify-content-center">
            <div class="spinner-border"
                 role="status" id="loading">
                <center><span class="sr-only">Loading...</span></center>
            </div>
        </div>

        <!-- table for showing data -->
        <center><table id="students" width="500" border="5"  cellpadding="5" cellspacing="5"></table></center>
    </body>
</html>
