Use Cases & Requirements for Permissions for Geolocation on the Web
=====================================

Examples of permissions working within native applications to develop use cases for permissions on the web. 

## Introduction ##

There is a growing mountain of evidence [1][2][3][4][5][6][8] that some government and commercial institutions have exploited software, hardware, and laws to undermine individuals’ fundamental human right to privacy (see Article 12 of [9] and Article 8 of [10] for declarations of right to privacy). In the worst cases, misuse of personal information has led to serious privacy violations: individuals unjustly find themselves deprived of access to goods, services, or even employment because an institution has violated their privacy – without any avenue for recourse [1]. Where privacy has been erroneously violated, as in the case with mistaken identity or human error, it can take months or even years for an individual to have the damage undone [1][2][3]. In more severe cases, individuals have found themselves incarcerated for exercising their human right of freedom of expression [8]. This as a direct result of commercial entities providing personally identifiable information to law enforcement agencies of countries that have little or no respect for human rights [8]. In some states, such as the United States, individuals have virtually no legal right to control, modify, or access data about themselves [1][2]; nor can they see who can access that data, or who that data is being sold to (and for what purpose) [1]. Bottom line is: because of the Internet our privacy and reputation is more at threat than at any other time in human history [2].

In his book, Database Nation: The Death of Privacy in the 21st Century, Garfinkel [1] warns:

“Few engineers set out to build systems designed to crush privacy and autonomy, and few business or consumers would willingly use or purchase these systems if they understood the consequences. What happens more often is that the privacy implications of a new technology go unnoticed. Or if the privacy implications are considered, they are misunderstood. Or if they are understood correctly, errors are made in implementation. In practice, just a few mistakes can turn a system designed to protect personal
information into one that destroys our secrets.”

The roll-out of “advanced Web APIs”, which is really an euphemism for APIs that access device capabilities and other personally identifiable data, will add more data that needs to be carefully protected by all those involved: the public, businesses, browser makers, standards setting bodies, operating system vendors, hardware manufacturers, and law makers. A balance needs to be struct between adhering with local and international laws, protecting the rights of individuals, and being able to conduct business across the globe [8].

## Common Issues ##

When conducting this use case analysis it was found that a number of privacy and UX related issues continued to be occur:

* __Time duration:__ the permission alert / process gave no idication of how long the permission will remain in an not active or active state. 
* __How data is being used__: the permissions alert / process gave no indication of how the user's data would be used, and whether this would be sent to a third party, or who these third parties are.
* __Geolocation Provider:__ the permissions alert / process gave no indication of who the provider of the geolocation data is, or how to change this.
* __Prompt is Modal__: the user cannot fully view or interact with the underlying application to make an assessment of what the application might do with the positioning data, without first rejecting geolocation access to the website.
* __No Revoke__: If a user changes their mind about allowing location services, there is usually no way for them to revoke geolocation access without either quitting the application, uninstalling the application, or finding some other convoluted way to revoke access to geolocation services (e.g., having to globally disable location services on the device through the “Settings” menu). 

## Use Cases ## 
### Use Cases derived from Native Applications ###

Here is a collection of geolocation permissions flows from a number of high profile native applications featured in iOS and Android application stores.

In the book, The Future of Reputation: Gossip, Rumor, and Privacy on the Internet, Solove [2] argues that privacy can be evaluated in terms of confidentiality, accessibility, and control. I define these terms with the following questions:

Accessibility:
* Are options and information pertaining to privacy accessible to the end-user?

Control:
* Given the accessibility to privacy options, how much control does the system afford the end-user over privacy settings?

Confidentiality:
* Does the system afford to the end-user anonymity or alternative means of protecting their privacy?

#### iOS ####

#### Android ####

### Use Cases derived from Mobile Browsers ###

#### Chrome ####


#### Safari ####


#### Internet Explorer ####


#### Firefox ####


#### Opera ####


## Classification of Methods ##

The examples above show a range of differenct permissions model methods. These can be classified as follows:

## Other Issues ##

Click Through: modal confirmation dialog lead to ‘click fatigue’: whereby users simply become accustomed to clicking “OK” to every prompt without grasping the consequences of their actions

Privacy policies buried: “Settings” menu of the iPhone, under the “Legal” option, which contains about 50 pages of legalese and no searchable index!

## Requirements ##

### User Privacy Controls ###
List requirements
