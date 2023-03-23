# PredictHomePrices
# In This code i take the median of bedrooms using (math.floor) """math.floor(df.bedrooms.median())""" 
# And fit it into my missing data using fillna """df.bedrooms.fillna(median_bedrooms)""" and assign it into "df.bedrooms"
# Then i build and train my LinearRegression model """reg.fit(df[['area', 'bedrooms', 'age']], df.price)"""
# With my model i can predict home price """reg.predict([[3000,3,40]])"""
# Then i use mathematical formula to see how my model calculate price, based on my "coef" value and "intercept" value
