## Tech Stack  
- **Frontend (iOS):** SwiftUI + HealthKit (to collect health data)  
- **Backend:** FastAPI (to process)  
- **AI Model:** Ollama (Llama3.2:3B) for generating meal plans  

## Data Flow  
**HealthKit → iOS App → FastAPI → Ollama → Personalized Meal Plan**  

## HealthKit ↔ AI Integration Flow  
1. **User grants HealthKit permissions**  
2. **App collects:**  
   - Step count  
   - Distance run  
   - Weight/Height trends  
   - Heart Rate  
3. **Data sent to FastAPI endpoint**  
4. **AI processes data considering:**  
   - Caloric needs  
   - Macronutrient balance  
   - Food preferences  
   - Cooking time constraints  
