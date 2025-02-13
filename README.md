# Soccer-Player-Performance-Analysis

Conducted an in-depth analysis of soccer player performance using  SQL, Power BI, and to uncover trends, enhance scouting, optimize team strategies, and improve fan engagement.

## Problem Statement:
Analyze soccer player performance data using SQL, Power BI to gain insights into skills and trends.

## Business Use Cases:
Player Scouting: Identify high-potential players based on performance metrics for recruitment.

Performance Analysis: Assess player skills to optimize team formations and strategies.

Injury Prevention: Analyze physical attributes to reduce injury risks and improve fitness regimens.

Fan Engagement: Tailor marketing strategies using player performance data to enhance fan experience.

Contract Negotiation: Use performance insights to justify player salaries and contract terms.

## Approach:
Data Collection: Extract player performance data from databases using SQL queries.

Data Preprocessing: Clean the dataset to address missing values and standardize metrics.

Exploratory Data Analysis (EDA): Utilize Tableau or Power BI to visualize player statistics and trends.

Feature Engineering: Develop new metrics that enhance player evaluation and comparison.

Visualization and Reporting: Create interactive dashboards in Power BI or Tableau to showcase insights and recommendations.

## Goals :
Enhance Player RecruitmentLeverage data-driven insights to identify promising talent, enabling scouts and recruiters to make strategic decisions while aligning player selection with team requirements and budget constraints.

Optimize Team PerformanceEvaluate individual and team-wide metrics to assist coaches in creating optimal line-ups, refining game strategies, and maximizing performance through data-backed tactical adjustments.

Prevent Player InjuriesAnalyze physical metrics to pinpoint players at risk of injury, enabling the design of personalized fitness programs that reduce injury rates, enhance longevity, and maintain peak performance levels.

Boost Fan EngagementDevelop captivating visualizations and insights to deepen fan connection with player performance, driving personalized marketing campaigns and elevating the overall fan experience.

Support Contract NegotiationsEquip management with performance-based data to guide salary decisions, contract renewals, and transfers, ensuring player compensation aligns with their contributions and value to the team


## Data Cleaning and Transformation 
Checked and assigned appropriate data types to ensure accurate calculations and visualizations.

Removed duplicates based on a combination of Name + Age + Nationality + Club, as it is unlikely that two players would share the exact same combination of these key attributes.

The "Acceleration" column is critical for the analysis, and since some rows had missing values, those rows were removed


## Key Questions for Player Performance Analysis (SQL and Power BI):
1. Identify the top players by overall rating.
   
2. Calculate the average age of players in each position.
   
3.Determine the market value distribution among different nationalities.

4.Analyze performance metrics of players by club.

5.Find the most common positions played by top-performing players.

6.Identify players with the highest acceleration and agility ratings.

7.Calculate the average wage for players in each league.

8.Discover trends in player performance over the last few seasons.

9.Determine the potential vs. overall rating for young talents.

10.Identify players with multiple preferred positions and their performance metrics.

11.Analyze correlations between physical attributes and skill ratings.

12.Calculate the average market value of players by age group.

13.Identify players with the best free-kick accuracy.

14.Create visualizations for player statistics comparisons by club.

15.Develop queries to identify players at risk of being transferred based on performance.

# Dashboard ![image](https://github.com/user-attachments/assets/57706f88-d16f-4290-a627-4ee245b07472)

# Dashboard ![image](https://github.com/user-attachments/assets/0b628db2-5976-4f9d-ae01-7ea3ad6b3338)

# Full project https://github.com/yogeshbala-business-analyst/Soccer-Player-Performance-Analysis/blob/main/FIFA_OLYMPIC_PROJECT%20.pptx

## Identify The Top Players By Overall Rating
Findings:

Cristiano Ronaldo has the highest overall rating.
Lionel Messi closely follows with a high rating.
Manuel Neuer and Neymar share similar high ratings.
De Gea, Eden Hazard, and Gonzalo Higuaín have consistently high ratings.

Insights:

Cristiano Ronaldo and Lionel Messi's ratings reflect their exceptional skills and dominance in soccer.
Manuel Neuer and Neymar's ratings indicate their significant impact on the field.
De Gea, Eden Hazard, and Gonzalo Higuaín demonstrate strong proficiency and consistency in their performance.

Overall:

The analysis highlights these players as key figures in soccer, showcasing their influence and prominence in the sport.

