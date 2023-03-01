### EDA Report On Ski Resort Data
![Ski Resort Report](https://github.com/Lone2000/Ski-Resort-Report/blob/main/Ski_resort_report_img.jpg)

### Tools Used
I used data modeling technique such as Star Schema, better known as a Kimball schema. Which consisted of a Fact Table and numerous Dimension tables, where fact table consisted of the business metrics and the Dimension tables further described the business metrics in further categories. Power Query was used to clean and transform data for visualization, along with DAX formulas to create flexible measures.

### Purpose
Main goal for creation of this report was to determine and showcase which continent held the best ski resort out of the whole world. After which drilling down into european countries to find the most afforable and child friendly resort. 

### Data Modeling
I used Star Schema, to normalize the data and for organization. This was the best fit for such a dataset, the hierarchy of this relation was Top to Bottom, where Facts table was always the middle and no other Dimension table had a relationship with another table other then the Fact table.

![Data Model](https://github.com/Lone2000/Ski-Resort-Report/blob/main/model.PNG)

