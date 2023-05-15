# NGO Aid Web Application

This web application allows NGOs to individuals who have received aid or donations. Thye can be searched by name or ID number to check whether a person is eligible to receive aid or whether they have already received aid.
# Problem Statement:
 
In recent months, concerns have been raised about the unequal distribution of donations to needy individuals in Pakistan. While many NGOs and charities are working to provide essential supplies such as food, shelter, and clothing to those in need, there are growing concerns that these donations are not reaching everyone who requires assistance.
 
According to some reports, certain NGOs and charities are focusing on providing aid to individuals who are more visible or have greater influence, rather than prioritizing those who are most in need. This has resulted in a situation where some individuals receive multiple donations from different organizations, while others receive little or no assistance.
 
In a recent survey of individuals who have received aid from NGOs and charities, many expressed frustration at the unequal distribution of donations. One respondent, who requested anonymity, stated that "It's not fair that some people are getting multiple donations while others are being left out completely. We all need help, and it should be distributed equally."

# Let’s get started
Real World Case:
Headline: "Charity donations not reaching the neediest in Pakistan, says report"
Source: The Guardian
Date: April 14, 2021

According to a recent report by the Human Rights Commission of Pakistan (HRCP), charity donations in the country are not being distributed equally to the neediest people. The report found that some of the largest charities in the country were failing to reach the most vulnerable groups, including widows, orphans, and disabled individuals, due to bureaucratic obstacles and a lack of transparency in the distribution process. The report also found that some charities were prioritizing political connections and personal interests over the needs of the community.
The unequal distribution of charity donations has had serious consequences, especially during the COVID-19 pandemic, with many vulnerable families struggling to access basic necessities such as food, shelter, and healthcare. The HRCP has called for greater transparency and accountability in the distribution of charity donations and has urged the government to take action to ensure that aid reaches those who need it the most.
# They need to overcome these things:
1. Financial Mismanagement: NGOs may face financial mismanagement issues, such as misusing or embezzling funds, poor accounting practices, or overspending on administrative costs.
2. Eye on Needy One: NGOs need to make a record of the data of every needy person for now and future.
3. Mission Drift: NGOs may lose sight of their original mission and become involved in activities that do not align with their core values.
# Solution:
We have an easy and convenient way to make this possible.
The EquiDonate app will make every NGO take all data of their needy person and take a decision to give them a donation or not by verifying their information from NADRA.
 
 The main purpose is Unlocking the Power of Equality in Giving: Ensuring Fair, equitably and Just Opportunities for Every needy person
#Wroking
·        We use Oracle Apex because it is easy to showcase our data in low code. Data can be presented in charts graphs and such as many          other awesome features.
·        First we collected all data from NGOs as well as needy people.
·        Verify the data that the person is really needed or not.
·        Our app presents a graph that shows the income even the family member of that person.
·        One form for the donation which can be used by NGOs in which NGOs will enter the detail of the person who takes a donation from that NGO. So this will be helpful for other NGOs able to check the details of that person this person already take a donation from another NGO.

# Workflow
So, in our Oracle Apex application, we have one table for personal details like CNIC, ADDRESS, NAME, INCMOE, etc. In which we check whether a person deserves a donation by checking his income. So we generate checks using a SQL query on income. We also display a graph of a person's income on the dashboard.
 
Next, we have a second table for NGOs, in which we include the NGO's name, address, the total amount they have to donate, details of the items they donate, etc. So in this, we display the NGO donation graph on the dashboard.

# Future goal
1.  But then we also think that if a needy person has taken three sacks of flour, which have run out because there are more people in his household if he needs flour again, so here we need to determine a period for which these three bags of flour are being given to him for one month. Next month, it will be given again.
2. Second, from a business point of view, we can also sell our database to new NGOs who want to join our network.


# Features
The following features are included in this web application:

Search for individuals by name or ID number
View individual details, including aid received from NGO'S
Add new individuals to the database

# Technologies Used
This web application was built using the following technologies:

Oracle Apex

# usage
Once the web application is running, NGOs can log in and search for individuals by name or ID number. They can then view the individual's details, and aid received information, and add new individuals to the database..
