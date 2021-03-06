---
title: Coursera - Collaborative Robot Safety, Design & Deployment
date: 2020-04-06
categories: safety
lang: en
---

Notes from Cousera class on 
[Collaborative Robot Safety: Design & Deployment](https://de.coursera.org/learn/collaborative-robot-safety)

# Key Take-away
* The compression constant of the human hand is: 75 N/mm
* The collaborative robots can typically handle a payload of 1-5 kg and would cost around $30-40K per application station.
* Categories of cobot include:
    * power and force limiting
    * Speed and separation monitoring
    * ...
* Cobot are not intrinsically safe: EAT needs to be assessed:
    * counter-example: a cobot holding a knife is not safe
* ISO TS 15066 based on Mainz University measures for:
    * Clamping force in N
    * Impact force in N
    * Pressure in N/m2
    * Compresison constant for different human body parts in N/mm




## Week 3
### Video Applications

0:19 - 0:36
"""
To date, collaborative robots have been used in material handling applications with payloads of up to 30 kilograms. 
Although at heavier payloads, they are restricted to moving slowly. Most applications are for payloads in the 1-5 kilogram 
range., marked from 19 seconds till 36 secondsTo date, collaborative robots have been used in material 
handling applications with payloads of up to 30 kilograms. Although at heavier payloads, they are restricted to moving slowly. 
Most applications are for payloads in the 1-5 kilogram range.
"""

2:05 - 2:23
'''
There's a large force sensor between the base of the robot and the floor. This force sensor records the normal forces during a training session. Then, if during operation, an unexpected force is detected, the robot will stop
'''

### Automation Application: Machine Tending
NTR

### Testing
[video1](https://www.coursera.org/learn/collaborative-robot-safety/lecture/5Tesa/testing-part-1)

6:08 - 6:30
```
Finally, risk reduction measures should be described. These might include reducing the robot speed when approaching pinch points, wrapping rigid objects with foam, tools that breakaway at certain forces and fixtures that are spring loaded and deflect if an operator is trapped by the robot.
```

5:45 - 5:53
```
It also includes the body part that could be contacted and the type of contact that might take place
```

5:22 - 5:45
```
For robots that fall under the category of power and force limiting, additional documentation is recommended, this includes the effect of payload which includes the robot moving mass, the end effector mass, the payload and the forward reflected inertia of the drive train which can be quite large.
```

4:50 - 5:00
```
Section seven of 15066 addresses verification and validation but not collision force testing
```

2:35 - 2:55
```
Broadly, there are two different types of collisions with people defined in ISO 15066. Collisions in free space, which are called transient collisions, and collisions against a rigid surface, which are called quasi-static collisions
```

0:33 - 0:45
```
However, to date, 15066 says very little about how to test robots to determine if they meet the safe forces described in the standard
```

### Testing 2
### Additional Ressources

[GTE force testing fixture on youtube](https://www.youtube.com/watch?v=4Q92fAOqTSc&feature=youtu.be)
[GTE product page](https://www.gte.de/product/force-measuring-systems-for-collaborating-robots/?lang=en)

[Quasi static vs Transient](https://www.youtube.com/watch?v=dP_CX8MGlx4&feature=youtu.be)
* Quasi-static: crushing
* transient: human body free to move

## ISO TS 15066 - RIA TR R15.606-2016    

* [Table 1 - Injury severity, exposure, and avoidance factors](https://d3c33hcgiwev3.cloudfront.net/LZ49q7B0EeiWawql-q9FAg_2de92870b07411e88a4eb579a1c3d105_Table-1---Injury-severity_-exposure_-and-avoidance-factors.pdf?Expires=1585785600&Signature=lUlBdT1ySRVMC6a2BcR7C5Sa1wMHYV5-~2BkFceGG4v~p~YKo~LN1FqP5HZjKsW4mMEqhziAxDjZGSHElJua01ogf7ZrpdyjRnEkgi-gAsT6Wp2xLmIlSLjxQrfbrGaXzWYU5asw5zh4SSqLRLK9D58isvYxxYr9oWFXknlpA5A_&Key-Pair-Id=APKAJLTNE6QMUY6HBC5A)
* [Table 2 - Risk level decision matrix](https://d3c33hcgiwev3.cloudfront.net/LZ4WDLB0Eeiu9BLDf-7i5A_2de99da0b07411e88d141f6854e3a104_Table-2---Risk-level-decision-matrix.pdf?Expires=1585785600&Signature=BNlo5F9KasugvRc1iChGVt~pOmT0dlYFh5~xwoo5sxV1B~QzjG7G63Tju5bD80zpssxVZza73SzvPvYXSoBTsN-z9w4laH225RnRXeWjKiZOxELbRksldQpgtlwrPddTHucs8Bwt6mqFA8TlGTd2YOMAQjB48rOiqHGwNDCOO-M_&Key-Pair-Id=APKAJLTNE6QMUY6HBC5A)
* [Table 4 - Minimum risk reduction measures as a function of the risk level](https://d3c33hcgiwev3.cloudfront.net/LZ5kyrB0EeitmQqVuF7yZg_2dee0a70b07411e8a2fc69f90a9c1b90_Table-4---Minimum-risk-reduction-measures-as-a-function-of-the-risk-level.pdf?Expires=1585785600&Signature=X6L24SSxF5kWtgZnQVBt~8DAq7xwVuPwGIhhJI~~cJKUTKlg07I3WpOHxu-rlNVVfEkW8Z6MTyIPkGDPr0ze8l0zUjFJbn87-U-L2NBf93rivjYqfv0INBZ-E-78Xo474gLqoVgdGibfKFo-qxokJwKtE5iV-o9u9Ju20mGA100_&Key-Pair-Id=APKAJLTNE6QMUY6HBC5A)
* [Table 5 - Minimum functional safety performance](https://d3c33hcgiwev3.cloudfront.net/LZ3vNbB0EeibgBLbO2j-4A_2dede360b07411e89888854a4cd979ed_Table-5---Minimum-functional-safety-performance.pdf?Expires=1585785600&Signature=CcP8ij2FzFgU550tqjlAsl4d3mNeYezZuAOiiiig7TeTnJP~KtpT~WdrqZiFbo2qnOLxp1Y43Es0jZ8EUcJnJW1EDmRQuixGxwIrGVEWWzR3Reblt1SGHg0qJPbp1V3NQ7PuOFjo1pV1q2ypQl934SjjVGpcl4wSErBSrOgMYpA_&Key-Pair-Id=APKAJLTNE6QMUY6HBC5A)
* [Table 6 - Safety toolkit](https://d3c33hcgiwev3.cloudfront.net/Lb-AcLB0EeiIWQ7qQVoxgg_2de7a1d0b07411e890627db2b1703caf_Table-6---Safety-toolkit.pdf?Expires=1585785600&Signature=RRrrPHrM3Rbv6mNWNVg0QB4yHWof6NuhVS7CBm-69egFSoMLSC9nDEHIIVqMv~wXE1x8YBQEbXVT2zx2crHt7Z~pXAkI-G2ytJR9O4~XQuULyOWHwqZFZ8oXkhndyq0wsZOTatcgjl4K2GlKh00WbIw93vv~UoqbtvFlm61MfUw_&Key-Pair-Id=APKAJLTNE6QMUY6HBC5A)
* [Table A.2 - Biomechanical limits](https://d3c33hcgiwev3.cloudfront.net/Lb03a7B0EeitmQqVuF7yZg_2df647d0b07411e88f945f0072a1b689_Table-A.2---Biomechanical-limits.pdf?Expires=1585785600&Signature=MDZ9eHdjNkN96vHijgNwE9MxGRT8WlGL3rZ~J8XMWQKnuRSuNWc8Pn7E-aFjVJWOZLchaJfuPx9PydJAFKDJw8aEo6RUM8jbHkgtbJcPQhJ0fPttqBMBPH0JA8plj-Zn8GkHOZjlogDjx8DDaubOJbZzxcyamGJ71~3pG6Yq2Kg_&Key-Pair-Id=APKAJLTNE6QMUY6HBC5A)
