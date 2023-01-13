# EVA8_S3_BackPropagation
Back Propagation in Excel


# Step 1
See the figure of the neural network.  
List the relationships/equations between each neuron.  
h1 = w1 * i1 + w2 * i2  
h2 = w3 * i1 + w4 * i2  
a_h1 = σ(o1) = 1/(1+exp(-h1))  
a_h2 = σ(h2) = 1/(1+exp(-h2))  
o1 = w5 * a_h1 + w6 * a_h2  
o2 = w7 * a_h1 + w8 * a_h2  
a_o1 = σ(o1) = 1/(1+exp(-o1))  
a_o2 = σ(o2) = 1/(1+exp(-o2))  
E_total = E1 + E2  
E1 = 1/2 * (t1 - a_o1)^2   
E2 = 1/2 * (t2 - a_o2)^2  
