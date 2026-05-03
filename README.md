# CS370ForeignWhispersLab
My final project for CS 370
Contains datapipeline api: Youtube and youtube_captions

✔ Re-runs automatically skip completed steps  
✔ Deterministic pipeline execution  
✔ Persistent caching layer  

---

## 📡 Observability (Logfire Tracing)

Each pipeline stage is instrumented with **Logfire spans**.

### 🔍 Live Traces

- 🟦 P1 Download  
  https://logfire-us.pydantic.dev/public-trace/2e5d94d8-0c0e-439c-80a3-779ca680ef39?spanId=9145deeb309534d3  

- 🟩 P2 Transcript  
  https://logfire-us.pydantic.dev/public-trace/e855904a-7a52-4b86-b79e-ec2efaf1818d?spanId=6133382585b02695  

- 🟨 P3 Clean  
  https://logfire-us.pydantic.dev/public-trace/2d428415-21d9-473d-bf90-71363b2c7d43?spanId=330ad2e046f613c9  

- 🟧 P4 Analyze  
  https://logfire-us.pydantic.dev/public-trace/e5525d1d-d1e7-4d10-a34b-152aba1dcef8?spanId=a12c3b570be96ac8  

- 🟥 P5 Stitch  
  https://logfire-us.pydantic.dev/public-trace/cba182d0-5596-4870-9cf8-2836acc2602d?spanId=88c4c220bb13ad66  

