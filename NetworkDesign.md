![image](https://github.com/user-attachments/assets/0b1f8b12-d46f-4bf7-b0fb-0afc8c72497e)


**Part 2. Network Scalability Analysis**

Recall the e-commerce website scenario we discussed earlier. Given the
expected surge in traffic, analyze the provided network topology
diagram. Identify potential bottlenecks and areas where scalability
might be a concern. Propose specific strategies to improve the
network\'s scalability and performance to ensure a seamless user
experience during the peak traffic period. Consider factors such as
increased user demand, new applications, and security threats.

**Potential Bottlenecks**

**Network Congestion**

-   Each server is equipped with a 1Gbps connection, which may not
    > provide enough aggregate bandwidth during peak usage times.

**Single Points of Failure**

-   Without redundancy in network paths, a failure in any single
    > component could lead to service disruptions.

**Security Vulnerabilities**

-   Higher traffic volumes can attract cyber threats, making it
    > essential to implement strong security measures.

**Proposed Strategies for Improvement**

-   **Increase Bandwidth**

    -   Upgrade network connections to higher speeds, like 10Gbps, to
        > handle more traffic.

-   **Create Backup Network Paths**

    -   Set up multiple routes in the network to improve reliability and
        > reduce the chance of failures.

-   **Use Firewalls and Intrusion Detection Systems (IDS)**

    -   Improve security measures to protect against cyber threats
        > during busy times.

-   **Use Load Balancers for Managing Traffic**

    -   Spread incoming requests across several servers to avoid
        > overloading any single server.

![](vertopal_e4ec2b7b54284c73ae777db1d1026493/media/image2.png){width="5.052917760279965in"
height="3.8255161854768156in"}

![image](https://github.com/user-attachments/assets/b98e1711-78be-4335-905b-86d51d6b48ff)

The second topology for the e-commerce website is justified by its focus
on improving network performance and scalability. Key features include
having multiple network paths to ensure reliability, allowing data to
reroute if one path fails. This setup minimizes service disruptions,
which is crucial during busy times.

Security measures like firewalls and intrusion detection systems (IDS)
are also important. They help protect user data from cyber threats that
can increase with higher traffic.

Additionally, using load balancers helps manage incoming traffic by
spreading user requests across several servers. This prevents any single
server from becoming too busy, ensuring fast response times.

Overall, this topology creates a strong and efficient network that can
handle growing demands while providing a secure and smooth experience
for users.

  ------------------------------------------------------------------------------
  Criteria          Excellent \| 10pts Good \| 7pts        Needs Improvement \|
                                                           4pts
  ----------------- ------------------ ------------------- ---------------------
  **Network         Accurately         Identifies key      Identifies some basic
  Analysis**        identifies         network components  network components
                    potential          and some potential  but lacks a
                    bottlenecks,       bottlenecks.        comprehensive
                    security risks,                        analysis.
                    and capacity                           
                    limitations.                           

  **Scalability     Proposes multiple  Proposes some       Proposes limited
  Planning**        relevant solutions relevant            scalability
                    and provides       scalability         strategies.
                    detailed           strategies but      
                    explanations,      lacks detail.       
                    including                              
                    potential                              
                    drawbacks and                          
                    benefits.                              

  **Evaluation of   Proposes           Provides a basic    Does not evaluate the
  Solutions**       comprehensive      evaluation of the   proposed solutions or
                    scalability        proposed solutions, provides a
                    strategies,        but lacks depth.    superficial
                    including specific                     evaluation.
                    recommendations                        
                    for hardware                           
                    upgrades, software                     
                    configurations,                        
                    and network                            
                    optimizations.                         

  **Proposed        Provides a         Provides a basic    Does not provide a
  Design**          detailed and       design but lacks    clear and detailed
                    well-justified     specific details    design.
                    design, including  and justifications. 
                    network diagrams,                      
                    configuration                          
                    details, and                           
                    implementation                         
                    plans.                                 

  **Evaluation and  Provides a         Provides a basic    Does not evaluate the
  Justification**   thorough           evaluation of the   proposed solutions or
                    evaluation of the  proposed solutions, provides a
                    proposed           but lacks depth.    superficial
                    solutions,                             evaluation
                    considering                            
                    factors like cost,                     
                    complexity, and                        
                    potential impact.                      

  Score:                                                   /50
  ------------------------------------------------------------------------------
