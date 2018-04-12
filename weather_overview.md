---

copyright:
  years: 2015, 2016
lastupdated: "2016-07-01"

---

{:new_window: target="_blank"}
{:shortdesc: .shortdesc}
{:screen:.screen}
{:codeblock:.codeblock}
{:note:.deprecated} 

# About Insights for Weather
{: #about_weather}

Use Weather Company Data for IBM Bluemix to incorporate weather data from
The Weather Company (TWC) into your {{site.data.keyword.Bluemix}} applications.
{:shortdesc}

**This service is deprecated:** All instances of this service are deprecated. 
The revised service is available in Bluemix as Weather Company Data for IBM Bluemix.  
Current apps that use the Insights for Weather APIs will continue to work without 
any modifications for 90 days after the Weather Company data service is released on July 1 2016.
To take advantage of the newly added APIs and the improved pricing model, 
it is in your best interest to migrate to one of the new plans.
{:deprecated}

You can add weather observations and forecasts to your {{site.data.keyword.Bluemix_notm}} application and display the weather data
for an area that is specified by a geolocation by using the [REST APIs](https://twcservice.{APPDomain}/rest-api-deprecated/){:new_window}.
The Weather Company is the most comprehensive provider of historical and forecast
weather data. Data for all forms of weather, including precipitation, barometric pressure,
wind, and thunderstorms, is captured.

You can use the REST APIs to retrieve the following information:

* An hourly weather forecast for the next 24 hours that starts from the current time for a specified geolocation.
* A daily weather forecast for the next 10 days that includes forecasts for the daytime and nighttime segments for a specified geolocation. This forecast includes the forecast narrative text string of up to 256 characters with appropriate units of measure for the location and in the language requested.
* The current observed weather data for a specified geolocation. This weather data includes temperature, precipitation, wind direction and speed, humidity, barometric pressure, dew point, visibility, and ultraviolet (UV) radiation.
* The observed weather data for a specified geolocation and a specified time range. This data is sourced from physical observation stations. This API returns weather observations for current conditions and past observations up to and including the previous 24 hours.

## Feedback and support
{: #feedback_support}

If you have technical questions about creating an app with Insights for Weather,
post your question on [Stack Overflow](http://stackoverflow.com/search?q=weather+bluemix){:new_window}
and tag your question with **bluemix** and **weather**.

If you experience any issues with this service, use the [IBM developerWorks Answers forum](https://developer.ibm.com/answers/topics/insights-weather/?smartspace=bluemix){:new_window}.
Include the **insights-weather** and **bluemix** tags to allow IBM to support you better.

For information about troubleshooting problems with Bluemix, see [Troubleshooting](https://console.{DomainName}/docs/troubleshoot/troubleshoot.html){: new_window}.
For details about searching for information and asking questions through forums, and about contacting support, see [Getting customer support](https://console.{DomainName}/docs/support/index.html#getting-customer-support){: new_window}.
