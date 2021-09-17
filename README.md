# Guide
The dataset consists of $200000$ samples. The number of users $K$ is given by $K=100$.

**Please remember that the rows are for different samples, while the columns are for different users.**

The **input** for the neural network has $3K+1=301$ parameters. The dataset for the input is given by: 

1. Data_xsort_beta_nvar_Tx_12x12_Rx_6x6_NumUser_100

​		Dimension: (200000,100)		Variable:  $ \tilde{\beta}_k $ 

2. Data_xsort_tdtheta_x_Tx_12x12_Rx_6x6_NumUser_100

   Dimension: (200000,100)		Variable:  $ \tilde{\theta}_k^{\mathrm{x}} $ 

 3. Data_xsort_tdtheta_y_Tx_12x12_Rx_6x6_NumUser_100

    Dimension: (200000,100)		Variable:  $ \tilde{\theta}_k^{\mathrm{y}} $ 

 4. Data_xsort_power_Tx_12x12_Rx_6x6_NumUser_100

    Dimension: (200000,1)		Variable:  $ P $ 

The **output** for the neural network has $K=100$ parameters. The dataset for the output is given by:

​	Data_xsort_lambda_Tx_12x12_Rx_6x6_NumUser_100

​	Dimension: (200000,100)		Variable:  $ \tilde{\lambda}_k^{\mathrm{opt}} $ 

