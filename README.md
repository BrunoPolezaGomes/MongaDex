# Pokédex
<div>
  <h2>ASP.NET Core 3.1 MVC/Web API Application</h2>
  <h3>
    <a href="https://mypokedex.azurewebsites.net/" target="_blank">MyPokédex Hosted on Azure App Services</a>
    <img src="https://img.shields.io/website?logo=microsoft&url=https%3A%2F%2Fmypokedex.azurewebsites.net"/>
  </h3>
  <p>Search NationalDex Pokémon based on a variety of criterion. Create, modify, and view a personal Pokédex.</p>
</div>

<div>
  <h3>Technologies & Methodologies</h3>
  <ul>
    <li>C#, .NET Core 3.1, ASP.NET Core 3.1 MVC & Web API</li>
    <li>Logging, Configuration, Health Check, & Dependency Injection</li>
    <li>SQL Server, SSMS, T-SQL, Azure SQL Database</li>
    <li>Azure App Services</li>
    <li>Azure Application Insights</li>
    <li>Cloudscribe Models/Pagination</li>
    <li>Repository Pattern</li>
    <li>EntityFrameworkCore, LINQ, & AutoMapper</li>
    <li>Unit Testing with Moq & MSTest Frameworks, Arrange/Act/Assert Pattern</li>
    <li>JavaScript, jQuery, JSON, HTML5, LESS, CSS3, Responsive Design, WebCompiler, BEM Notation, Minification</li>
    <li>Swagger & Postman</li>
    <li>Visual Studio</li>
  </ul>
  <h3>Local Setup (Quickstart)</h3>
  <ol>
    <li>
      <span>Prerequisites</span>
      <ul>
        <li>Visual Studio</li>
        <li>SQLServer Instance</li>
        <li>SSMS & SSDT</li>
        <li>Web Compiler [used for LESS compilation, only needed if you make changes]</li>
        <li>Postman</li>
      </ul>
    </li>
    <li>Publish POKEDEXDB to localdb.</li>
    <li>Update the PokedexApp/PokedexAPI appsettings.Development.json connection string to point to the newly create database.</li>
    <li>Ensure nuget packages are restored and ready to use.</li>
    <li>Build, Run Tests, Run Application locally. Note: if calling API, utilize Postman Collection.</li>
  </ol>
  <p>Note: see repository <a href="https://github.com/pobruno/MongaDex/wiki">Wiki</a> for detailed Architecture, Design, and Implementation</p> 
</div>
