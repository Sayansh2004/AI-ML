We need to tranform our data in order to feed data to the model.It can be done in two ways  : 

The very first way is Normalisation while another is standardisation

## Normalisation

It is a technique which converts every values and brought them back to the scale between 0 and 1.

## Standardisation

It is a techinique in which data is transformed in such a way that mean becomes 0 and standard deviation becomes 1.

We use standardScaler for it 

fit () - computes mean and standard deviation.
fit_transform()- Fit to data and then transform it.
transform()- Uses mean and standard deviation computed by fit.