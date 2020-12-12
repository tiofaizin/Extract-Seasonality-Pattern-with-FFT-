# Extract Seasonality Pattern with FFT
This documentation is completely based on my medium post with the same topic. [Check this out](https://medium.com/@tiofaizintio/extract-seasonality-patterns-from-climate-data-with-fast-fourier-transform-fft-de479303f01)

### Brief Description
Meteorology students hardly experience smooth and expeditious data analysis. When comes to results, they oftentimes plunge to nebulous insights and vague conclusions. Despite how clearly the method used, meteorology students shouldn’t take the idea of being creative in handling the data for granted. The quality of results totally depends on how creative they scramble the data and extract its insights. Hence the better result quality comes the more beneficial explanation. For the practical instance, when harnessing the time series meteorological dataset on analysis, many students trivialize the existence of another possible domain on the dataset. Many students don’t treat the time series data as a signal or wave that related to many parameters such as frequency and period. In this post, I’m going to show an uncomplicated example on how we use other possible domain of time series data -which is frequency- on analyzing meteorology phenomenon encompassing its practical step-by-step methods using python programming language.

### Required Libraries
Please make sure that you already install these following libraries (**Run on Python 3**):
- Numpy
- Pandas
- Matplotlib
- Scipy
- Math
- Pylab

### Data Used
I use 37-years daily precipitation from CHIRPS which is rainfall estimates from rain gauge and satellite observations. The data has been cropped at the specific BMKG Station in Bandung, named Cemara Weather Station.

### Things might you find hard to grasp
- About the FFT Formula. Since FFT is extremely complex formula, I suggest having a look at some article about how's FFT work. [Check this gentle introduction](https://www.earlevel.com/main/2002/08/31/a-gentle-introduction-to-the-fft/#:~:text=The%20FFT%20works%20by%20requiring,and%20multiplication%20is%20not%20needed.)
- After applying FFT to your data, you will probably confused with the step afterward as mentioned in the jupyter notebook that the FFT result is mirrored. [Why FFT is mirrored?](https://dsp.stackexchange.com/questions/4825/why-is-the-fft-mirrored)

### Licence
This is a public domain work, dedicated using [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/). Feel free to do whatever you want with it.
