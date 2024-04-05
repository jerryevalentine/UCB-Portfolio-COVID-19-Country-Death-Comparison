# Unnecessary Covid Deaths #
USA LOST 480,758.0 compared to the world average across nations.  So this nation did WORSE than the average nation.  

# American Military Deaths in all conflicts #
it's estimated that over 1.3 million Americans have died in all wars combined, including the American Revolution, Civil War, World War I, World War II, the Korean War, the Vietnam War, the Persian Gulf War, the Iraq War, and the War in Afghanistan

# US Deaths from all conflicts in the 20th and 21st centuries #
Excluding the casualties from the Civil War and the Revolutionary War, the conflict that accounts for the most deaths among Americans is World War II (1939-1945). In World War II, the United States suffered approximately 405,000 military deaths. This figure includes deaths from combat, accidents, disease, and other causes related to the war. World War II remains one of the deadliest conflicts in human history, with millions of casualties worldwide.

# American military deaths in the conflicts of the 20th and 21st centuries #

116,516 (World War I) +
405,399 (World War II) +
36,574 (Korean War) +
58,220 (Vietnam War) +
383 (Persian Gulf War) +
2,448 (War in Afghanistan) +
4,431 (Iraq War) =

Total: Approximately 624,971 American military deaths in the conflicts of the 20th and 21st centuries.

# percentage of Soviet citizens that died in World War II #
Soviet casualties (26 million) by the estimated population of the Soviet Union in 1939 (168 million), then multiply by 100 to express the result as a percentage.

(26 million / 168 million) * 100 ≈ 15.48%

So approximately 15.48% of the Soviet Union's population perished during World War II.

# Stalin's regime #
Deaths directly or indirectly caused by Stalin's regime could be between 10 million to 30 million people.

# German Genocide #
--Jews: Approximately 6 million Jews were systematically murdered by the Nazis and their collaborators in what is commonly referred to as the Holocaust.
--Romani People (Gypsies): Estimates suggest that between 220,000 and 500,000 Romani people were killed by the Nazis.
--Soviet Prisoners of War: Around 2.8 to 3.3 million Soviet prisoners of war died in German captivity, primarily due to starvation, harsh conditions, and mistreatment.
--Disabled Individuals: An estimated 200,000 to 250,000 disabled individuals, including mentally and physically disabled individuals, were killed as part of the Nazi euthanasia program.
--Political Dissidents and Resistance Fighters: Tens of thousands of political dissidents, including communists, socialists, trade unionists, and members of resistance movements, were executed or died in concentration camps.
--Homosexuals: Exact figures are difficult to determine, but it's estimated that thousands of homosexuals were persecuted by the Nazis, with many being sent to concentration camps where they faced extreme hardship and death.
--Poles and Other Slavic Peoples: While precise numbers are debated, millions of ethnic Poles and other Slavic peoples, including Ukrainians, Russians, and others, were killed during the German occupation of Eastern Europe.
--Others: The Nazis also targeted Jehovah's Witnesses, Freemasons, black people, and others deemed undesirable or inferior according to their racial and ideological beliefs.
    
# % Jewish population that died during the Holocaust #
(6 million / 16.6 million) * 100 ≈ 36.1%
Therefore, approximately 36.1% of the Jewish population was killed during the Holocaust.

Here's a breakdown of what your code does:

    Retrieves the death rates per million for both countries.
    Retrieves the total number of deaths and population for the first country (USA).
    Calculates the predicted number of deaths for the first country (USA) if it had the same death rate as the second country (Peru), based on the population of the first country.
    Calculates the predicted number of deaths for the first country (USA) if it had the same death rate as the median death rate across all nations, again based on the population of the first country.
    Compares the predicted number of deaths with the actual number of deaths in the first country (USA) and prints out the difference.

Your code provides a way to understand the impact of different death rates on the number of deaths in a particular country. 
It's a straightforward and valid approach for comparing mortality rates between countries. 
However, it's essential to interpret the results with caution and consider other factors that might influence death rates,
such as healthcare systems, demographics, and government policies.

 determine if the difference in death rates between the USA and Peru is statistically significant. One commonly used test for comparing means between two groups is the independent samples t-test. However, since you're comparing death rates, you may want to use a variation of this test, such as the Welch's t-test, which is more robust when the variances of the two groups are unequal.

Here's a general outline of how you could perform this test:

    Formulate hypotheses:
        Null hypothesis (H0): There is no difference in death rates between the USA and Peru.
        Alternative hypothesis (H1): There is a difference in death rates between the USA and Peru.

    Collect data:
        You already have the death rates per million for both countries.

    Perform the statistical test:
        Calculate the test statistic (e.g., t-statistic) and its associated p-value using a suitable statistical test (e.g., Welch's t-test).
        The test statistic quantifies the difference between the mean death rates of the two groups, while the p-value indicates the probability of observing such a difference if the null hypothesis were true.

    Interpret the results:
        If the p-value is less than your chosen significance level (e.g., 0.05), you reject the null hypothesis and conclude that there is a statistically significant difference in death rates between the USA and Peru.
        If the p-value is greater than your chosen significance level, you fail to reject the null hypothesis, indicating that there is not enough evidence to conclude a difference in death rates between the two countries.

Here's a Python example using the SciPy library to perform Welch's t-test:
