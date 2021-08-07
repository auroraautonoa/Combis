Upute za korištenje

1. Promijeniti connection string
	UserManagment.Api => appsettings.json =>   "ConnectionStrings": {"DBConnection": "" },
2. Izvršiti migracije
	- Package Manager Console (UserManagment.Api) unijeti naredbe: 
		- Add-Migration InitialCreate 
		- Update-Database in PM
