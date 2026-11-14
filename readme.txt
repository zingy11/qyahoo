make_a_flexible_application_object_that_deals_with_a_single_site
quarkus, maven, java, postgres, hiveql

resteasy vs quarkus

You can build and run a Quarkus REST API with just:

Plain Text
Java 21
+
Maven
+
Quarkus

No application server required.

No WildFly required.

No Tomcat required.

===============================================
create a minimal working project with Quarkus using maven, later comeback try to change libraries or tools
==============================================


You don't build an outbound API endpoint for every external endpoint.

You usually build:

Outbound client methods (your code calling external APIs)
Inbound endpoints (your API exposed to users)

The mapping can be 1:1, many:1, or 1:many.




should be a single schema for any site - and each site has a subset of fields

this case we're dealing with:
stocks
forex
commodities
futures
fundamentals
websocket
freetier

also types of markets (by the tradingcharts categories):

Futures Market Sectors		just spell them repeatedly in relation to their containments
Currency Futures	      regenerate glands and focus in on different patterns wisely
Energy / Oil Futures
Grains & Oilseed
Index Futures
Interest Rate & Bond
Metals Futures
Meats, Cattle / Pork
Softs Commodities

Major Forex Pairs
EUR/USD
USD/JPY
GBP/USD
USD/CHF
EUR/GBP
EUR/JPY
EUR/CHF
AUD/USD
USD/CAD
NZD/USD

Popular Stocks
Microsoft
3M Company
Bank of America
Cisco Systems
Exxon Mobil
Intel Corp
JP Morgan Chase
Kraft Foods Inc
