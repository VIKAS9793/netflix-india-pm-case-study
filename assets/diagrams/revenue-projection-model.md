# Revenue Projection Model - Netflix India

```mermaid
xychart-beta
    title "Netflix India Revenue Projections (2024-2027)"
    x-axis ["2024 Q1", "2024 Q2", "2024 Q3", "2024 Q4", "2025 Q1", "2025 Q2", "2025 Q3", "2025 Q4", "2026 Q1", "2026 Q2", "2026 Q3", "2026 Q4", "2027 Q1", "2027 Q2", "2027 Q3", "2027 Q4"]
    y-axis "Revenue (₹ Crores)" 0 --> 400
    bar [45, 52, 58, 65, 72, 80, 88, 95, 105, 115, 125, 135, 145, 155, 165, 175]
```

## Revenue Breakdown by Source

```mermaid
pie title Revenue Sources (2027 Projection)
    "Subscription Revenue" : 70
    "Advertising Revenue" : 15
    "Partnership Revenue" : 10
    "Premium Features" : 5
```

## Subscriber Growth Projection

```mermaid
xychart-beta
    title "Netflix India Subscriber Growth (2024-2027)"
    x-axis ["2024", "2025", "2026", "2027"]
    y-axis "Subscribers (Millions)" 0 --> 30
    line [8, 15, 22, 28]
```

## ARPU Evolution

```mermaid
graph LR
    subgraph "Current State (2024)"
        Current["₹649/month<br/>Premium Plan<br/>8M subscribers"]
    end
    
    subgraph "Target State (2027)"
        Premium["₹649/month<br/>Premium Plan<br/>10M subscribers"]
        Standard["₹399/month<br/>Standard Plan<br/>12M subscribers"]
        Mobile["₹199/month<br/>Mobile Plan<br/>5M subscribers"]
        Ads["₹149/month<br/>Ad-Supported<br/>1M subscribers"]
    end
    
    subgraph "Revenue Impact"
        Total["Total Revenue<br/>₹1,750 Crores<br/>28M subscribers<br/>Weighted ARPU: ₹520"]
    end
    
    Current --> Premium
    Current --> Standard
    Current --> Mobile
    Current --> Ads
    
    Premium --> Total
    Standard --> Total
    Mobile --> Total
    Ads --> Total
    
    style Current fill:#ffebee
    style Premium fill:#e8f5e8
    style Standard fill:#e8f5e8
    style Mobile fill:#e8f5e8
    style Ads fill:#e8f5e8
    style Total fill:#4caf50
```

## Key Financial Metrics

### Revenue Growth Drivers:
1. **Subscriber Growth**: 25% YoY growth target
2. **ARPU Optimization**: Balanced pricing strategy
3. **New Revenue Streams**: Advertising and partnerships
4. **Market Penetration**: 20% market share by 2027

### Cost Structure:
- **Content Costs**: 60% of revenue
- **Infrastructure**: 15% of revenue
- **Marketing**: 20% of revenue
- **Operations**: 5% of revenue

### Profitability Timeline:
- **Break-even**: Q3 2025
- **Positive EBITDA**: Q4 2025
- **Target Margin**: 15% by 2027
