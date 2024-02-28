# Load_Performance_Testing_Jmeter

Dear viewers, 

I’ve completed performance test on frequently used API for test App. 
Test executed for the below mentioned scenario in server 000.000.000.00. 

1400 Concurrent Request with 1 Loop Count; Avg TPS for Total Samples is ~ 140 And Total Concurrent API requested: 8400 Error Rate  0%.

1800 Concurrent Request with 1 Loop Count; Avg TPS for Total Samples is ~ 178  And Total Concurrent API requested: 10800 Error Rate  0%.

2200 Concurrent Request with 1 Loop Count; Avg TPS for Total Samples is ~ 188 And Total Concurrent API requested: 13200 Error Rate  0% .

2600 current Request with 1 Loop Count; Avg TPS for Total Samples is ~ 249 And Total Concurrent API requested: 15600 Error Rate  0%.

3000 Concurrent Request with 1 Loop Count; Avg TPS for Total Samples is ~ 288 And Total Concurrent API requested: 18000 Error Rate  0% .

3500 Concurrent Request with 1 Loop Count; Avg TPS for Total Samples is ~ 305 And Total Concurrent API requested: 21000 Error Rate  0.08% .

While executed 3500 concurrent request, found  16 request got connection timeout and error rate is 0.08%. 

Summary: Server can handle almost concurrent 19500 API call with almost zero (0) error rate.

Report:

<img width="376" alt="image" src="https://github.com/rifat12927/Load_Performance_Testing_Jmeter/assets/66294509/c733f545-6f6d-4c77-981f-45178c6cb0e0">
<img width="716" alt="image" src="https://github.com/rifat12927/Load_Performance_Testing_Jmeter/assets/66294509/f8615f58-218f-4913-8ead-73a87e8b579c">

