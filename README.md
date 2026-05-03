# Online Prodavnica – ASP.NET MVC 5

## Opis aplikacije
Web aplikacija za online kupovinu razvijena u ASP.NET MVC 5 
sa Entity Framework Code First pristupom i SQL Server bazom podataka.

Aplikacija omogućava korisnicima pregled i kupovinu proizvoda, 
upravljanje korpom i uređivanje profila. 
Administratori mogu dodavati, menjati i brisati proizvode.

## Tehnologije
- ASP.NET MVC 5 (.NET Framework 4.7.2)
- Entity Framework 6 – Code First sa migracijama
- ASP.NET Identity – autentifikacija i autorizacija
- SQL Server LocalDB
- Bootstrap 5
- jQuery Validate + Unobtrusive Validation
- PagedList.Mvc – paginacija
- Chart.js – statistika

## Stranice
| Stranica       | URL                     | Opis                             |
|----------------|-------------------------|----------------------------------|
| Proizvodi      | /Proizvod               | Lista, pretraga, filter, sort    |
| Detalji        | /Proizvod/Detalji/{id}  | Pregled jednog proizvoda         |
| Korpa          | /Korpa                  | Upravljanje korpom               |
| Profil         | /Profil                 | Izmena ličnih podataka           |
| Statistika     | /Statistika             | Grafikon po kategorijama (Admin) |
| Prijava        | /Auth/Login             |                                  |
| Registracija   | /Auth/Register          |                                  |

## Uputstvo za pokretanje

### Preduslovi
- Visual Studio 2019 ili 2022
- SQL Server LocalDB (dolazi uz Visual Studio)
- .NET Framework 4.7.2

### Koraci
1. Klonirati repozitorijum
   git clone https://github.com/TVOJE_IME/online-prodavnica.git

2. Otvoriti Online_prodavnica.sln u Visual Studiju

3. Restore NuGet paketa
   desni klik na Solution → Restore NuGet Packages

4. Pokrenuti migracije u Package Manager Console
   Update-Database

5. Pokrenuti projekat (F5)

### Admin nalog
- Email: admin@shop.com
- Lozinka: Admin123!

## Napredni zahtevi
- Paginacija liste proizvoda (PagedList.Mvc)
- Korisnički profil – pregled i izmena podataka

## Autor
Ime Prezime – Razred – Školska godina 2024/2025
