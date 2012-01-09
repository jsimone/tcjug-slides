<!SLIDE>
# Deploying Java and Play! Apps on Heroku

## John Simone
## @j_simone
## github.com/jsimone
## Slides: tcjug.herokuapp.com

<!SLIDE>

## Safe Harbor
This presentation may contain forward-looking statements that involve risks, uncertainties, and assumptions. If any such uncertainties materialize or if any of the assumptions prove incorrect, the results of salesforce.com, inc. could differ materially from the results expressed or implied by the forward-looking statements we make. All statements other than statements of historical fact could be deemed forward-looking statements, including: any projections of earnings, revenues, or other financial items; any statements regarding strategies or plans of management for future operations; any statements concerning new, planned, or upgraded services or developments; statements about current or future economic conditions; and any statements of belief. 

The risks and uncertainties referred to above include - but are not limited to - risks associated with our new business model; our past operating losses; possible fluctuations in our operating results and rate of growth; interruptions or delays in our Web hosting; breach of our security measures; the immature market in which we operate; our relatively limited operating history; our ability to expand, retain, and motivate our employees and manage our growth; risks associated with new releases of our service; and risks associated with selling to larger enterprise customers. 

<!SLIDE>

## Safe Harbor (continued)
Further information on potential factors that could affect the financial results of salesforce.com, inc. are included in our registration statement (on Form S-1) and in other filings with the Securities and Exchange Commission. These documents are available on the SEC Filings section of this Web site. 

Salesforce.com, inc. assumes no obligation and does not intend to update these forward-looking statements. 

Any unreleased services or features referenced in this or other press releases or public statements are not currently available and may not be delivered on time or at all. Customers who purchase our services should make the purchase decisions based upon features that are currently available.

<!SLIDE>

# Heroku = Polyglot + PaaS + Cloud Components

## Forget servers and focus on building your app

<!SLIDE bullets>

# Polyglot

* Ruby
* node.js
* Clojure
* Java
* Play!

<!SLIDE bullets>

# Polyglot

* Scala
* Python

<!SLIDE bullets>

# Even

* PHP ... for Facebook

<!SLIDE>

# 844,000+ Apps Running on Heroku

<!SLIDE incremental>

# Cloud Application Platform

* HTTP Routing / Load Balancing
* Elastic Polyglot Runtime
* Management & Logging
* Component as a Service Ecosystem

<!SLIDE center>

![how-it-works](../images/how-it-works.png)

<!SLIDE>

# Instant App Creation

## `heroku create --stack cedar`

<!SLIDE>

# Instant Deployment

## `git push heroku master`


<!SLIDE>

# Demo!

### Spring MVC Application on Heroku
