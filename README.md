clc; 
clear all; 
 
x0 =0; 
v = 20; 
t = 1:50; 
for i=1:numel(t) 
    x(i) = x0 + v*t(i); 
    z(i)=100; 
    plot(x(i),z(i),'*') 
    axis ([0 1000 0 200]) 
    drawnow(); 
    pause(0.05) 
end 
plot(x,z) 
axis ([0 1000 0 200])


<!---
Mrunmay2528/Mrunmay2528 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
