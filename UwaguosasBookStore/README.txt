
Started the Assignment-2 inh class on the lab computer
Set uip the ASP.NET MVC w/core 1.3(out- of support)
HTTPS enabled, individual account authentication ... no RAzor 
Reviewed the Areas folder, controller, Model, View
1506 in startup.cs (Line 33)
removed options for default identity:
options=> options.SignIn.RequireConfirmedAccount = true
1510
Tested the App .. ran it and it was goosd... tested the link as well
Action Items:
-Modify the Navigation
1516
Modified the default welcome message
review the route pattern in startup.cs
-Update the Copyright.. from static to Dynamic

2023-03-03
1510 clone my repository UwaguosaBookStore in Github.. test it 
1550
Created the READ.md File and pulled it.

2023-03-09
@1412 cloned my repository 
@1420 Created a navigation for books in the shared views
@1425 Selected the bootstrap theme(Morph) from bootswatch and downloaded the bootstrap.css
@1430 
Replaced the existing bootstrap.css in the lib/bootstrap/dist/css with the downloaded bootstrap 
Also replaced the site.css in the main css folder with the downloaded bootstrap.css
Changed the file name from bootstrap.min.css to bootstrap.css in the shared _layout.cshtml head
Changed the nav class from navbar-light to navbar dark and bg-white to bg-primary
removed the text-dark in line 23, Added "text-white-50 bg-primary" to the footer class 
Replaced the @RenderSection("script, required:false") with @await RenderSectionAsync("script, required:false") in line 48
In the _LoginPartial.cshtml removed the "text dark" in line 9
Ran the project and the theme was updated.
@1510 Added addidtional stylesheet  and JS to the _Layout.cshtml page 
@1525 Added a Dropdown menu in the navigation bar
ran it but the drop down did not work
@1540 then I replaced the id with "navbarDropdownMenuList" and added "data-toggle="dropdown""
also replaced the aria-labelledby with "navbarDropdownMenuList"
@1555 Ran the app and the dropdown worked 

2023-03-10
@1427 Made three new projects (UwaguosasBooks.DataAccess, UwaguosasBooks.Model, UwaguosasBooks.Utility)
@1522 Copied the Data folder and pasted it to UwaguosasBooks.DataAccess and deleted it from original app
installed the Microsoft.EntityFrameworkCore.Relational and Core.SqlServer packages
Deleted the Migration folder