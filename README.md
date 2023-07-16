<a name="readme-top"></a>

## About the 'Livestock' project
The livestock internet shop, where people can buy a cow, a pig and so on.<br />
<p>
The project consists of the following:
<ul>
  <li><a href="https://github.com/lukesukhanov/livestock-web">the frontend application</a></li>
  <li><a href="https://github.com/lukesukhanov/livestock-database">the database service</a></li>
  <li><a href="https://github.com/lukesukhanov/livestock-database-migration">the database migration service</a></li>
  <li><a href="https://github.com/lukesukhanov/livestock-discovery-server">the discovery service</a></li>
  <li><a href="https://github.com/lukesukhanov/livestock-api-gateway">the API gateway</a></li>
  <li><a href="https://github.com/lukesukhanov/livestock-authorization-server">the authorization server</a></li>
  <li><a href="https://github.com/lukesukhanov/livestock-product-service">the product service</a></li>
  <li><a href="https://github.com/lukesukhanov/livestock-cart-service">the cart service</a></li>
</ul>

## How to run the project
Execute 'docker-compose up -d' in the directory with docker-compose.yml.<br />
The following ports will be exposed: 5500, 8765, 8761.<br />
Now you can find Livestock on localhost:5500.

## What does it look like
![alt text](https://github.com/lukesukhanov/livestock-web/blob/main/screenshot.jpg)

## What features are presented
<ul>
  <li>You can select a product category, e. g. 'Козы'.</li>
  <li>You can search products (by name and description).</li>
  <li>You can filter products by min and max price.</li>
  <li>You can register an account on authorization server.</li>
  <li>You can login to your registered account.</li>
  <li>You can add products to the cart (works only for authenticated users, sadly).</li>
  <li>You can open the cart.</li>
  <li>You can remove one product from the cart.</li>
  <li>You can remove all products from the cart.</li>
</ul>

## What tools are exploited
<ul>
  <li>HTML + CSS + (pure) JavaScript</li>
  <li>PostgreSQL + Liquibase</li>
  <li>Spring Cloud: discovery server + API gateway + clients</li>
  <li>Spring Boot</li>
  <li>Spring Security: OAuth 2.1 + Spring Authorization Server</li>
  <li>Docker</li>
</ul>
