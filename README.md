## Metrics After Hardening / Security Controls
## For the "AFTER" metrics, Network Security Groups were hardened by blocking ALL traffic with the exception of my admin workstation, and all other resources were protected by their built-in firewalls as well as Private Endpoint
![image](https://github.com/user-attachments/assets/e85907eb-3bd5-4f75-8dbf-bc6ad326868e)

![image](https://github.com/user-attachments/assets/b2aacb16-ffaa-44ee-b371-8903aa8f4b62)


## Conclusion

In this project, a mini honeynet was constructed in Microsoft Azure and log sources were integrated into a Log Analytics workspace. Microsoft Sentinel was employed to trigger alerts and create incidents based on the ingested logs. Additionally, metrics were measured in the insecure environment before security controls were applied, and then again after implementing security measures. It is noteworthy that the number of security events and incidents were drastically reduced after the security controls were applied, demonstrating their effectiveness.

It is worth noting that if the resources within the network were heavily utilized by regular users, it is likely that more security events and alerts may have been generated within the 24-hour period following the implementation of the security controls.
![image](https://github.com/user-attachments/assets/c47cdf46-f66f-42a8-b583-34ca0ac18816)
