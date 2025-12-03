# Orphanhood-and-wellbeing-in-baboons
In this study, we analyse the relationship between orphanhood and wellbeing in juvenile baboons using behavioural measures. Specifically, I focus on two dimensions of wellbeing: sociability and affectivity. In this regard, the general hypothesis is that **orphaned baboons will show poorer wellbeing than non-orphans**.

The indicators and models used are:

1) Displacement behaviour rate (indicators of anxiety and stress)

     1.1) Orphan vs non-orphans: Negative Binomial GLMM with a log link function

     1.2) Only orphan population: Negative Binomial GLMM with a log link function
     
  2) Time spent alone: proportion of time spent without any neighbors within 5 meters)

     2.1) Orphan vs non-orphans: Beta GLMM with a logit link function 

     2.2) Only orphan population: Beta GLMM with a logit link function
     
  3) Negative interactions (time spent in negative interactions and frequency):

    a) Duration of negative interactions:

      Orphan vs non-orphans: Beta GLMM with a logit link function

      Only orphan population: Beta GLMM with a logit link function

    b) Frequency of negative interactions:
      
       Orphan vs non-orphans: Negative Binomial GLM with a log link function

       Only orphan population: GLM 
