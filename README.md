# Aplicação prática R centralizar teste poisson

poissonteste <- rpois (200,2)
hist(poissonteste)

poissontestecentral <- poissonteste - mean (poissonteste) 
hist(poissonteste)
hist(poissontestecentral)
