## Predicting_and_Classifying_ASD_through_Eye-movement_Tracking_using_CV_and_ML

#### MIDS Capstone project - Computer Vision | Machine Learning
#### Makanzie Muller | Nina Hunag | Jesse He | Mohith Subbarao | Waqas Ali
------------

References
------------

Project Plan
https://docs.google.com/spreadsheets/d/1yGRvUtkHTvtxuE4s47o9nNMiNjEpHLIKpMIfPMVECRg/edit#gid=241399891

Project Intro - Presentation # 1
https://docs.google.com/presentation/d/179uAEfzJPfzm0kHQVgCDLREdzKlI9KfbssCj6gD6L8w/edit#slide=id.p

Data Sources
https://docs.google.com/document/d/19Ig2KH7a97AFvgl5OH0AKu_khc6lP2Qwmul3UMv9Rqo/edit

Project Organization
------------

    ├── README.md             <- The top-level README for developers using this project.
    ├── data
    │   ├── images            <- Data from third party sources, used is ViT and CNN
    │       ├── rev0            <- Data Split - train:test:val::0.6:0.1:0.3
    │       ├── rev1            <- Data Split - train:test::0.9:0.1
    │   ├── metadata          <- Intermediate data that has been transformed.
    │   ├── data_transformer  <- Data used for training language based transformer model
    │       ├── input.pt        <- Image coordinates saved in the fomr of tensor. Total number of coordinates are limited to 50.
    │       ├── labels.pt       <- CARS value for each image, saved in the form of tensor. 
    ├── models                <- Trained and serialized models, model predictions, or model summaries
    ├── notebooks             <- Jupyter notebooks. Naming convention is a number (for ordering),
    │                            the creator's initials, and a short `-` delimited description, e.g.
    │                            `1.0-jqp-initial-data-exploration`.
  
