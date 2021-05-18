# LOCAL STORAGE

rsistent local storage is one of the areas where native client applications have held an advantage over web applications. For native applications, the operating system typically provides an abstraction layer for storing and retrieving application-specific data like preferences or runtime state. These values may be stored in the registry, INI files, XML files, or some other place according to platform convention. If your native client application needs local storage beyond key/value pairs, you can embed your own database, invent your own file format, or any number of other solutions.

Historically, web applications have had none of these luxuries. Cookies were invented early in the web’s history, and indeed they can be used for persistent local storage of small amounts of data. But they have three potentially dealbreaking downsides:

* Cookies are included with every HTTP request, thereby slowing down your web application by needlessly transmitting the same data over and over
* Cookies are included with every HTTP request, thereby sending data unencrypted over the internet (unless your entire web application is served over SSL)
* Cookies are limited to about 4 KB of data — enough to slow down your application (see above), but not enough to be terribly useful

**Definition and Usage**


*The localStorage and sessionStorage properties allow to save key/value pairs in a web browser.*

*The localStorage object stores data with no expiration date. The data will not be deleted when the browser is closed, and will be available the next day, week, or year.*

The localStorage property is read-only.

Tip: Also look at the sessionStorage property which stores data for one session (data is lost when the browser tab is closed).

**Syntax**

*window.localStorage*


**Syntax for SAVING data to localStorage:**

*localStorage.setItem("key", "value");*


**Syntax for READING data from localStorage:**

*var lastname = localStorage.getItem("key");*



**Syntax for REMOVING data from localStorage:**

*localStorage.removeItem("key");*


## Example

The following example counts the number of times a user has clicked a button:


if (localStorage.clickcount) {
  localStorage.clickcount = Number(localStorage.clickcount) + 1;
} else {
  localStorage.clickcount = 1;
}
document.getElementById("result").innerHTML = "You have clicked the button " +
localStorage.clickcount + " time(s).";
