## Progress repo of PID controller contribution to [ARVP](https://arvp.org/)

To do: 
- [X] Rewrite the node itself (interface layer)
- [X] Rewrite math in eigen
- [X] Test in simulation (gazebo) 
- [X] Do synthetic tests  
- [ ] Test in the pool  


## PID Performance Synthetic Test Comparison [Terminal IMG](https://github.com/user-attachments/assets/7ce4f6ff-2e25-4975-b5ae-d9ced179f271)

| Implementation | Avg Time per Update (micro s) | Total Time (s) | Relative Speed |  
|---------------|--------------------------|---------------|----------------|
| C++ (rclcpp + eigen)          | 1.96706                  | 0.196706      | 1×               
| Python (rclpy + numpy)       | 213.80                   | 21.3803       | 108.7× slower 






Demo explaining:


https://github.com/user-attachments/assets/fd431dcd-feb3-4e55-8f5a-2b2395aeb38e




