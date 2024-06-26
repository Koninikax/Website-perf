# Website-perf
Website performance analysis; evaluating various metrics related to a website’s functionality, user engagement, and overall success in achieving business goals.
## Session Trends
![image](https://github.com/Koninikax/Website-perf/assets/96631757/9be6306d-2368-45be-8548-8d0d1d1523bd)

From the graph, we can observe there are some fluctuations in the number of users and sessions, possibly indicating daily cycles or specific high-traffic periods. Both users and sessions appear to follow a similar trend, which is expected as more users generally mean more sessions. Some peaks might correspond to specific marketing activities, promotions, or events.
## User Engagement
![image](https://github.com/Koninikax/Website-perf/assets/96631757/8f1e43d9-c5b1-4d53-b488-e0bfea0385f1)

The user engagement analysis provides insights into how visitors interact with the website:

Average Engagement Time per Session: The time spent per session shows fluctuations over the observed period. There are noticeable peaks, suggesting times when users were particularly engaged, potentially due to specific content releases or events.

Engaged Sessions per User: This ratio fluctuates slightly but generally indicates that a good portion of sessions per user are engaged. Peaks in this metric could correspond to times when users find the content more relevant or engaging.

Events per Session: The count of events per session remains relatively consistent but does show some variation. Peaks here could indicate more interactive content or features being used by visitors.

Engagement Rate: The engagement rate over time shows how many sessions are considered engaged out of the total. There are some ups and downs which may relate to how different content resonates with users or how effective certain user acquisition channels are.


![image](https://github.com/Koninikax/Website-perf/assets/96631757/bc2c3730-a735-4fe0-a030-3ec79d2977cd)

Average Engagement Time vs Events per Session: There appears to be a concentration of data points at lower average engagement times with a wide range of events per session. 
As the average engagement time increases, the number of events per session tends to cluster more narrowly around lower values.

Average Engagement Time vs Engagement Rate: There is a clear trend where sessions with very low engagement times have a broad range of engagement rates, but as engagement time increases, the engagement rate converges towards higher values.

Engaged Sessions per User vs Events per Session: Most data points cluster at lower values for both metrics, with few users having a high number of engaged sessions or events per session.

Engaged Sessions per User vs Engagement Rate: There is a strong positive correlation between engaged sessions per user and engagement rate, especially noticeable at higher values of engaged sessions per user.

## Channel Performance Analysis
![image](https://github.com/Koninikax/Website-perf/assets/96631757/3d0300f9-4951-4966-a081-fc7d0e6cd95d)

The data illustrates significant variations in performance across different channels, highlighting the strengths and weaknesses of each in driving traffic, engaging users, and encouraging interactions. The high performance of ‘Organic Search’ in driving traffic contrasts with its lower relative engagement and events metrics, suggesting quantity over quality of visits. In contrast, ‘Referral’ and ‘Organic Video’ channels, while not leading in volume, excel in engaging users deeply, pointing to potential areas for leveraging these strengths in marketing strategies.

## Forecasting website traffic

![image](https://github.com/Koninikax/Website-perf/assets/96631757/e6ccf4fa-90d6-48ea-9fb1-04109ba93574)
 In our plot, the PACF shows a significant spike at lag 1 and then cuts off, suggesting an AR part of order 1. Therefore, p=1.
 The ACF plot in our case tails off gradually, but considering the first significant spike is essential. Since the spike at lag 1 is significant and there’s a gradual tailing off rather than a sharp cut-off, it suggests a potential MA component. However, the tailing-off nature complicates the exact determination of q, but a starting point of q=1 could be considered.

![image](https://github.com/Koninikax/Website-perf/assets/96631757/7fbe8c97-510d-49ad-81e2-479c8f92b916)
