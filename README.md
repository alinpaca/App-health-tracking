# App health tracking

**Product**: Health tracking and food journal mobile app to help users track their food intake (nutrition, calories, etc)

**Opportunity**: Data from the mobile app had not been analyzed or was being used in any way. There was potential to better understand the users' needs and typical use cases, and in understanding this, would potentially be able to do targetted marketing, prioritize specific app features for development, and distinguish themselves from other apps.

**Challenge**: Small dataset and data quality

**Solution**: Do exploratory data analysis and focus on key aspects of understanding who the user is and how they use the app 

## Data analysis process:
- [data cleaning and feature engineering](#data-clean-feature-eng)
- [data visualization](#data-viz)
- discussion with client on what aspects they were most interested in to focus on: analysis of previously-run campaign where a specific product was offered, in hopes of increasing user conversion
- determination of [optimal product pricing](#opt-price) for different markets
- [testing sampling techniques on imbalanced dataset](#test-techniques) to determine if we could predict which user would subscribe (shortcut to answer: we could not do this given the data sparsity and lack of features that would indicate a positive or negative result)


### <a name="data-clean-feature-eng"></a>Data cleaning and feature engineering

Brief background on this mobile app:
- enables users to sign up and state their goals (i.e. weight loss/gain, nutritional goals, eating healthier, etc)
- typical use case: user eats a food, inputs the food into the app, and app logs the food along with caloric and macronutrient data from online databases

Dataset:
- ~ 900,000 entries across 59 features

<figure>
  <figcaption>Visualization of complete and missing entries in dataset (purple: complete, yellow: missing)</figcaption>
  <img src='Images/dataset_viz.png'>
</figure>

### <a name="data-viz"></a>Data visualization

### <a name="opt-price"></a>Optimal product pricing for different markets

App developer offered a product "Q" at different price points to users

### <a name="test-techniques"></a>Predict user subscription? (No, mostly an exercise to test sampling techniques on imbalanced dataset)