# Electoral Systems of the Lower House in Latin America and its Reforms 

Welcome to the GitHub repository of the database "Electoral Systems of the Lower House in Latin America and its Reforms," maintained by members of the Political Reform Observatory in Latin America.

## Contents

- [Summary](#summary)
- [Description](#description)
- [Citation](#citation)

## Summary

The database contains information on electoral reforms concerning the regulations governing electoral systems of the lower house in 19 Latin American countries. This includes modifications to the principle of representation, electoral formula, existence of special constituencies, house size, number of electoral districts, voting structure, mandate duration, electoral threshold, and the possibility of reelection and recall.

The review of regulations commenced from the year of each country's transition to democracy based on the framework proposed by Alcántara, Páramo, Freidenberg, and Déniz (2006).

For countries with gradual political change processes, the beginning of the third wave of democracy 
in Latin America (Huntington, 1991) is used as the basis. 

Members of the Observatory of Political Reforms in Latin America collected and coded the information. The information collection managers are Karolina Monika Gilas (Faculty of Political and Social Sciences, UNAM) and Luciana Modica (National University of Río Cuarto, Argentina), the information coding manager is Carlos Guadarrama Cruz (FLACSO, Mexico).

## Description

The directory `./Data/` contains the file `./Data/DD_SECB` where all relevant information regarding the database linked to the electoral systems of the Lower House in Latin America and its reforms is located. Specifically, the database consists of the following variables:

-   `country`: Name of the country where the reform of the legislative electoral regime in Latin America was implemented.

-   `cowcode`: Country code according to the “Correlates of War”, coding available at  https://correlatesofwar.org/data-sets/cow-country-codes.

-   `country_code`: Country code according to the three- letter ISO code: (e.g. ARG, MEX,SAL) available at http://utils.mucattu.com/iso_3166-1.html 

-   `cons_ctry_ref`: Records the consecutive number of reforms to the legislative branch in each Latin American country. E.g. Peru_1 Peru_2, Peru_3, Peru_4.

-   `year`: Calendar year corresponding to the reform of the legislative branch electoral regime in each Latin American country between 1949-2023.

-   `rep_prin`: Indicates the principle of political representation governing the election of the national lower house members of the legislative branch in each country. Its values are: [1] Majority, [2]: Proportional, [3]: Mixed.

-   `elec_form_n`: Indicates the vote to seat conversion formula established in the electoral reform for the lower house of the national legislative power. Its values are: [1] Distribution figure, [2]: D ́Hondt, [3] Electoral quotient or residue, 4]: Hare and largest remainder method, [5] Modified Hare, [6] Corrected Imperial, [7]: Weighted factor,  [8]: Webster,[9]: Hagenbanch-Bischoff, [10]: Integral Proportional System, [11]: Absolute majority,  [12] Relative majority, [99] N/A. 

-   `sp_circ`: Indicates the existence of special electoral constituencies assigned for the election of some   members of the lower house of the national legislative branch, e.g. indigenous communities, population abroad, etc. Values: [0]: Not specific, [1]: Specific.

-   `m_house`: Indicates the number of seats established by the electoral reform for the lower house of the national legislative branch.

-   `elect_dist_n`: Indicates the number of electoral districts established by the electoral reform for the lower house of the national legislative branch based on the principle of political representation. 

-   `vot_struct_n`: Indicates the type of vote established by the electoral reform for the lower house of the national legislative branch based on the principle of political representation. Its values are: [1]: Single-member candidacy, [2]: Closed and blocked list, [3]: Closed and non-blocked list, [4]:Closed unblocked list with double preferential voting, 5]: Closed unblocked list with optional preferential voting, [6]: Open list, [7]: Open list and preferential voting,  [8]: Single list linked to presidential candidacy,[9]: Preferential voting, [10]: Double simultaneous voting, [11]: Optional double preferential voting,[12]: Voting for a candidate on party lists, [13]: Mixed.

-   `mandate`: Indicates the duration of the mandate of the lower house members in years.

-   `elect_threshold`: Indicates whether an electoral threshold is provided for political parties to access the distribution of seats in the lower house of the national legislative branch. Its values are: [0]: Not specified, [1]: Specified. 

-   `leg_reelec`: Indicates how the electoral reform regulates the reelection of members in the lower house of the national legislative branch. Its values are: [1]: No reelection, [2]: No immediate reelection, [3]: Immediate reelection, [4]: Immediate and indefinite reelection, [5]: Immediate reelection for two terms. 

-   `legis_recall`: Indicates whether the legislative recall is provided for members of the lower house of the national legislative branch. Its values are:  No [0]: the regulations do not provide legislative recall, Yes [1]: the regulations provide legislative recall.

## Citation

``` r
Freidenberg, Flavia. Dir., 2023, “Electoral Systems of the Lower House in Latin America and its Reforms”, Observatory of Political Reforms in Latin America (1978-2023). Mexico City: Institute for Legal Research (IIJ-UNAM) and Washington, D.C.: Secretariat for Strengthening Democracy of the Organization of American States (SSD/ OAS), V2. DOI: https://doi.org/10.5281/zenodo.8368074
```