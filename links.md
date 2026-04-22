
## Demo 1

## 1.1 Text to SQL
Goal - Show that Chat can bring back a forcast but its doing so via AI Forcast
1. Ask BigQuery Via Chat - "Forecasting electricity generation low carbon and high carbon for the next 30 days" on raw table

## 1.2 Text to SQL with Q&A
Goal - Show where agent are
Goal - Show Q&A help ground the Agent
Goal - Show the agent ca use 3rd party ML models
2. Ask Agent in BigQuery via Chat - "Forecasting electricity generation, low carbon and high carbon, for the next 30 days using two different models. Have the result in one chart."

# Demo 2

Goal - Show looker Gate
2.0 Go to https://780eb09e-7dab-4076-9ec1-ecf9d8414630.looker.app/dashboards/2JmCykbwHrQzkDyrbxl2NE
2.1 Ask Following Question - "Forecasting electricity generation, low carbon and high carbon, for the next 30 days based on 1 years full history"

LookML Edit
2.2 - Remove "90 filiter" - Go to https://780eb09e-7dab-4076-9ec1-ecf9d8414630.looker.app/projects/gde_rk/files/models/gde_rk.model.lkml 


Results

Failed - https://780eb09e-7dab-4076-9ec1-ecf9d8414630.looker.app/conversations/2682a8ecd1ea4e0a97b404c45f359870
Passed - https://780eb09e-7dab-4076-9ec1-ecf9d8414630.looker.app/conversations/b355d5c064f84df98e64be52db1d6df4