![image](https://github.com/user-attachments/assets/f017ed17-a893-458a-979f-6ac42e63386f)

# Calculate the average age of players in each position
   GK: Goalkeeper - 26.11  
   CDM: Central Defensive 
   Midfielder - 25.79
    CB: Centre  Back - 25.77
    RB: Right Back - 25.13
    LB: Left Back - 25.03 
     ST: Striker - 24.85
    RM: Right Midfielder - 23.65

  ![image](https://github.com/user-attachments/assets/a6ec31e7-2775-4121-bf71-3a753ccfcb22)

 
#### Analysis:

Ages 24 to 26 typically represent a player’s prime years in professional sports, where they combine physical peaks with a mature understanding of the game. 

This suggests that teams prioritize players in their peak years across all positions, likely to optimize both physical performance and tactical experience.

there are some positions with slightly lower average ages (like CM and RW). 

This might suggest a strategy of investing in younger, potentially high-growth players for these roles, or perhaps a preference for more experienced players in other positions.

# Determine The Market Value Distribution Among Different Nationalities
![image](https://github.com/user-attachments/assets/acd68624-5dc9-4518-9346-956e600b2d92)

### Market Value Distribution by Nationality –

#### Top Market Value Nations:
Brazil (€472M) and Argentina (€461M) lead, highlighting the global demand for South American talent
.
#### European Stronghold:
France, Spain, Germany, and Portugal hold high values (from €272M to €381M), driven by strong leagues and player development.

#### Value Gap:
 There was a significant drop in market value for countries like the Netherlands (€159M) and Chile (€152M).

#### Strategic Takeaway:
Focus recruitment in Brazil/Argentina for emerging talent and in Europe for experienced players.


# positions played by top-performing players

Among the top-performing players, the most common position is GK (Goalkeeper) with 11 players.

 This is followed by LW (Left Wing) with 4 players.
 The least common positions are RM (Right Midfield),
  CM (Central Midfield), and CAM (Center Attacking Midfield), each with 2 players.

 ![image](https://github.com/user-attachments/assets/153a5416-d76f-4622-80ec-9069faccba46)


The dominance of goalkeepers in the top-performing list highlights the importance of a strong defensive foundation in modern football. The prevalence of left-wingers suggests a preference for attacking play from the left flank, possibly due to the skill sets of players like Neymar and Hazard.

The less common positions of RM, CM, and CAM may indicate a shift in modern tactics, with a focus on defensive stability and counter-attacking football.


## Analyze performance metrics of players by club. Performance Metrics: Various attributes such as acceleration, agility, dribbling, and shooting stats


![image](https://github.com/user-attachments/assets/9354224a-e1b1-44cf-a7f1-a9cca29818ad)


#### Insights 
These clubs likely maintain high standards in their player recruitment and training, ensuring that players meet or exceed certain performance thresholds.

With overall ratings averaging above 70, these clubs possess well-rounded squads with balanced skill levels, suggesting depth and versatility across their rosters.

High ratings in physical metrics, such as Acceleration, Agility, Stamina, and Sprint Speed, indicate that these clubs value not only technical skill but also physical resilience and agility.

This makes them competitive in both defensive and offensive play, especially in high-paced matches.

# Players With The Highest Acceleration And Agility Ratings

## Key Points:

Agility: Players like Neymar, E. Hazard, and A. Gómez are renowned for their ability to change direction quickly, making them difficult to defend.

Acceleration: Players like P. Aubameyang and Neymar possess exceptional acceleration, allowing them to exploit space and create scoring chances.


![image](https://github.com/user-attachments/assets/f0243cb9-4d07-415a-8b95-6f10dc3ceecf)


Combined Attributes: Players who excel in both agility and acceleration, such as Neymar and E. Asante, are highly effective attacking players.

Overall, agility and acceleration are essential attributes for top-level soccer players. Teams that can identify and develop players with these qualities can gain a significant advantage on the field.


# Determine The Potential Vs. Overall Rating For Young Talents

![image](https://github.com/user-attachments/assets/7bb22dac-f1f5-49fe-a335-6b467e9694d5)

### Young soccer players' skills and potential develop over time Ratings:
Rapid Growth: Between ages 16 and 18, players experience significant improvement in both their current skill level (overall rating) and their future potential. This is due to focused training and gaining experience. 

#### Growth Highland :
 After age 18, the rate of improvement slows down. Players reach a point where their skills align more closely with their maximum potential


# Identify Players With Multiple Preferred Positions And Their Performance Metrics

Among 17,845 players, 8,169 play multiple positions. Multi-position players, especially those with high overall ratings, provide significant strategic benefits.

Their adaptability makes them valuable assets in a lineup, as they can cover gaps caused by injuries or tactical shifts. 
Identifying high-rated multi-position players

 (e.g., those rated 80 and above) can highlight key talents who offer both high performance and flexibility.


![image](https://github.com/user-attachments/assets/fcdd1b0b-b24b-45e7-9129-13dfdbcaa9b9)

Multi-Position Player Insights

Total Players Analyzed: 17,845.

Multi-Position Players: 8,169 (45.8%).

#### Strategic Benefits:
High adaptability to cover injuries or tactical changes.

Valuable assets in dynamic lineups.

#### High-Rated Multi-Position Players:
Focus on players rated 80+ for optimal performance and flexibility.

#### Key Insight:
Multi-position players with high ratings are critical for maximizing team versatility and efficiency.

Analyze Correlations Between Physical Attributes And Skill Ratings
The strong positive trend here suggests that players with high sprint speed are also often effective finishers.

 This combination allows players to quickly get behind defenses and capitalize on scoring opportunities with precise finishing.


![image](https://github.com/user-attachments/assets/1f90264b-b933-40b0-8805-124b3d737929)


## Speed and Scoring:
Fast players are often good at scoring goals. This is because they can quickly get past defenders and have more time to shoot.


Players with high stamina tend to be better at intercepting passes, as stamina supports sustained focus, agility, and movement over the entire game. High-stamina players can press and cover more ground, increasing their chances of disrupting the opposing team’s play by intercepting passes.

Stamina and Interceptions: Players with high stamina can run for longer periods, which helps them intercept passes from the opposing team


![image](https://github.com/user-attachments/assets/4cfeb4b0-7ef4-4493-bd47-62d0af870c68)


In essence, these physical attributes are crucial for a soccer player's success. By understanding these connections, we can better appreciate the skills of top players and the tactics used in the game.

## The Average Wage For Players In Each League


This breakdown of teams based on their average wage highlights significant wage disparities across clubs, which can offer insights into how player salaries align with club prestige, market influence, and league competition level

![image](https://github.com/user-attachments/assets/b2b7494b-f613-4ac1-84e7-ae3d36a42263)


High Wage Clubs (Average Wage Euros)
Top European Clubs: FC Barcelona, Real Madrid, Bayern Munich, Juventus, Chelsea, and Manchester United are all globally renowned clubs with large fan bases, substantial revenue streams, and frequent participation in prestigious leagues and tournaments like the UEFA Champions League.

Low Wage Clubs (Average Wage 100 Euros)
Smaller and Lower-Division Clubs: SC Fortuna Köln, Werder Bremen II, and SG Sonnenhof GroBaspach operate with significantly lower budgets, often from lower or secondary leagues.

The Average Market Value Of Players By Age Group
## insights and Interpretations:

#### Prime Years (26-30): 
Players in this age group exhibit the highest average market value, reflecting their peak physical and technical abilities. They are often sought after by top clubs due to their consistent performance and ability to contribute immediately.

#### Early Career (21-25):
 This age group demonstrates significant potential and is valued for their future development. Clubs invest in these players, anticipating their growth into top-tier talents.


![image](https://github.com/user-attachments/assets/a973b4af-bcc4-48d0-8dac-285cfb9ac73b)

#### Experienced Players (31-35):
While their physical attributes might decline, these players possess invaluable experience, leadership qualities, and tactical knowledge. Their market value reflects their ability to guide younger players and contribute to team success.

#### Young Talents (16-20):

This group's value is primarily based on their raw potential. Clubs invest in young players with exceptional talent, hoping to nurture them into future stars.

#### Master (36+):

The declining physical abilities of players in this age group lead to a significant decrease in their market value. However, their experience and leadership skills can still be valuable assets for certain teams.


#### Based on the observed trends in the overall player rating over age, here are three insights:
Rapid Growth Phase (Ages 16-25):Players experience the fastest growth in their overall rating between ages 16 and 25, with ratings jumping from around 65 to 92. This indicates that the most significant improvements in skill and performance happen early in a player's career, likely due to intense training, skill acquisition, and physical development.


![image](https://github.com/user-attachments/assets/f02877d6-08da-494b-a59c-efa8ff8f1601)

#### Peak Performance and Stability (Ages 25-32)

Between the ages of 25 and 32, players reach and maintain their peak performance, with ratings stabilizing at around 92-94. This plateau suggests that players’ physical and technical abilities are well-developed and refined, allowing them to consistently perform at a high level.


![image](https://github.com/user-attachments/assets/c60ab1af-4df3-4409-90e6-01003f9ca89a)

#### Gradual Decline Phase (Post-36):

After age 36, a slow but noticeable decline in rating begins, likely due to the physical toll of the sport. This gradual decrease reflects the natural aging process, where factors like endurance, agility, and recovery times may start to impact performance despite accumulated experience and skill.
These insights illustrate a typical career trajectory, emphasizing the importance of player development in early years, peak physical and skill-based consistency in late 20s to early 30s, and the gradual performance impact of aging.


# Recommendations

1) Enhance Player Recruitment

Identifying Young Talent:

Potential vs. Overall: Use this metric to identify players under 25 with significant room for improvement.
Positional Analysis: Analyze players' performance within their specific positions to identify hidden gems.

2) Optimize Team Performance :
   
Forming Lineups: Create effective lineups by considering players' strengths and weaknesses.
Identifying Multi-Position Players: Utilize players who can play in multiple positions to increase squad flexibility.

4) Prevent Player Injuries

Monitoring Physical Attributes:
Key Physical Attributes: Focus on physical attributes like stamina, balance, and acceleration, especially for defensive and midfield roles.
Injury Prevention: Monitor players' physical condition to reduce the risk of injuries.

4) Boost Fan Engagement:
Highlighting Popular Players: Showcase popular players to increase fan engagement and loyalty.

Leveraging Social Media: Use social media to connect with fans and share player updates.

Transfer Market Strategies:
Wage Performance Ratio: Identify players who are overpaid or underpaid relative to their performance.

Transfer Risk: 

Assess the potential risks and rewards of transfer deals.

Player Value: Use data to determine the fair market value of players.

By implementing these recommendations, teams can make informed decisions, optimize player performance, and enhance overall team success.







